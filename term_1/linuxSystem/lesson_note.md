# Linux

  

## Week 1

`2022/8/29`

### 前言

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220829163300.png" alt="image-20220829163259906" style="zoom:50%;" />

* 三种软件模式

![image-20220829163443615](https://gitee.com/lynbz1018/image/raw/master/img/20220829163444.png)



* GNU 项目

![image-20220829165202352](https://gitee.com/lynbz1018/image/raw/master/img/20220829165203.png)

* Linux 系统

![image-20220829165239879](https://gitee.com/lynbz1018/image/raw/master/img/20220829165240.png)

* Linux的优点
  * 属于自由软件
  * 具有Unix的全部功能
  * Linux不仅提供了强大的操作系统，而且提供了丰富的应用软件。

![image-20220829165426767](https://gitee.com/lynbz1018/image/raw/master/img/20220829165427.png)



### Linux系统

  

![image-20220829165651845](https://gitee.com/lynbz1018/image/raw/master/img/20220829165652.png)

   

![image-20220829165721141](https://gitee.com/lynbz1018/image/raw/master/img/20220829165722.png)

#### 内核 Kernel

![image-20220829170008807](https://gitee.com/lynbz1018/image/raw/master/img/20220829170009.png)

![image-20220829170059631](https://gitee.com/lynbz1018/image/raw/master/img/20220829170100.png)

 

#### 发行版 Distribution



![image-20220829170313991](https://gitee.com/lynbz1018/image/raw/master/img/20220829170315.png)

![image-20220829170446726](https://gitee.com/lynbz1018/image/raw/master/img/20220829170447.png)



* 硬盘分区

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220901103252.png" alt="image-20220901103250516" style="zoom:67%;" />

* IDE接口 /dev/hd
* SATA接口 /dev/sd
* 1-4留给主分区或扩展分区使用
* 逻辑分区从5开始

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220901103349.png" alt="image-20220901103348113" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220901103624.png" alt="image-20220901103623467" style="zoom:67%;" />

* Ctrl Alt F1 创建多个虚拟控制台

![image-20220901113419242](https://gitee.com/lynbz1018/image/raw/master/img/20220901113420.png)

* shutdown && reboot

![image-20220901113903205](https://gitee.com/lynbz1018/image/raw/master/img/20220901113904.png)



## Week2

`2022/9/5`

### 文件系统及常用命令



#### 本章内容

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905164039.png" alt="image-20220905164038056" style="zoom:50%;" />



* 文件的成分
  * 索引节点
  * 数据

#### 文件的命名

![image-20220905165916403](https://gitee.com/lynbz1018/image/raw/master/img/20220905165917.png)

#### 一些基本的文件库

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905170522.png" alt="image-20220905170521292" style="zoom:67%;" />

## Week3

`2022/9/15`

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220915101902051.png" alt="image-20220915101902051" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220915102525524.png" alt="image-20220915102525524" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220915103905299.png" alt="image-20220915103905299" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220915104214496.png" alt="image-20220915104214496" style="zoom:67%;" />

#### 文件类型

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220915113544300.png" alt="image-20220915113544300" style="zoom:50%;" />

* 目录文件

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220915113620845.png" alt="image-20220915113620845" style="zoom:50%;" />

* 设备文件
  * 字符设备 c character
  * 块设备 b block

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220915113638.png" alt="image-20220915113637621" style="zoom:50%;" />

* 符号链接文件

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220915113727028.png" alt="image-20220915113727028" style="zoom:50%;" />



## Week4

`2022/9/19`

#### 简单命令

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220919160024011.png" alt="image-20220919160024011" style="zoom:80%;" />



```markdown
su liuyunuo
su - liuyunuo  // - 会改变环境变量
```



## Week5

`2022/9/26`

#### 常用命令

![image-20220926155132798](https://gitee.com/lynbz1018/image/raw/master/img/20220926155134.png)

##### **cat**

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220926162345343.png" alt="image-20220926162345343" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220926162631798.png" alt="image-20220926162631798" style="zoom:50%;" />



```bash
cat > tmp.txt
hello world!
nihao
what's up.
#ctrl + d 结束

cat test.txt tmp.txt > fusion.txt
```

##### **more**

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220926164814590.png" alt="image-20220926164814590" style="zoom:50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220926164832182.png" alt="image-20220926164832182" style="zoom: 50%;" />

```bash
ls -a -l /etc/ | more -d 5
# -5 一屏幕显示5行 -d 更多提示信息
```



##### cp

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20220926165107006.png" alt="image-20220926165107006" style="zoom:50%;" />