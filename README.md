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
>>>print('hello world!!!')
'hello world'

>>>print("hello world!!!")
'hello world'
```



#### 布尔值



### 字典（dict）

> dict使用键值对存储。

```
>>>obj = {'userName':'lili','age':12}
>>>obj['userName']// 取字典里面的值
'lili'
>>>obj['height'] = 1.70 //给字典里面赋值
>>>obj.get('height')//get可以接收两个参数，假如字典里面没有第一个值，会有一个默认的值，就是第二个参数
1.70
>>>obj.pop('height')//删除字典里面的值pop里面需要接收参数，不然会报错
1.70
```

### list、tuple和set

list一种有序的集合，可以添加和删除其中的元素。

```
>>>list = ['lili','kangkang','huahua']
>>>list[0]
'liii'
>>>list[-1]
'huahua'
>>>list.append('pangpang')//往list后面添加元素
['lili','kangkang','huahua','pangpang']
>>>list.pop()//删除某元素
['lili','kangkang','huahua']
>>>list.pop(1)
['lili','huahua']
>>>list.insert(1,'kangkang')
['lili','kangkang','huahua']
```

tuple与list类似，tuple初始化后就不能修改，也没有append(),pop()等方法。

```
t = (3,)//当tuple只有一个元素时，要加逗号，因为与运算符号冲突。

```

set是一组Key的集合，不存储value。set里面没有重复的key。set里面可以可以接收一个tuple、list或者dic。

```
>>>s = set([1,2,3,3,3])//当传入的list或则tuple重复时，set会去掉重复的key;
set([1,2,3])
>>>s = set({'userName':'lili'})
set(['userName'])

>>>s = set([1,2,3])
>>>s.add(4)//往set里面添加元素
>>>s 
set([1,2,3,4])
>>>s.remove(4)//往set删除元素
>>>s
set([1,2,3])
```

### 函数



