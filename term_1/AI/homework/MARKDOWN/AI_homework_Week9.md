# AI作业

### 刘宇诺

**学号：**20201210207



## 归结反演作业

![image-20221006141558872](https://gitee.com/lynbz1018/image/raw/master/img/20221020102849.png)

**答：**

**将已知和事实用谓词公式表示出来：**

​	(1) $\forall$ x, y, (party(x, y) $\wedge$ friend(x)) $\rightarrow$ Happy(x)

​	(2) $\forall$ x, y,  (sport(x) $\vee$ sevice(x)) $\rightarrow$ party(x, y)

​	(3) $\neg$sport(John) $\wedge$ service(John)

​	(4) $\forall$ x, service(x) $\rightarrow$ friend(x)

​	把要进行求证的结论用谓词公式表示出来并取反

​	(5) $\neg$Happy(John)

**将上述公式化成子句集：**

​	(1)  $\neg$party(x, y) $\vee$ $\neg$friend(x) $\vee$ Happy(x)

​	(2) { $\neg$sevice(x) $\vee$ party(x, y), $\neg$sport(m) $\vee$ party(m, n)}

​	(3) {$\neg$sport(John), service(John)}

​	(4) $\neg$service(x) $\vee$ friend(x)

​	(5) $\neg$Happy(John)

**应用归结原理进行归结**

​	(6) party(John, y)	(2) (3) 归结

​	(7) $\neg$friend(John) $\vee$ Happy(John)	(1)(6)归结

​	(8) friend(John)	(3)(4)归结

​	(9) Happy(John)	(7)(8)归结

​	(10) NIL	(5)(9)归结



**所以John是快乐的。**





****



## 不确定性推理作业



![image-20221020114417799](https://gitee.com/lynbz1018/image/raw/master/img/20221020114419.png)

**答：**

```markdown
CF(E2) = 0.6 * max{0, CF(E1)}
	   = 0.6 * 0.5 = 0.3

CF(E4) = 0.8 * max(0, min(CF(E2), CF(E3)))
	   = 0.8 * 0.3 = 0.24

CF1(H) = 0.7 * max(0, CF(E4))
	   = 0.7 * 0.24 = 0.168

CF2(H) = 0.9 * max(0, CF(E5))
	   = 0.9 * 0.4 = 0.36

CF1(H) >= 0, CF2(H) >= 0;
CF1,2(H) = CF1(H) + CF2(H) - CF1(H) * CF2(H)
		 = 0.168 + 0.36 - 0.168 * 0.36
		 = 0.46752
```



![image-20221020114428383](https://gitee.com/lynbz1018/image/raw/master/img/20221020114429.png)

**答：**

​	A $\cap$ B = 0.5/x1 + 0.65/x2 + 0.8/x3 + 0.9/x4 + 0.7/x5

​	A $\cup$ B = 0.85/x1 + 0.7/x2 + 0.9/x3 + 0.9/x4 + 0.77/x5

​	$\neg$A = 0.15/x1 + 0.3/x2 + 0.1/x3 + 0.1/x4 + 0.7/x5





![image-20221020235040392](https://gitee.com/lynbz1018/image/raw/master/img/20221020235041.png)

**答：**



$$\begin{bmatrix}
0.4&0.8\\
0.4&0.9\\
0.7&0.5\\
0.7&0.6\\
\end{bmatrix}$$


