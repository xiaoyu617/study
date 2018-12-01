# python 学习

- 求和 

```py
def sum(a,b):
    return a+b
```

- 计算 `a + b - c * d`

```py
def f(a, b, c, d):
    return a + b - c * d
```

- 求矩形面积和周长

```py
def rect(a,b):
    area = a * b
    around = (a + b) * 2
    return area, around
```


- 计算折扣金额

```py
def price(x):
    q = 0
    if x >= 50 and x <= 100:
        q = 0.1
    if x > 100:
        q = 0.2

    return q, (1 - q) * x
```


- 能同时被 3 和 5 整除

```py
def f(a):
    return a % 3 == 0 and a % 5 == 0
```

- 求 1 到 100 的和

```py
def sum():
    s = 0
    for i in range(101):
        s += i
    return s
```

- 交换两个数

```py
def swap(a,b):
    temp = a
    a = b
    b = temp
    return a,b

def swap1(a,b):
    return b,a

def swap2(a,b):
    [b, a] = [a, b]
    return a, b
```
