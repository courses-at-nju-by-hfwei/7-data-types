# 括号序列(brackets.c)

## 题目描述

**完成本题前建议先完成[栈(stack.c)](http://172.26.41.176:5000/contest/9/problem/23)**

定义一个合法括号序列（balanced bracket sequence）为仅由`()[]{}`构成的字符串且:

- 空串是一个合法括号序列。
- 如果串`s`是合法括号序列，那么`(s)`，`[s]`和`{s}`也都是合法括号序列。（`(s)`表示在`s`两边加上`()`得到的字符串，如`s = [()]`，那么`(s) = ([()])`）
- 如果`s`, `t`都是合法括号序列，那么`st`也是合法括号序列。(`st`表示`s`和`t`相连得到的字符串)

给出$T$个字符串，判断每个字符串是否是一个合法的括号序列。

## 输入格式

第一行一个整数$T$（$T \leqslant 30$），表示一共有$T$组数据

之后$T$行每行输入一个字符串$s$（$|s| \leqslant 10^5$），为给定的括号序列

## 输出格式

一共$T$行，每行一个`True`或者`False`，表示对应的字符串$s$是/不是合法的括号序列

## 脚注

## 样例

### 样例输入

4
[(])
([)]
([{}])([])
())(()

### 样例输出

False
False
True
False
