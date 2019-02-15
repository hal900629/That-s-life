## 原型链




原型链的示意结构图如下:

![](20.png)

### 原型链实现继承
function A(){
```

上述代码实现的示意图如下:

![](21.png)

### 只继承于原型

function A(){}
```

### 原型链的问题

function object( o ){
```

根据原型式继承所总结的 object() 函数实现继承，如下代码示例:

```javascript
var person = {
```

这种原型式继承要求必须具有一个对象可以作为另一个对象的基础。
var person = {
```

> **值得注意的是:** 原型式继承具有与原型链同样的问题。



```javascript
function SuperType(){
```

## 组合方式继承


- 使用原型链或原型式继承实现对原型的属性和方法的继承。

```javascript
function SuperType( name ){
```