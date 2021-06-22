# OOP面向对象

看下面的代码来体会用oop来解决问题的思路。。。。。

```javascript
function Cat(name){
  this.name = name;
}

Cat.prototype.eat = function(something){
    console.log("eat " + something);
}
  
var xiaoA = new Cat('xiaoA');
var xiaoB = new Cat('xiaoB');

xiaoA.eat('apple');
xiaoA.eat('banana');
xiaoB.eat('banana');
```



