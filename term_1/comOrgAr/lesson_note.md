# 计算机组成原理

   

## Week1

`2022/8/31`

   

### 考核标准

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220831122943.png" alt="image-20220831122941989" style="zoom: 33%;" />

### 教学内容

* 讲解**单台**计算机**完整硬件系统**的**基本组成原理**与内部运行机制和系统结构的基本概念

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220831124627.png" alt="image-20220831124626694" style="zoom:50%;" />

* 内容结构

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220831125147.png" alt="image-20220831125146627" style="zoom:50%;" />

* 学时分配

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220831125420.png" alt="image-20220831125419020" style="zoom:50%;" />

### 第一章、概论

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220831125525.png" alt="image-20220831125524443" style="zoom: 33%;" />

#### 重点

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220831125636.png" alt="image-20220831125635765" style="zoom: 33%;" />

  

#### 1.计算机性能指标

##### 利用率、总线宽度

![image-20220831133616250](https://gitee.com/lynbz1018/image/raw/master/img/20220831133617.png)

#####    时钟周期、CPI

![image-20220831131813885](https://gitee.com/lynbz1018/image/raw/master/img/20220831131815.png)

#####     MIPS

![image-20220831133535320](https://gitee.com/lynbz1018/image/raw/master/img/20220831133536.png)

##### CPI例题 ***

1. 例题1

![image-20220831134821111](https://gitee.com/lynbz1018/image/raw/master/img/20220831134822.png)

2. 例题2

![image-20220831135451281](https://gitee.com/lynbz1018/image/raw/master/img/20220831135452.png)

   

#### 2.计算机硬件系统

* 五大部件
  * 运算器、控制器、存储器、输入、输出

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220831140802.png" alt="image-20220831140800926" style="zoom:67%;" />

* 冯诺依曼结构

![image-20220831141507503](https://gitee.com/lynbz1018/image/raw/master/img/20220831141508.png)

##### 2.1运算器

* 如果有三个总线 两个输入一个输出 可以不用寄存器

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220907120530.png" alt="image-20220907120529299" style="zoom:50%;" />

##### 2.2存储器



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220907122538.png" alt="image-20220907122536813" style="zoom:67%;" />



##### 2.3控制器



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220907123006.png" alt="image-20220907123005412" style="zoom:67%;" />



##### 程序计数器PC 

* **程序的第一条指**令位于PC程序计数器中
* 获取第一条指令后，**通过增量，能够使指令自动的执行**
* 在分析指令后才有数据的地址
* 数据地址在指令中，**但是执行的时间段不同**，所以指令和数据都是二进制编码 但不会混淆

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220907130754.png" alt="image-20220907130753198" style="zoom: 80%;" />

#### 3.计算机软件

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220907134614985.png" alt="image-20220907134614985" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220907134649679.png" alt="image-20220907134649679" style="zoom:33%;" />



<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220907134715412.png" alt="image-20220907134715412" style="zoom:67%;" />



#### Amdhal定律

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220907135037.png" alt="image-20220907135035851" style="zoom:67%;" />



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220907135303.png" alt="image-20220907135302308" style="zoom:50%;" />



#### 本章小结

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220907134231.png" alt="image-20220907134230050" style="zoom:67%;" />



*****

#### 课堂习题

1.  `1s/2G = 0.5ns`

![image-20220831134252059](https://gitee.com/lynbz1018/image/raw/master/img/20220831134253.png)

2. `250 * 2 = 500; 500 * 1.2 = 600 600 / 500 = 1.2`

![image-20220831140014307](https://gitee.com/lynbz1018/image/raw/master/img/20220831140015.png)

   

​    

****



## Week2

`2022/9/7`



### 第二章、运算方法和运算器



#### 1.大纲要点

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220907135534198.png" alt="image-20220907135534198" style="zoom:50%;" />



<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220907135734548.png" alt="image-20220907135734548" style="zoom: 50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220907135750722.png" alt="image-20220907135750722" style="zoom:50%;" />



#### 2.数据与文字的表示方法



<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220907140336404.png" alt="image-20220907140336404" style="zoom:33%;" />



### Week3

`2022/9/14`

* 为甚要用二进制表示数据

![image-20220914120205262](https://gitee.com/lynbz1018/image/raw/master/img/20220914120206.png)



#### 3.数据格式：定点表示法

* 小数点位置固定
  * 纯整数
  * 纯小数

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220914120701.png" alt="image-20220914120700456" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220914120910358.png" alt="image-20220914120910358" style="zoom: 50%;" />



<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220914121345485.png" alt="image-20220914121345485" style="zoom:50%;" />

##### 原码表示法

* 用0表示 + 
* 用1表示 -
* 用8位原码表示，整数前边+0 小数后边+0

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220914122024.png" alt="image-20220914122023827" style="zoom: 50%;" />

1. 0有两种表示 +0 -0
2. 定点小数：-1 < X < 1; 定点整数：-2^n < X < 2^n
3. 与真值对应关系简单；参与复杂运算需要将数值位和符号位分开考虑。

##### 补码表示法

* 正数不变
* 负数，定点小数[2 - |x|], 定点整数[2^n - |x|]
* 整数的补码数值位 原码按位取反再加1  **从左开始按位取反最后一个1和后边的不变**

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220914125144472.png" alt="image-20220914125144472" style="zoom:50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220914125811710.png" alt="image-20220914125811710" style="zoom:67%;" />

* +0 = -0 = 0000 零有唯一表示

* 补码表示范围可以表示 -1 和 2^n
  * 因为在补码中0的表示是唯一的 原码中0有两种表示
* 补码求原码 ，对补码在求一次补码

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220914130521294.png" alt="image-20220914130521294" style="zoom:50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220914131407113.png" alt="image-20220914131407113" style="zoom:50%;" />

* 补码运算

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220914131650.png" alt="image-20220914131649413" style="zoom:67%;" />

##### 反码表示

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220914132045.png" alt="image-20220914132044271" style="zoom:50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220914132101693.png" alt="image-20220914132101693" style="zoom:50%;" />

##### 移码表示

* 0的移码：1000

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220914132406298.png" alt="image-20220914132406298" style="zoom:50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220914132557074.png" alt="image-20220914132557074" style="zoom:50%;" />

##### Summary

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220914134233122.png" alt="image-20220914134233122" style="zoom:50%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220914133335.png" alt="image-20220914133334067" style="zoom: 50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220914133454862.png" alt="image-20220914133454862" style="zoom: 50%;" />

#### 4.浮点数

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220914140709.png" alt="image-20220914140707689" style="zoom:50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220914141324246.png" alt="image-20220914141324246" style="zoom:50%;" />

##### 规格化

* 保证浮点数表示的唯一性
* 位数0.5 < X < 1 二进制的是0.1

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220914141355.png" alt="image-20220914141354045" style="zoom:50%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220914141446.png" alt="image-20220914141444912" style="zoom:50%;" />

* 看**符号位和数值位异或是1** 则是规格化的

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220921121258704.png" alt="image-20220921121258704" style="zoom: 67%;" />

##### 表示范围

计算机表示的数都是**有限的**

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220921122010.png" alt="image-20220921122009688" style="zoom:67%;" />

###### 例题

最大正数和最小负数都是对应的

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220921123511861.png" alt="image-20220921123511861" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220921131316951.png" alt="image-20220921131316951" style="zoom:50%;" />

* 溢出问题

![image-20220921124351190](https://gitee.com/lynbz1018/image/raw/master/img/20220921124352.png)

##### 数据格式 IEEE754

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220921125722.png" alt="image-20220921125721509" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220921125858583.png" alt="image-20220921125858583" style="zoom:50%;" />

**指数真值要加127变成阶码E**

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220921125502.png" alt="image-20220921125500947" style="zoom:67%;" />

###### 例题

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220921130358282.png" alt="image-20220921130358282" style="zoom: 67%;" />

#### 5.定点数的加减运算

##### 补码加法 | 减法

* `[x]补 + [y]补 = [x + y]补`补码的加法 == 加后的补码

* 符号位参与运算

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220921135558888.png" alt="image-20220921135558888" style="zoom:67%;" />

##### 溢出问题

* 两个正数加，变负数
* 两个负数加，变正数



* 双符号位检测

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220921141009570.png" alt="image-20220921141009570" style="zoom:50%;" />

* 单符号位检测

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220921141302.png" alt="image-20220921141301077" style="zoom:50%;" />