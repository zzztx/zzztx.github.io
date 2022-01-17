---
layout: post
title:  树形数据结构。
date:   2022-01-14 00:00:00 +0300
image:  algorithm_01_02.jpg
tags:   Algorithm

---

树、图、搜索以及基本的树形数据结构。提到数就不得不提到递归。

## 目录.

### 递归：

Recursion递归是{1.函数自身调用自身。2.通过函数体来进行的循环。3.以自相似的方法重读进行}

##### 递归的三个关键：

1. 重叠子问题
2. 确定递归边界
3. 保护与还原现场

![image-20220110112607310](C:\Users\zzztx\AppData\Roaming\Typora\typora-user-images\image-20220110112607310.png)

##### 递归的题型：

1. 子集
2. 组合
3. 全排列
4. 全排列Ⅱ

### 分治：

分而治之，把原问题划分成若干子问题然后解决。原问题的各个子问题都是重复同类的，分治算法一般用递归所实现，除了向下递归，还要向上合并结果。

![image-20220110212914743](C:\Users\zzztx\AppData\Roaming\Typora\typora-user-images\image-20220110212914743.png)

### 树与图：

树和递归是分不开的，树有子树，递归有子问题。

##### 完全二叉树：

只有最后一层的右边可以缺点。 

##### 二叉树的遍历：

1. 前序遍历：根左右
2. 中序遍历：左根右
3. 后续遍历：左右根
4. 层次遍历

![image-20220111102703251](C:\Users\zzztx\AppData\Roaming\Typora\typora-user-images\image-20220111102703251.png)

前序的第一个永远是树根，后续的最后一个永远是树根。前中后序遍历是递归的，是深度遍历

##### 二叉树还原：

### 图：

链表是特殊的树，树是特殊的图 

##### 图的存储方式：

1. 邻接矩阵：适用于稠密图，空间利用率不高
2. 出边数组：能到的放在后面（目前以出边数组作为图的存储学习）
3. 邻接表：和2的区别是用链表表示后面

![image-20220111202502836](C:\Users\zzztx\AppData\Roaming\Typora\typora-user-images\image-20220111202502836.png)





![image-20220111221117098](C:\Users\zzztx\AppData\Roaming\Typora\typora-user-images\image-20220111221117098.png)

