# 基于C实现简单的朴素贝叶斯方法

## 项目描述
该项目运用《概率论与数理统计》中的先验概率、后验概率、条件概率等知识实现简单的朴素贝叶斯方法，通过收集历史数据 + 定义若干相关因素生成模型，预测某学生在每周的某天某时间段逃课的概率大小。

## 问题描述

每个人在决定是否做一件事时往往会参考过往的经验，利用C语言实现朴素贝叶斯方法，
通过所有的“经验”生成相应的训练数据，将训练数据通过朴素贝叶斯算法，
最终得出相应事件的是与否的相应概率大小，最终生成概率作为参考。

## 程序实现的功能

在某个样例条件下，通过朴素贝叶斯算法计算出基于训练数据，
在该样例条件下做出相应决策的概率大小分别是多少。
显示相应的决策概率分布，为使用者做出决策提供参考。

## 程序概述

#### 程序输入的形式
程序的输入数据均在data.h文件定义并填入

#### 程序的输出形式
弹出黑框文字展示相应决策的概率大小

## 文件内容简述
- data.h： 定义并存放训练样本集，以及设定新实例的输入

- 朴素贝叶斯算法.cpp： 算法实现的函数封装

*为方便理解，将主函数文件名设置为中文*
