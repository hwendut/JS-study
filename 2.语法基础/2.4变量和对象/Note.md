# 变量和对象

原始类型：number、string、boolean、null、undefined

引用类型：object、function函数

## 在变量中存放对象

1. 通过变量，读取对象中的某个属性

```js
变量名.属性名
```

**当读取的属性不存在时，会得到undefined**

**当读取属性的对象不存在（undefined或null）时，程序报错**

2. 通过变量，更改对象中的某个属性

**当赋值的属性不存在时，会添加属性**

3. 删除属性

```js
delete 对象.属性
```