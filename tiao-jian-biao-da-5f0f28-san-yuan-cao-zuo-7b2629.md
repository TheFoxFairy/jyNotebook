有时候只需执行if语句以及else子句就可以了，看下实例

```
>>> if 1 == 2:
...     print("1等于2")
... else:
...     print("1不等于2")
...
1不等于2
```

但是会发现如果这样写的话，感觉有点长，那现在可以使用三目运算符来简写这个条件语句

简写这个条件语句之前，先看下三目运算符的语法

```
语法: 输出a if 表达式b else 输出c

解释:如果表达式b条件为真，就执行输出1，否者执行输出c
```

实例:

```
>>> print("1") if 1 < 2 else print("2")
1


>>> print("1等于2") if 1==2 else print("1不等于2")
1不等于2
```



