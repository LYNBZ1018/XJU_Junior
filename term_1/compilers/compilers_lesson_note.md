##  Compilers



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

## 一、引论

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

## 二、文法和语言



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

###### 闭包

![image-20220905134632685](https://gitee.com/lynbz1018/image/raw/master/img/20220905134633.png)





#### 2.3文法和语言的形式定义

语言的描述可以是**生成**或**识别**方式

**生成**：BNF范式是一种元语言，用来描述其它语言。

**大写字母A B ... 为非终结符**

{}  可重复

[] 可选项

![image-20220905140949034](https://gitee.com/lynbz1018/image/raw/master/img/20220905140950.png)

**识别**的方式描述语言

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220919120605.png" alt="image-20220919120604532" style="zoom:67%;" />

##### 文法定义

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220919121220.png" alt="image-20220919121219500" style="zoom:80%;" />

##### 推导定义

有一个文法，存在一对属于V*的任意符号，使得v和w在串头和串尾加上那一对符号后分别等于那个文法

则说w是v的直接推到

![image-20220919121823646](https://gitee.com/lynbz1018/image/raw/master/img/20220919121824.png)

* <u>直接推到</u>  *+: 至少一步推到*     ***: 0步或至少一步推到**

![image-20220919123119778](C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220919123119778.png)

**例子**

```markdown
Vn = {A, B};  // 定义大写字母是非终结符 Vt = {a, b}; S = A;
B->a 推导出 Bb => ab
```

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220919122540426.png" alt="image-20220919122540426" style="zoom:50%;" />



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220919124411.png" alt="image-20220919124410070" style="zoom:67%;" />

##### 句型 句子 语言

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220919130517.png" alt="image-20220919130515978" style="zoom:80%;" />

当一个语言是无穷的时候一定是**递归**实现的

如果一个语言可以有两种文法表示，则这两个文法称为**等价文法**

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220919140531284.png" alt="image-20220919140531284" style="zoom:67%;" />



#### 2.4文法和语言的分类

* 0型文法，没有要求
* 1型文法，要求右边串长**大于等于**左边

* 2型文法，<u>左部只有一个非终结符</u> `所有的大写字符 A B C ... 都是非终结符`

* 3型文法，右部没有非终结符，有的话就只有一个终结符B，在右边为右线性

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220926120451.png" alt="image-20220926120449831" style="zoom: 67%;" />



#### 2.5上下文无关文法及其语法树

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220926123511911.png" alt="image-20220926123511911" style="zoom:67%;" />

![image-20220926125123247](https://gitee.com/lynbz1018/image/raw/master/img/20220926125124.png)

**语法树**

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220926125533.png" alt="image-20220926125532003" style="zoom:80%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220926125602949.png" alt="image-20220926125602949" style="zoom:80%;" />

短语 - 简单短语 - 句柄

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220926130317.png" alt="image-20220926130316141" style="zoom:80%;" />

##### 必考题 例题

![image-20220926132559539](https://gitee.com/lynbz1018/image/raw/master/img/20220926132600.png)

**注意括号也要写**

![image-20220926140046355](https://gitee.com/lynbz1018/image/raw/master/img/20220926140047.png)



##### 文法二义性

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220926140400764.png" alt="image-20220926140400764" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220926141118410.png" alt="image-20220926141118410" style="zoom:80%;" />



#### 2.6句型分析

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221010122203.png" alt="image-20221010122202354" style="zoom:67%;" />



**多余规则**

![image-20221010123603874](https://gitee.com/lynbz1018/image/raw/master/img/20221010123605.png)

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221010124554897.png" alt="image-20221010124554897" style="zoom:67%;" />

**有害规则**

![image-20221010123614897](https://gitee.com/lynbz1018/image/raw/master/img/20221010123616.png)



## 三、词法分析

**Week7**

`2022/10/10`



<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221010124809071.png" alt="image-20221010124809071" style="zoom: 50%;" />



<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221010125330852.png" alt="image-20221010125330852" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221010125556333.png" alt="image-20221010125556333" style="zoom:67%;" />

### 3.2单词的描述工具

##### 正规式

![image-20221010130205052](https://gitee.com/lynbz1018/image/raw/master/img/20221010130206.png)



**例子**

![image-20221010130957321](https://gitee.com/lynbz1018/image/raw/master/img/20221010130958.png)

![image-20221010131119796](https://gitee.com/lynbz1018/image/raw/master/img/20221010131120.png)



##### 正规文法转化成正规文法

*是闭包

![image-20221010131802622](https://gitee.com/lynbz1018/image/raw/master/img/20221010131803.png)



正规式转化成正规文法

![image-20221010135031950](https://gitee.com/lynbz1018/image/raw/master/img/20221010135033.png)

### 3.3自动机

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221010135422095.png" alt="image-20221010135422095" style="zoom:50%;" />

##### 有穷自动机

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221010135637682.png" alt="image-20221010135637682" style="zoom: 67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221010140437.png" alt="image-20221010140436736" style="zoom:67%;" />



从起始 到终结点 路径就是字符串

若一个点既是初态点又是终态点，则空串是该自动机可接受

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221010140845.png" alt="image-20221010140844781" style="zoom: 67%;" />

例题

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221010141448942.png" alt="image-20221010141448942" style="zoom:67%;" />



##### 不确定的有穷自动机

![image-20221010141519639](https://gitee.com/lynbz1018/image/raw/master/img/20221010141520.png)



注意：初态有一个**从外边的射入弧**，终态有一个**同心圆**

![image-20221017120203745](https://gitee.com/lynbz1018/image/raw/master/img/20221017120204.png)





##### NFA转换成等价的DFA

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221017121257.png" alt="image-20221017121256155" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221017122234193.png" alt="image-20221017122234193" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221017122357236.png" alt="image-20221017122357236" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221017123557807.png" alt="image-20221017123557807" style="zoom:67%;" />

###### 例题

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221017124854389.png" alt="image-20221017124854389" style="zoom:67%;" />

##### DFA的简化

![image-20221017125248644](https://gitee.com/lynbz1018/image/raw/master/img/20221017125249.png)



**注意：** 一个集合 经过相同符号后到达相同的转态 也可以合并为一个

![image-20221017130340352](https://gitee.com/lynbz1018/image/raw/master/img/20221017130341.png)



##### 必考题 例题

![image-20221017133827031](https://gitee.com/lynbz1018/image/raw/master/img/20221017133828.png)

##### 正规式和有穷自动机的转换

<u>如果正规式是闭包</u> 空弧不能任意省略掉

![image-20221017140356227](https://gitee.com/lynbz1018/image/raw/master/img/20221017140357.png)

![image-20221017135751392](https://gitee.com/lynbz1018/image/raw/master/img/20221017135752.png)

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221017140216502.png" alt="image-20221017140216502" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221017141650.jpg" alt="b8aa0aa34ba432d4afec6db218698df" style="zoom: 50%;" />

![image-20221024123225957](https://gitee.com/lynbz1018/image/raw/master/img/20221024123227.png)

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221024123510.png" alt="image-20221024123509542" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221024123902519.png" alt="image-20221024123902519" style="zoom:67%;" />

![image-20221024124758524](https://gitee.com/lynbz1018/image/raw/master/img/20221024124759.png)

![image-20221024124942452](https://gitee.com/lynbz1018/image/raw/master/img/20221024124943.png)





## 四、语法分析

![image-20221024125540323](https://gitee.com/lynbz1018/image/raw/master/img/20221024125541.png)

### LL(1)文法

![image-20221024130518069](https://gitee.com/lynbz1018/image/raw/master/img/20221024130519.png)

##### FIRST集合

![image-20221024132109236](https://gitee.com/lynbz1018/image/raw/master/img/20221024132110.png)



###### 例题

可以推到出空 - 就FIRST去空  -- 都能推导出来空就并上一个空

不能推导出空 - 就写一个不写后边的

![image-20221024134021492](https://gitee.com/lynbz1018/image/raw/master/img/20221024134023.png)



##### FOLLOW集合

![image-20221024140616133](https://gitee.com/lynbz1018/image/raw/master/img/20221024140617.png)

![image-20221024140917192](https://gitee.com/lynbz1018/image/raw/master/img/20221024140918.png)

###### 例题

FOLLOW(S), 看右部有哪些有S

有S的右部，看S的右边，如果能推导出空就用First去空并上左边的Follow

不能推到出空就是S右边的First

![image-20221031122041898](https://gitee.com/lynbz1018/image/raw/master/img/20221031122129.png)

![image-20221024141423288](https://gitee.com/lynbz1018/image/raw/master/img/20221031122031.jpg)



##### SELECT集合

![image-20221031122511313](https://gitee.com/lynbz1018/image/raw/master/img/20221031122512.png)

![image-20221031122948632](https://gitee.com/lynbz1018/image/raw/master/img/20221031122949.png)

###### 例题

![image-20221031123653076](https://gitee.com/lynbz1018/image/raw/master/img/20221031123654.png)



#### 消除左递归 提取左公因子

![image-20221031132601309](https://gitee.com/lynbz1018/image/raw/master/img/20221031132602.png)

![image-20221031133739121](https://gitee.com/lynbz1018/image/raw/master/img/20221031133740.png)



#### 表驱动分析法

![image-20221031134702339](https://gitee.com/lynbz1018/image/raw/master/img/20221031134703.png)



##### 题型

先进行改写 - 判别是否是LL1文法

![image-20221031134940838](https://gitee.com/lynbz1018/image/raw/master/img/20221031134942.png)

![image-20221031135030886](https://gitee.com/lynbz1018/image/raw/master/img/20221031135032.png)

![image-20221031135132049](https://gitee.com/lynbz1018/image/raw/master/img/20221031135133.png)

![image-20221031140406186](https://gitee.com/lynbz1018/image/raw/master/img/20221031140407.png)