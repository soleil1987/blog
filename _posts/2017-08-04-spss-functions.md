---
layout:     post
title:      "SPSS函数总结"
subtitle:   "CDF.NORMAL(quant, mean,stddev)"
date:       2017-08-04 18:00:00
author:     "Xiaotong"
header-img: "img/in-post/post-bg-os-metro.jpg"
header-mask: 0.3
catalog:    true
tags:
- 统计学
- spss
---

# 函数调用



# 常用函数

## 算术函数

| 函数名     | 功能   | 举例   |
| ------- | ---- | ---- |
| Abs()   |      |      |
| Sqrt()  |      |      |
| Sin()   |      |      |
| Cos()   |      |      |
| Exp()   |      |      |
| Ln()    |      |      |
| Lg10()  |      |      |
| Rnd()   |      |      |
| Trunc() |      |      |
| Mod()   |      |      |



## 统计函数

| 函数名        | 功能   | 举例   |
| ---------- | ---- | ---- |
| Mean()     |      |      |
| Sd()       |      |      |
| Variance() |      |      |
| Sum()      |      |      |
| Cfvar()    |      |      |
| Max()      |      |      |
| Min()      |      |      |



## 与分布相关的函数

| 函数名                     | 功能   | 距离   |
| ----------------------- | ---- | ---- |
| Rv.Normal(x,y) x=标准差    |      |      |
| Rv.Uniform(x,y)         |      |      |
| Rv.分布名                  |      |      |
| **CDF.MORMAL(x,m,s)**   |      |      |
| **IDF.NORMAL(p,m,s)**   |      |      |
| **CDF.分布名(x,参数,...)**   |      |      |
| IDF.分布名(p,参数,...) 0≤p≤1 |      |      |



## 查找函数

| 函数名                       | 功能   | 举例   |
| ------------------------- | ---- | ---- |
| Rang(变量名,x1,x2) ,其中 x1≤x2 |      |      |
| Any(变量名,x1,x2,..),        |      |      |



## 字符串函数

| 函数名                  | 功能   | 举例   |
| -------------------- | ---- | ---- |
| Concat(s1,s2,...)    |      |      |
| Index(s1,s2)         |      |      |
| Length(s)            |      |      |
| Lower(s)             |      |      |
| Upcse(s)             |      |      |
| Char.Lpad(s,x,c)     |      |      |
| Char.Rpad(s,x,c)     |      |      |
| Ltrim(s)             |      |      |
| Rtrim(s)             |      |      |
| Char.Substr(s,x1,x2) |      |      |



## 日期函数

| 函数名               | 功能   | 举例   |
| ----------------- | ---- | ---- |
| Date.Dmy(d,m,y)   |      |      |
| Date.Qyr(q,y)     |      |      |
| Date.Yrday(y,x)   |      |      |
| Xdate.Mday(日期型变量) |      |      |
| Xdate.Jday(日期型变量) |      |      |
| Xdate.Week(日期型变量) |      |      |



## 缺失值函数

| 函数名                  | 功能   | 举例   |
| -------------------- | ---- | ---- |
| Missing(变量名)         |      |      |
| Sysmis(变量名)          |      |      |
| Nmiss(变量名1,变量名2,...) |      |      |
| Value(变量名)           |      |      |



## 显著性

| 函数名                  | 功能   | 举例   |
| -------------------- | ---- | ---- |
| Sig.Chisq(quant,df)  |      |      |
| Sig.F(quant,df1,df2) |      |      |



## 其他函数

| 函数名          | 功能   | 举例   |
| ------------ | ---- | ---- |
| Lag(变量名,n)   |      |      |
| number(s,格式) |      |      |
| String(x,格式) |      |      |

