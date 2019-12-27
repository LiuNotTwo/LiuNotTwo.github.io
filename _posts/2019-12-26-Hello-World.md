---
layout:     post                    # 使用的布局（不需要改）
title:      C语言结构体内字符串变量的声明和赋值              # 标题 
subtitle:   Hello World, Hello Blog #副标题
date:       2019-12-26              # 时间
author:     NotTwo                  # 作者
header-img: img/post-bg-2015.jpg    #这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - test
---

## 字符串声明与赋值
> C语言
typedef struct stu{
    char name[20];  //姓名
    int score;  //成绩
} Stu;

typedef struct stu{
    char *name;  //姓名
    int score;  //成绩
} Stu;

scanf("%s%d",students[i].name, &students[i].score);

在用scanf赋值时情形1没有问题，情形2出错。
