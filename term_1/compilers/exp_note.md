# 编译原理实验

  

## Week1

`2022/9/2`



1. 编译型语言 vs 解释型语言

![image-20220902103755861](https://gitee.com/lynbz1018/image/raw/master/img/20220902103757.png)



2. 编译-解释型语言

![image-20220902103935558](https://gitee.com/lynbz1018/image/raw/master/img/20220902103936.png)



### 实验内容

![image-20220902104146068](https://gitee.com/lynbz1018/image/raw/master/img/20220902104147.png)



##### C++

```c++
#include <iostream>
#include <fstream>
#include <time.h>

using namespace std;

const int N = 1000;

int a[N][N];
int res[N][N];

void matrix()
{
	for (int i = 0; i < N;i ++ )
	{
		for (int j = 0; j < N; j ++ )
		{
			int tmp = 0;
			for (int k = 0; k < N; k ++ )
			{
				tmp += a[i][k] * a[k][i];
			}
			res[i][j] = tmp;
		}
	}
}

double test()
{
	time_t start,stop;
    start = clock();
    matrix();
    stop = clock();
    double t = (double)(stop - start) / CLOCKS_PER_SEC;
    printf("%.4fs\n", t);
    return t;
}

int main()
{
	ifstream fin("D:/xjuexp/matrix1000");
	for (int i = 0; i < N; i ++ )
	{
		for (int j = 0; j < N; j ++ )
		{
			fin >> a[i][j];
		}
	}
	fin.close();
	
	double sum = 0;
	for (int i = 0; i < 10; i ++ )
	{
		sum += test();
	}
	printf("avg:%.4f\n", sum / 10.0);
	
	return 0;
}
```



##### Java

```java
package compilers;

import java.awt.*;
import java.io.BufferedReader;
import java.io.FileReader;
import java.io.IOException;
import java.util.ArrayList;

public class exp1 {
    public static void main(String[] args) throws IOException {
        BufferedReader bf = new BufferedReader(new FileReader("D:\\xjuexp\\matrix1000.txt"));
        String textLine = new String();
        String str = new String();

        while ((textLine = bf.readLine()) != null) {
            str += textLine + ",";
        }

        String[] numbers = str.split(",");
        int[][] a = new int[numbers.length][numbers.length];
        String[] stmp = null;
        for(int i = 0; i < numbers.length; i++) {
            stmp = numbers[i].split(" ");
            for(int j = 0; j < numbers.length; j++) {
                a[i][j] = Integer.parseInt(stmp[j]);
            }
        }

        Tool tool = new Tool();
        tool.exp(a);
    }
}

class Tool {
    void matrix(int a[][], int res[][]) {
        for (int i = 0; i < a.length; i ++ ) {
            for (int j = 0; j < a[0].length; j ++ ) {
                int tmp = 0;
                for (int k = 0; k < a[0].length; k ++ ) {
                    tmp += a[i][k] * a[k][i];
                }
                res[i][j] = tmp;
            }
        }
    }

    double test(int a[][], int res[][]) {
        long start = System.nanoTime();
        matrix(a, res);
        long end = System.nanoTime();
        return (double) (end - start) / 1000000000l;
    }

    void exp(int a[][]) {
        double sum = 0;
        int[][] res = new int[a.length][a[0].length];
        for (int i = 0; i < 10; i ++ ) test(a, res);  // 先计算10次

        for (int i = 0; i < 10; i ++ ) {
            double t = test(a, res);
            System.out.printf("%.4fs\n", t);
            sum += t;
        }
        System.out.printf("avg:%.4fs", (sum / 10));
    }
}

```



##### Python

```python
import time
import numpy as np

N = 1000
a = [[0 for col in range(N)] for row in range(N)]
b = [[0 for col in range(N)] for row in range(N)]

def readfile():
    Efield = []
    with open("matrix1000.txt", 'r') as file_to_read:
        while True:
            lines = file_to_read.readline()
            if not lines:
                break
            E_tmp = [int(i) for i in lines.split()]
            Efield.append(E_tmp)
        Efield = np.array(Efield)
    return Efield

def mul():
    readfile()
    start = time.time()
    for d in range(0, N):
        for e in range(0, N):
            b[d][e] = 0
            for c in range(0, N):
                b[d][e] += (a[d][c] * a[c][e])
    end = time.time()
    t = end - start
    print('%.4f' % t)
    return t

def main():
    sum = 0
    for i in range(0, 10):
        sum += mul()
    print('avg=%.4f' % (sum / 10));

if __name__ == '__main__':
    main()
```



## Week3

* 词法分析器的任务
  * 从字符流到记号流： 编码所识别的词法单元

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220916101643889.png" alt="image-20220916101643889" style="zoom:67%;" />

* 词法分析器的实现

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220916102505603.png" alt="image-20220916102505603" style="zoom:67%;" />



* 标志符

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220916103755866.png" alt="image-20220916103755866" style="zoom:67%;" />



* 关键字

![image-20220916103824306](https://gitee.com/lynbz1018/image/raw/master/img/20220916103825.png)

#### 实验内容

```bash
gcc -E hello.c -o hello.i  // 预处理
gcc -S hello.i -o hello.s  // 编译
gcc -C hello.s -o hello.o  // 汇编
gcc hello.o -o hello

gcc hello.c -o hello  // 一步到位

gcc hello.c -O2 hello2  // 进行二级优化
```



![image-20220916112527340](https://gitee.com/lynbz1018/image/raw/master/img/20220916112528.png)

`-O2` 进行二级优化

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220916112559066.png" alt="image-20220916112559066" style="zoom:67%;" />