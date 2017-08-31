# Python基础总结


### 数据类型
------------

#### 整数

整数常用的十进制，包括负整数，例如：1，-100,0等等。
使用十六进制时，用0x前缀和0-9，a-f表示，例如：0xffe2，0xcccc，等等。

### 浮点数

浮点数就是小数。

#### 字符串

字符串是以单引号或者双引号括起来的任意文本。

```
print('hello world!!!')
>>>hello world

print("hello world!!!")
>>>hello world



```



#### 布尔值

### 字典（dict）

> dict使用键值对存储。

```
obj = {'userName':'lili','age':12}
obj['userName']// 取字典里面的值
>>>'lili'
obj['height'] = 1.70 //给字典里面赋值
obj.get('height')
>>>1.70

```