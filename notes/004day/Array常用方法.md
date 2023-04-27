# some()

判断数组内是否有元素符合条件，如果有则返回 true，否则返回 false。

**语法**

```js
array.some(function(value,index,array),thisValue)
```

# every()

判断数组内是否所有元素都符合条件，如果都符合则返回 true ，否则返回 false。

**语法**

```js
array.every(function(value,index,array),thisValue)
```

# fill()

将数组内根据指定位置填充指定的值。返回填充后的数组

该方法会改变原始数组。

**语法**

```
array.fill(value, start, end)
```

# filter()

使用指定函数过滤数组中的元素，返回过滤后的数组。

**语法**

```js
array.filter(function(value,index,array),thisValue)
```

# find()

返回符合条件的数组元素。

**语法**

```js
array.find(function(value,index,array),thisValue)
```

# findIndex()

返回符合条件的数组元素的索引。

**语法**

```
array.findeIndex(function(value,index,array),thisValue)
```

# forEach()

为数组中每个元素都执行一遍指定函数。没有返回值。

**语法**

```js
array.forEach(function(value,index,array),thisValue)
```

# indexOf()

返回第一个匹配指定数组元素的索引。

**语法**

```js
array.indexOf(item)
```

# join()

返回使用指定连接符拼接所有数组元素的字符串。

**语法**

```js
array.join(str)
```

# map()

为所有数组元素执行指定函数，函数的返回值组成新的数组并返回。

**语法**

```js
array.map(function(value,index,array),thisValue)
```

# push()

在数组末尾添加新的数组元素，返回添加后的数组长度。

该方法会改变原始数组。

**语法**

```js
array.push(item1,item2,...)
```

# pop()

移除数组最末尾的元素，并返回该移除的元素。

该方法会改变原始数组。

**语法**

```
array.pop()
```

# unshift()

在数组开头添加元素，并返回添加后的数组长度。

该方法会改变原始数组。

**语法**

```
array.unshift(item1,item2,...)
```

# shift()

移除数组开头第一个元素并返回。

该方法会改变原始数组。

**语法**

```
array.shift()
```

# reduce()

将数组元素从左往右缩减为一个值并返回。

**语法**

```
array.reduce(function(total,value,index,array),initValue)
```



# reverse()

将数组元素的顺序翻转并返回数组。

该方法会改变原始数组。

**语法**

```
array.reverse()
```



# sort()

将数组元素排序。返回排序后的数组。

**语法**

```
array.sort([function(a,b)])
```



# splice()

数组中删除添加元素。

该方法会改变原始数组。

**语法**

```
array.splice(target,howmany,item1,item2,...)
```



# slice()

从数组中提取指定范围的元素组成新数组并返回。

**语法**

```
array,slice(start,end)
```

