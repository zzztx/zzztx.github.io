---
layout: post
title:  常用知识点。
date:   2022-01-01 00:00:00 +0300
image:  important_01.jpg
tags:   Important
---
力扣常用知识点。



## 算法.

##### 排序：

```go
//int,float64,strings排序
s := []int{4, 2, 3, 1}
sort.Ints(s)
fmt.Println(s) // [1 2 3 4]

//结构体自定义排序
family := []struct {
    Name string
    Age  int
}
sort.SliceStable(family, func(i, j int) bool {
    return family[i].Age < family[j].Age
})
```

##### max&min:

```go
const INT_MAX = int(^uint(0) >> 1)
const INT_MIN = ^INT_MAX

//无符号最小就是0
const UINT_MIN uint = 0
const UINT_MAX = ^uint(0)
```

##### 结构体定义:

```go
type MinStack struct {
    stack []int
    min []int
}


func Constructor() MinStack {
    return MinStack{
        stack:[]int{},
        min:[]int{INT_MAX},
    }
}
```



