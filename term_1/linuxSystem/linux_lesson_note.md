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

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220901113420.png" alt="image-20220901113419242" style="zoom:67%;" />

* shutdown && reboot

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220901113904.png" alt="image-20220901113903205" style="zoom:67%;" />



## Week2

`2022/9/5`

### 文件系统及常用命令



#### 本章内容

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905164039.png" alt="image-20220905164038056" style="zoom:50%;" />



* 文件的成分
  * 索引节点
  * 数据

#### 文件的命名

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20220905165917.png" alt="image-20220905165916403" style="zoom:67%;" />

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

##### ls

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

##### mv

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221010154401.png" alt="image-20221010154359857" style="zoom: 50%;" />

##### rm

![image-20221010155700249](https://gitee.com/lynbz1018/image/raw/master/img/20221010155701.png)



##### grep

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221010160150.png" alt="image-20221010160148960" style="zoom:50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221010160239680.png" alt="image-20221010160239680" style="zoom:80%;" />



##### sort

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221010163056.png" alt="image-20221010163055382" style="zoom:67%;" />

`ls -la | sort -rnk 5`



##### mkdir

![image-20221010163742468](https://gitee.com/lynbz1018/image/raw/master/img/20221010163743.png)

`mkdir -p doc/text/text/`

`mkdir -p /xju/xxxy/{jsjx, dzx, xxx}`



### 基本权限管理



#### chown

属主 属

```bash
chown liu test.txt

chown liu:doc test.txt
```



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221010165738.png" alt="image-20221010165736919" style="zoom:67%;" />

#### 文件权限

```bash
chmod a+x stu.txt  #所有的加
chmod g-w,o+w stu.txt
chmod 666 stu.txt
u 用户
g 组
o 其他
a 全部
```



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221010170355.png" alt="image-20221010170353980" style="zoom:80%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221010170419.png" alt="image-20221010170418858" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221013103619045.png" alt="image-20221013103619045" style="zoom:50%;" />

##### umask

默认权限减去umash就是创建时的权限

![image-20221013103708470](https://gitee.com/lynbz1018/image/raw/master/img/20221013103709.png)



### vim

```markdown
vi的命令（常用） 
一、定位：
nG：光标移至第n行首 
n+：光标下移n行 
n-：光标上移n行 
$：光标移至当前行尾 
0或^:光标移至当前行首
G:光标移至最后一行
gg：光标移至第一行


二、插入文本类命令 
i ：在光标前
I ：在当前行首 
a：光标后 
A：在当前行尾 
o：在当前行之下新开一行
O：在当前行之上新开一行 


三、删除命令
d0：删至行首 
d$：删至行尾 
dd：删除当前行
ndd：删除当前行及其后n-1行 
dnG：删除当前行至第n行


四、搜索及替换命令
/pattern：从光标开始处向文件尾搜索pattern 
?pattern：从光标开始处向文件首搜索pattern 
n：在同一方向重复上一次搜索命令 
N：在反方向上重复上一次搜索命令 
：n1,n2s/p1/p2/g：将第n1至n2行中所有p1均用p2替代 
：g/p1/s//p2/gc：将文件中所有p1均用p2替换 


五、复制、移动命令
：n1,n2 co n3：将n1行到n2行之间的内容拷贝到第n3行下 
：n1,n2 m n3：将n1行到n2行之间的内容移至到第n3行下 


六、恢复命令
u   取消刚才的操作。

七、退出
：w  保存当前文件 
: wq 保存当前文件并退出 
：q  退出vi 
：q! 不保存文件并退出vi 
: wq！ 强制保存当前文件并退出 

八、同时编辑多个文件
：e 文件名   编辑指定文件
：n    编辑下一个文件
：N    编辑上一个文件
```



### 文件链接

```bash
ln test.txt jsj20-1/test1.txt  # 硬链接
ln -s test.txt stu.info/test2.txt  # 软链接
readlink test2.txt  # 查看链接字符
```



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221017155959.png" alt="image-20221017155958546" style="zoom: 67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221017162809.png" alt="image-20221017162808636" style="zoom:80%;" />



<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221017165256314.png" alt="image-20221017165256314" style="zoom:67%;" />

## Week9

`2022/10/24`

### 多用户

![image-20221024160312400](https://gitee.com/lynbz1018/image/raw/master/img/20221024160313.png)

![image-20221024161014146](https://gitee.com/lynbz1018/image/raw/master/img/20221024161015.png)

![image-20221024161449091](https://gitee.com/lynbz1018/image/raw/master/img/20221024161450.png)

![image-20221024162343575](https://gitee.com/lynbz1018/image/raw/master/img/20221024162344.png)

![image-20221024162405692](https://gitee.com/lynbz1018/image/raw/master/img/20221024162406.png)



#### 添加用户

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221024163214.png" alt="image-20221024163213138" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221024163231.png" alt="image-20221024163230405" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221024163642.png" alt="image-20221024163641070" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221024163650.png" alt="image-20221024163649090" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221024163832.png" alt="image-20221024163831267" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221024163840.png" alt="image-20221024163839784" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221024163848.png" alt="image-20221024163847363" style="zoom:67%;" />



#### 组账户管理

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221024165858.png" alt="image-20221024165857336" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221024165925.png" alt="image-20221024165924605" style="zoom:67%;" />

![image-20221024165931546](https://gitee.com/lynbz1018/image/raw/master/img/20221024165932.png)

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221024165941.png" alt="image-20221024165939907" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221024165951.png" alt="image-20221024165950196" style="zoom:67%;" />





### 用户功能和查询命令

##### W

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221027112431.png" alt="image-20221027112428960" style="zoom:67%;" />

##### id

![image-20221027112508550](https://gitee.com/lynbz1018/image/raw/master/img/20221027112509.png)

##### whoami

![image-20221027112524141](https://gitee.com/lynbz1018/image/raw/master/img/20221027112525.png)

##### lastlog

![image-20221027112542262](https://gitee.com/lynbz1018/image/raw/master/img/20221027112543.png)

##### sudo

![image-20221027112617647](https://gitee.com/lynbz1018/image/raw/master/img/20221027112618.png)





#### 特殊权限

![image-20221027112953072](https://gitee.com/lynbz1018/image/raw/master/img/20221027112954.png)



**rwxrws--- 2770**

![image-20221027113018271](https://gitee.com/lynbz1018/image/raw/master/img/20221027113019.png)

![image-20221031161816412](https://gitee.com/lynbz1018/image/raw/master/img/20221031161817.png)

![image-20221031161836395](https://gitee.com/lynbz1018/image/raw/master/img/20221031161903.png)

![image-20221031161856875](https://gitee.com/lynbz1018/image/raw/master/img/20221031161858.png)





## 进程控制

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221031164751.png" alt="image-20221031164749823" style="zoom:80%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221031164800.png" alt="image-20221031164759233" style="zoom:80%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221031164807.png" alt="image-20221031164805758" style="zoom:80%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221031164814.png" alt="image-20221031164812900" style="zoom:80%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221031164820.png" alt="image-20221031164818979" style="zoom:80%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221031164826.png" alt="image-20221031164825090" style="zoom:80%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221031170117.png" alt="image-20221031170115804" style="zoom:80%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221031172059.png" alt="image-20221031170123556" style="zoom:67%;" />

## 本地存储管理

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221107155813463.png" alt="image-20221107155813463" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221107155829003.png" alt="image-20221107155829003" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221107155911775.png" alt="image-20221107155911775" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221107160208.png" alt="image-20221107160041275" style="zoom:80%;" />



## 软件包管理

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221110101458305.png" alt="image-20221110101458305" style="zoom:50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221110102122959.png" alt="image-20221110102122959" style="zoom:67%;" />



### RPM

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221110104502.png" alt="image-20221110104500650" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221110104527.png" alt="image-20221110104525298" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221110104630007.png" alt="image-20221110104630007" style="zoom:67%;" />



### yum

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221110111723.png" alt="image-20221110111722245" style="zoom:67%;" />



### tar

```bash
tar cvf filebak.tar file_bak/
tar czvf filebak.tar.gz file_bak/   # gzip 进行压缩
du -sh filebak*  # 查看文件大小
```



<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221114162737887.png" alt="image-20221114162737887" style="zoom:67%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221114162805724.png" alt="image-20221114162805724" style="zoom:50%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221114163704.png" alt="image-20221114163703614" style="zoom: 50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221114164527747.png" alt="image-20221114164527747" style="zoom: 67%;" />



## 六、计划任务和管理服务

### 守护进程

都是以d结尾

```bash
systemctl status firewalld
```



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221121155853.png" alt="image-20221121155815846" style="zoom:50%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221121155837.png" alt="image-20221121155836861" style="zoom:50%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221121155848.png" alt="image-20221121155847845" style="zoom:50%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221121155915.png" alt="image-20221121155914189" style="zoom:50%;" />



### crond作业

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221121160340.png" alt="image-20221121160339576" style="zoom:50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221121161515060.png" alt="image-20221121161515060" style="zoom:50%;" />



![image-20221121161342700](C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221121161342700.png)

![image-20221121161321579](https://gitee.com/lynbz1018/image/raw/master/img/20221121161322.png)

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221121163018.png" alt="image-20221121163017351" style="zoom:50%;" />

<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221121165049064.png" alt="image-20221121165049064" style="zoom:50%;" />



## 第七、系统日常维护、服务器 安全基础、防火墙



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221124110559.png" alt="image-20221124110511053" style="zoom:50%;" />



<img src="C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221124111421727.png" alt="image-20221124111421727" style="zoom:50%;" />

206页

### 禁止root用户登录

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221128155755.png" alt="image-20221128155754140" style="zoom:67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221128155900.png" alt="image-20221128155859777" style="zoom: 67%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221128155930.png" alt="image-20221128155929247" style="zoom:67%;" />

```bash
visudo  # 直接进入编辑

passwd -l root 
```

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221128160354.png" alt="image-20221128160353146" style="zoom: 67%;" />



## 八、shell

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221128164231.png" alt="image-20221128164230617" style="zoom: 67%;" />

![image-20221128165811820](C:%5CUsers%5Clyn95%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221128165811820.png)

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221128170812.png" alt="image-20221128170811531" style="zoom:67%;" />



```bash
#! /bin/bash
chmod +x test.sh
./test.sh

# 注释
:<<EOF
多
行
EOF


```

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221205160629.png" alt="image-20221205160628198" style="zoom:67%;" />

```bash
cat > test.sh
echo $1 $2 $3
echo $0

bash test.sh hello world nihao
hello world nihao
test.sh
```



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221205161649.png" alt="image-20221205161648614" style="zoom: 67%;" />

```bash
shift x 位置参数向左移动x位
cat > test.sh
echo $1
shift 
echo $1
shift
echo $1
echo $0

bash test.sh hello world nihao
hello 
world 
nihao
test.sh
```

![image-20221205163154720](https://gitee.com/lynbz1018/image/raw/master/img/20221205163155.png)

```bash
name=jsj20-1
myclass=${name}-zyb
```



<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221205163433.png" alt="image-20221205163432400" style="zoom:50%;" />

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221205163449.png" alt="image-20221205163448134" style="zoom:50%;" />



```bash
ls *.sh

ls ?  # 匹配一个字符
ls ??   # 匹配两个字符

ls -l ex[1-4].sh  # 1 2 3 4里面的任意一个
ls -l ex[!1-4].sh  # 不是1-4的
```

<img src="https://gitee.com/lynbz1018/image/raw/master/img/20221205164414.png" alt="image-20221205164413139" style="zoom: 67%;" />

```bash
echo "\$HOME is $HOME"
echo "Today is `date`"

```

![image-20221205165643708](https://gitee.com/lynbz1018/image/raw/master/img/20221205165644.png)

![image-20221205165625364](https://gitee.com/lynbz1018/image/raw/master/img/20221205165626.png)



## 实验课大作业



281页批量添加用户



搭建服务器规划

多分区、最小化安装、非必要服务不开启、硬件安全

课本参考





# 简单复习内容

## 简答题

1、简述Linux的标准目录结构及其存放内容。

 ```markdown

 ```



 

2、在Linux如何使用设备?常用的设备名有哪些?

 ```markdown

 ```



3、使用LVM比使用固定分区有哪些优点?

 ```markdown

 ```



4、CentOS7 Linux下常用的文件系统有哪些?

 ```markdown

 ```



5、如何使用systemctl管理服务？

 ```markdown

 ```



6、简述Linux 服务器的基本安全配置?

 ```markdown

 ```



7、Linux系统中的名称补全功能是什么，它能起到什么作用?管道符的功能是什么？举例说明。

 ```markdown

 ```



8、Centos系统常用安装软件包的方式有哪几个?请分别做简单的介绍。

 ```markdown

 ```



9、Linux文件系统的3种基木权限是什么?Linux文件系统的3种特殊权限是什么?（掌握修改权限的方法）。

 ```markdown

 ```



10、Vim有哪几种工作模式?怎样进行转换?（掌握定位，删除，查询，复制和移动操作方法）

 ```markdown

 ```



## 综合题

1、关于文件的基本操作（ls，cat，mkdir，cp，mv，chmod，rm）

 ```markdown

 ```



2、shell脚本编程。（能编写简单脚本并执行，能读懂脚本）

 ```markdown

 ```



3、多用户管理。（用户的添加，删除，组管理，指定管理员）.

 ```markdown

 ```
