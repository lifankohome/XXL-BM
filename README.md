## 信息论与编码课程设计 - JavaScript

凡是可用 JS 实现的事物最终都将用 JS 实现。

功能：

1. 统计信源熵（任意文本中各字符的数量，计算字符概率，并计算信源熵）
2. 香农编码（任意输入消息概率，利用香农编码方法进行编码，并计算信源熵和编码效率）

----------

香农编码

> 香农编码步骤：

>（1） 将信源消息符号按其出现的概率大小依次排列：p（x1）≥p（x2）≥„≥p（xn）

>（2） 确定满足下列不等式整数码长Ki：-log2p(xi)≤Ki＜-log2p(xi)+1

>（3） 为了编成唯一可译码，计算第i个消息的累加概率

>（4） 将累加概率Pi变成二进制数。 

>（5） 取Pi二进制数的小数点后Ki位即为该消息符号的二进制码字。

演示地址：http://hpu.lifanko.cn/xxl
