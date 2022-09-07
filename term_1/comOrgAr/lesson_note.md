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