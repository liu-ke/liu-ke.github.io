---
layout: post
title: SVM_Review
categories: Theory
tags: Machine Learning
---

SVM的原理不太记得了，今天来复习一遍，题目如下

<p align="center">
<img src="../images/blog/SVM_Review.png"><br/>
图1. 题目
</p>

通过\\(\phi(\underline{x})\\)映射后的特征线性可分，所以我们可以使用hard-margin SVM去分类。

设discriminant function为 $ f(x)=\underline{\omega}^{T}\phi(\underline{x})+b $
SVM原则是max margin，即 $ \underset{\omega }{max}(\frac{1}{\left \| \underline{\omega} \right \|^{2}}) $
相当于 $\underset{\omega }{min}(\frac{1}{2}{\left \| \underline{\omega} \right \|^{2}})$

	
$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$
