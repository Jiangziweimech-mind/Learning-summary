#### round()

是python自带的一个函数，用于数字的四舍五入

#### **kwargs

发送一个键值对的可变数量的参数列表给函数（打包参数）

```python
def test_kwargs(**kwargs):
    print(kwargs)
    print(type(kwargs))
    for key, value in kwargs.items():
        print("{} == {}".format(key, value))
 
test_kwargs(name='zxf',age=23,address='zhejiang')
# {'name': 'zxf', 'age': 23, 'address': 'zhejiang'}
# <class 'dict'>
# name == zxf
# age == 23
# address == zhejiang

```

#### 字典get

```python
dict.get(key, default=None)
#key-字典中要查找的键
#查找不到则返回default
```

#### def __init__(self, **kwargs)

https://blog.csdn.net/Jiana_Feng/article/details/107861130

super().__init__() 来继承另一个类的参数

** 字典  收集关键字参数

#### **items**   

字典items()方法和iteritems()方法，是[python](https://so.csdn.net/so/search?q=python&spm=1001.2101.3001.7020)字典的内建函数，分别会返回Python列表和迭代器

https://blog.csdn.net/zouxiaolv/article/details/94593651

####  **@abstractmethod 抽象类**

抽象类 该类不能直接实例化 需要被继承

from abc import ABC, abstractmethod

https://www.cnblogs.com/baxianhua/p/10876181.html

https://blog.csdn.net/jiang_huixin/article/details/109900067

#### **@classmethod 类方法**

![image-20220221152220959](E:/Mech-Mind/机器人适配/代码学习笔记/代码学习笔记.assets/image-20220221152220959.png)

#### **@staticmethod 静态方法**

可以在不实例化类的情况下直接访问该方法

#### **threading**

```python
def main():
	for i in xrange(0, 10):
		th = threading.Thread(target=test, args=(i, ))
		th.start()
```

```python
threading

threading.lock()

threading.lock.acquire()   #获取lock并将lock转成locked

threading.lock.release()   #释放锁
```

```python
threading.Condition()
```

![image-20220222155339094](E:/Mech-Mind/机器人适配/代码学习笔记/代码学习笔记.assets/image-20220222155339094.png)

#### Process( )

**multiprocessing.Process()**     进程

**multiprocessing.Lock()**    进程锁

**multiprocessing.Queue()**  队列  创建共享的进程队列，Queue是多进程安全的队列，可以使用Queue实现多进程之间的数据传递

#### **struct**

pack unpack 打包 解包

将字节解释为压缩二进制数据

struct.pack(format, v1, v2, ...)

#### **hasattr()** 

函数用于判断对象是否包含对应的属性。

#### assert expression

```
if not expression:
    raise AssertionError
```

#### 单下划线**_**

按照习惯，有时候单个独立下划线是用作一个名字，来表示某个变量是临时的或无关紧要的

#### **all()**

all() 函数用于判断给定的可迭代参数 iterable 中的所有元素是否都为 TRUE，如果是返回 True，否则返回 False

#### **math.isclose()**

```python
isclose(a, b, rel_tol = 1e-09, abs_tol 0.0)
#rel_tol:被视为“close”的最大差，相对于输入值的大小
#abs_tol:“close”的最大差异，与输入值的大小无关
```

math.isclose()方法用于确定两个浮点数的值是否接近

#### pop()

pop("key",default)    	移除字典要删除的键值 返回default

