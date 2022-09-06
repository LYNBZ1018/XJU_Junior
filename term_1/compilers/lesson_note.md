## Compilers



### 参考书目

![image-20220829125342280](https://gitee.com/lynbz1018/image/raw/master/img/20220829125343.png)



![image-20220829125355326](https://gitee.com/lynbz1018/image/raw/master/img/20220829125356.png)



### 课程简介

* 主要讲十章

![image-20220829125732456](https://gitee.com/lynbz1018/image/raw/master/img/20220829125733.png)

* 课时分配

![image-20220829125815134](https://gitee.com/lynbz1018/image/raw/master/img/20220829125816.png)



## Week 1

`2022/8/29`

### 一、引论

#### 1.1翻译程序 定义

* 翻译程序：将源程序转换成目标程序的程序，是汇编程序，编译程序以及各种变换程序的总称。
* 编译程序：将高级语言翻译成**低级语言程序**（汇编语言或机器语言）
* 目标程序：可以是介于源程序和机器语言之间的**“中间语言”**

![image-20220829131235765](https://gitee.com/lynbz1018/image/raw/master/img/20220829131236.png)

![image-20220829131307914](https://gitee.com/lynbz1018/image/raw/master/img/20220829131308.png)

​      

* **目标程序**：对源程序逐条解释执行，**不生成目标代码**
* 翻译程序：汇编程序、编译程序、解释程序

![image-20220829132019695](https://gitee.com/lynbz1018/image/raw/master/img/20220829132020.png)

* 编译程序 - C语言

![image-20220829133656523](https://gitee.com/lynbz1018/image/raw/master/img/20220829133657.png)

* 解释程序 - python

![image-20220829133726403](https://gitee.com/lynbz1018/image/raw/master/img/20220829133727.png)

* 编译-解释程序 Java

![image-20220829133948287](https://gitee.com/lynbz1018/image/raw/master/img/20220829133949.png)



##### 课堂习题

* **汇编程序**相对编译程序**工作更简单**

* **解释程序**跟适合**规模较小**的程序

****

#### 1.2编译过程和编译程序的结构

* 编译过程： 将高级语言翻译成**等价目标程序**的过程。
  * 词法分析 - 语法分析 - 语义分析 - 中间代码生成 - 代码优化 - 目标代码生成

![image-20220829134435727](https://gitee.com/lynbz1018/image/raw/master/img/20220829134436.png)

##### 编译过程

##### 1.词法分析 

* 分析和识别出来单词
* 输出单词列表

![image-20220829135400433](https://gitee.com/lynbz1018/image/raw/master/img/20220829135401.png)



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905124205.png" alt="image-20220905124203945" style="zoom:33%;" />



##### 2.语法分析



![image-20220829140137430](https://gitee.com/lynbz1018/image/raw/master/img/20220829140138.png)



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905123109.png" alt="image-20220905123108750" style="zoom:33%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905123521.png" alt="image-20220905123519929" style="zoom:33%;" />



##### 3.语义分析

* 进行语义审查

* 这个10的高精度转化就是语义分析完成的

![image-20220829140837932](https://gitee.com/lynbz1018/image/raw/master/img/20220829140838.png)



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905123315.png" alt="image-20220905123314797" style="zoom:25%;" />



##### 4.中间代码的生成

* 便于优化
* 便于移植

![image-20220829141045430](https://gitee.com/lynbz1018/image/raw/master/img/20220829141046.png)

* 例题

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220829141215.png" alt="image-20220829141214117" style="zoom: 50%;" />

##### 5.代码优化

* 为了得到高质量（省时间、省空间）的程序。



##### 6.目标代码生成

* 绝对指令代码：直接装入内存中确定的位置
* 可重定位的指令代码：需要时装入内存
* 汇编指令代码



![image-20220829141522431](https://gitee.com/lynbz1018/image/raw/master/img/20220829141523.png)



* 结构图
  * 六个阶段 八个功能

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905120634.png" alt="image-20220905120633613" style="zoom: 33%;" />



##### 表格管理 出错处理

表格管理：表示编译程序具有表格管理功能1

出错处理： 语义错误不一定能全部找到

![image-20220905120549955](https://gitee.com/lynbz1018/image/raw/master/img/20220905120551.png)

##### Def

###### 遍

遍：从头到尾扫描一次成为一遍

![image-20220905121613610](https://gitee.com/lynbz1018/image/raw/master/img/20220905121614.png)

###### 前端后端

前端：与源程序有关的部分，即编译过程的前五个部分

后端：与目标机有关的部分，即目标程序代码生成和优化

![image-20220905121921576](https://gitee.com/lynbz1018/image/raw/master/img/20220905121922.png)

##### 编译程序结构

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905122431.png" alt="image-20220905122430127" style="zoom:50%;" />





## Week 2

`2022/9/5`

### 二、文法和语言



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905125441.png" alt="image-20220905125439945" style="zoom:33%;" />



#### 2.1语言概述

* 语言：是在某个特定的字母表上的符号串组成的集合。
  * 是由句子组成的集合，是由一组记号组成的集合。



* 语法：构成语言句子的各个记号之间的组合规律
* 语义：表示各个记号的特定含义
* 语用：表示在各个记号所出现的行为中，它的来源、使用和影响



* 形式语言：只考虑语法

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905131036.png" alt="image-20220905131035200" style="zoom:50%;" />



#### 2.2符号和符号串

* 字母表：符号的非空有限集合
* 符号：字母表中的元素，不能分解的最小单位
* 符号串：字母表中符号组成的任何又穷序列
* 符号串集合：字母表上的符号串组合成的集合

* 空串：不包含任符号的符号串

​     

* 前缀： abc，前缀有 **空串**、a、ab、abc

* 后缀、子串
* 真前缀，真后缀：不和自身相等的非空前缀或后缀



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905132344.png" alt="image-20220905132342997" style="zoom:50%;" />



##### 符号串的运算



![image-20220905134632685](https://gitee.com/lynbz1018/image/raw/master/img/20220905134633.png)



#### 2.3文法和语言的形式定义

BNF范式是一种元语言，用来描述其它语言。



![image-20220905140949034](https://gitee.com/lynbz1018/image/raw/master/img/20220905140950.png)



