---
layout:     post
title:      "统计方法通用符号与缩写"
subtitle:   "f(x|μ，σ^2)"
date:       2017-08-02 10:00:00
author:     "Xiaotong"
header-img: "img/in-post/stats-symbols.jpg"
header-mask: 0.3
catalog:    true
tags:
- 统计学
---

# 参数（parameter）

* 描述**总体特征**的数量称为参数，用[希腊字母](https://baike.baidu.com/item/%E5%B8%8C%E8%85%8A%E5%AD%97%E6%AF%8D/4428067?fr=aladdin)表示，如总体均值、总体标准差；
* 因为总体包括全部数据，所以参数是固定值，为常数；
* 常用参数如下：

| 符号      | 名称                                       |
| ------- | ---------------------------------------- |
| α       | [检验水准](https://baike.baidu.com/item/%E6%B0%B4%E5%B9%B3a%E6%A3%80%E9%AA%8C/19098852?fr=aladdin)；[显著性水平](https://baike.baidu.com/item/%E6%98%BE%E8%91%97%E6%80%A7%E6%B0%B4%E5%B9%B3)；[第一类错误（拒真）的概率](https://baike.baidu.com/item/%E7%AC%AC%E4%B8%80%E7%B1%BB%E9%94%99%E8%AF%AF) |
| β       | 总体回归系数；第二类错误（纳伪）的概率                      |
| 1-α     | 可信度；[置信度](https://baike.baidu.com/item/%E7%BD%AE%E4%BF%A1%E5%BA%A6) |
| 1-β     | 检验效能；[把握度](https://baike.baidu.com/item/%E6%8A%8A%E6%8F%A1%E5%BA%A6) |
| v（df）   | [自由度](https://baike.baidu.com/item/%E8%87%AA%E7%94%B1%E5%BA%A6/5936984?fr=aladdin) |
| π       | 总体率                                      |
| μ       | 总体均值                                     |
| ρ       | 总体相关系数                                   |
| ∑       | 求和                                       |
| σ       | 总体标准差                                    |
| $$σ^2$$ | 总体方差                                     |
| $$χ^2$$ | $$χ^2$$检验的统计量                            |

# 统计量（statistic）

* 描述**样本特征**的数量称为统计量，用[拉丁字母](https://baike.baidu.com/item/%E6%8B%89%E4%B8%81%E5%AD%97%E6%AF%8D/1936851?fr=aladdin)表示，如样本平均值，样本标准差；
* 因为样本的随机性，所以统计量是估计值，为变量；
* 常用统计量如下：

| 符号                              | 名称                                       |
| ------------------------------- | ---------------------------------------- |
| A                               | $$χ^2$$检验中的实际频数                          |
| a,b,c,d                         |                                          |
| a                               | 样本回归直线在Y轴上的截距                            |
| b                               | 样本回归系数                                   |
| C                               | 校正数；常数；$$χ^2$$检验中的列数                     |
| CI（confidence interval）         | [可信区间](https://en.wikipedia.org/wiki/Confidence_interval) |
| CL                              | 可信限                                      |
| CV                              | [变异系数](https://baike.baidu.com/item/%E5%8F%98%E5%BC%82%E7%B3%BB%E6%95%B0/6463621?fr=aladdin) |
| d                               |                                          |
| f(x)                            | 连续型分布密度函数；                               |
| f                               |                                          |
| G                               | 几何均数；                                    |
| H                               | 调和均数；                                    |
| $$H_0$$（null hypothesis）        | [零假设](https://baike.baidu.com/item/%E9%9B%B6%E5%81%87%E8%AE%BE/8078898) |
| $$H_1$$（alternative hypothesis） | [备择假设](https://baike.baidu.com/item/%E5%A4%87%E6%8B%A9%E5%81%87%E8%AE%BE/3645727?fr=aladdin) |
| i                               |                                          |
| L                               |                                          |
| M（sample median）                | 中位数                                      |
| N                               |                                          |
| n                               | 样本含量；各样本含量的综合                            |
| P                               | 概率                                       |
| P(1)                            | 单侧检验的概率                                  |
| P(2)                            | 双侧检验的概率                                  |
| Px                              | 第x百分位数                                   |
| P                               | 样本率                                      |
| R                               | 极差（range）；样本相关系数；$$χ^2$$检验中的行数           |
| r                               | [样本相关系数](https://baike.baidu.com/item/%E6%A0%B7%E6%9C%AC%E7%9B%B8%E5%85%B3%E7%B3%BB%E6%95%B0) |
| RR（relative risk）               | [相对危险度](https://baike.baidu.com/item/%E7%9B%B8%E5%AF%B9%E5%8D%B1%E9%99%A9%E5%BA%A6) |
| s                               |                                          |
| $$S^2$$                         |                                          |
| sb                              |                                          |
| S02                             |                                          |
| sd                              |                                          |
| s-d                             |                                          |
| sp                              |                                          |
| Sp1-p2                          |                                          |
| sX?                             |                                          |
| **SD**（Standard Deviation）      | [标准差](https://baike.baidu.com/item/%E6%A0%87%E5%87%86%E5%B7%AE) |
| **SE**（Standard Error）          | [标准误](https://baike.baidu.com/item/%E6%A0%87%E5%87%86%E8%AF%AF) |
| T                               |                                          |
| t                               | t检验的统计量                                  |
| u                               |                                          |
| X                               | 变量；变量值；观察值；回归中的自变量                       |
| x                               |                                          |
| $$X_i$$                         | 变量X的第i个观察值；第i个变量                         |
| $$X_0$$                         | 假定均数                                     |
| X                               |                                          |
| Y                               | 变量；变量值；观察值；回归中的因变量                       |
| y                               |                                          |
|                                 |                                          |

# 说明

* 符号上有“^”表示估计值
* 符号上有“-”表示平均值
* 内容不断补充中
* markdown的math表达式在web上渲染不出来，正在寻找解决方案