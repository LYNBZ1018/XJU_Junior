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

#### 1.1翻译程序

* 翻译程序：将源程序转换成目标程序的程序，是汇编程序，编译程序以及各种变换程序的总称。
* 编译程序：将高级语言翻译成**低级语言程序**（汇编语言或机器语言）
* 目标程序：可以是介于源程序和机器语言之间的**“中间语言”**

![image-20220829131235765](https://gitee.com/lynbz1018/image/raw/master/img/20220829131236.png)

![image-20220829131307914](https://gitee.com/lynbz1018/image/raw/master/img/20220829131308.png)

​      

* **目标程序**：对源程序逐条解释执行，**不生成目标代码**

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

1. ##### 词法分析 

* 分析和识别出来单词
* 输出单词列表

![image-20220829135400433](https://gitee.com/lynbz1018/image/raw/master/img/20220829135401.png)



2. ##### 语法分析



![image-20220829140137430](https://gitee.com/lynbz1018/image/raw/master/img/20220829140138.png)



3. ##### 语义分析

* 这个10的高精度转化就是语义分析完成的

![image-20220829140837932](https://gitee.com/lynbz1018/image/raw/master/img/20220829140838.png)

4. ##### 中间代码的生成

* 便于优化
* 便于移植

![image-20220829141045430](https://gitee.com/lynbz1018/image/raw/master/img/20220829141046.png)

* 例题

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220829141215.png" alt="image-20220829141214117" style="zoom: 50%;" />

5. ##### 代码优化

* 为了得到高质量（省时间、省空间）的程序。



6. ##### 目标代码生成



![image-20220829141522431](https://gitee.com/lynbz1018/image/raw/master/img/20220829141523.png)