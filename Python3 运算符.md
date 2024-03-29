### 什么是运算符？

例如 4+5=9 这个算术表达式，“4” 和“5” 称为“操作数”、"+" 称为运算符。

Python语言支持以下类型的运算符：
* [算术运算符](#算术运算符)
* [赋值运算符](#赋值运算符)
* 比较（关系）运算符
* 逻辑运算符
* 位运算符
* 成员运算符
* 身份运算符
* 运算符优先级

### 算术运算符

Python中的算术运算符除了常见的加、减、乘、除以外，还包括取余、幂、取整等运算。具体见下表：


 | 运算符 | 描述                                        | 实例                |
 | ---------- | ----------------------------------------------- | ----------------------- |
 | +          | 加 - 两个对象相加                               | 10+3=13                 |
 | -          | 减 - 得到负数或是一个数减去另一个数             | 10-3=7                  |
 | *          | 乘 - 两个数相乘或是返回一个被重复若干次的字符串 | 10*3=30                 |
 | /          | 除 - x 除以 y                                   | 10/3=3.3333333333333335 |
 | %          | 取模 - 返回除法的余数                           | 10%3=1                  |
 | **         | 幂 - 返回x的y次幂                               | 10**3=1000              |
 | //         | 取整除 - 向下取接近除数的整数                   | 10//3=3                 |


### 算术运算范例
[点击此处](https://kada.163.com/ide/python/3647339.htm)在线运行程序。

```Python
# 初始化变量值
a = 10
b = 3
c = 0
# 对变量进行算术运算，再将结果按格式显示
c = a + b
print ("10 + 3 的和为：", c)
c = a - b
print ("10 - 3 的差为：", c)
c = a * b
print ("10 × 3 的积为：", c)
c = a / b
print ("10 ÷ 3 的商为：", c)
c = a % b
print ("10 ÷ 3 的余数为：", c)
c = a**b 
print ("10 的 3 次幂为：", c)
c = a//b 
print ("10 ÷ 3 商的整数部分为：", c)
```

以上程序输出结果如下所示：

```
10 + 3 的和为： 13
10 - 3 的差为： 7
10 × 3 的积为： 30
10 ÷ 3 的商为： 3.3333333333333335
10 ÷ 3 的余数为： 1
10 的 3 次幂为： 1000
10 ÷ 3 商的整数部分为： 3
```

###  赋值运算符

除了常见的 “=” 赋值以外，Python中还有以下赋值运算符：



| **运算符**   | **描述**   | **实例**   |
|:----:|:----:|:----:|
| = | 简单的赋值 | c = a + b 将 a + b 的运算结果赋值为 c |
| += | 加法赋值 | c += a 等效于 c = c + a |
| -= | 减法赋值 | c -= a 等效于 c = c - a |
| *= | 乘法赋值 | c *= a 等效于 c = c * a |
| /= | 除法赋值 | c /= a 等效于 c = c / a |
| %= | 取模赋值 | c %= a 等效于 c = c % a |
| **= | 幂赋值 | c **= a 等效于 c = c ** a |
| //= | 取整除赋值 | c //= a 等效于 c = c // a |


###  赋值运算范例：

```python
# 初始化变量值
a = 10
b = 3
c = 0
# 对变量进行赋值运算，再将结果按格式显示
c = a + b
print ("10 + 3 的和为：", c)
c += a 
print ("c=13,a=10，c与a的加法赋值为：", c)
c -= a 
print ("c=23,a=10，c与a的的减法赋值为：", c)
c *= a 
print ("c=13,a=10，c与a的乘法赋值为：", c)
c /= a
print ("c=130,a=10，c与a的除法赋值为：", c)
c %= a 
print ("c=13.0,a=10，c与a的取模赋值为：", c)
c **= a 
print ("c=3.0,a=10，c与a的幂赋值为：", c)
c //= a
print ("c=59049.0,a=10，c与a的取整除赋值为：", c)
```

以上程序输出结果如下所示：
```
10 + 3 的和为： 13
10 - 3 的差为： 7
10 × 3 的积为： 30
10 ÷ 3 的商为： 3.3333333333333335
10 ÷ 3 的余数为： 1
10 的 3 次幂为： 1000
10 ÷ 3 商的整数部分为： 3
```
