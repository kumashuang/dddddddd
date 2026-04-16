# JavaScript 基础知识

## 1. 变量和常量

- 使用 `var`、`let`、`const` 声明变量
  ```js
  var x = 5;
  let y = 10;
  const PI = 3.14;
  ```

## 2. 数据类型

- 基本类型：Number、String、Boolean、Undefined、Null、Symbol、BigInt
- 引用类型：Object、Array、Function 等

## 3. 运算符

- 算术运算符：+ - * / % **
- 赋值运算符：= += -= *= /=
- 比较运算符：== === != !== > < >= <=
- 逻辑运算符：&& || !

## 4. 条件语句

```js
if (x > 10) {
  // ...
} else if (x > 5) {
  // ...
} else {
  // ...
}
switch (color) {
  case 'red':
    // ...
    break;
  default:
    // ...
}
```

## 5. 循环语句

```js
for (let i = 0; i < 5; i++) {
  // ...
}

while (condition) {
  // ...
}

do {
  // ...
} while (condition);
```

## 6. 数组

```js
let arr = [1, 2, 3];
arr.push(4);      // 添加元素
arr.pop();        // 删除元素
arr.length;       // 获取长度
arr.forEach(...)  // 遍历
```

## 7. 对象

```js
let person = {
  name: 'Tom',
  age: 20
};
console.log(person.name); // 访问属性
```

## 8. 函数

- 声明式
  ```js
  function add(a, b) {
    return a + b;
  }
  ```
- 表达式（匿名函数）
  ```js
  const add = function(a, b) {
    return a + b;
  }
  ```
- 箭头函数
  ```js
  const add = (a, b) => a + b;
  ```

## 9. 作用域与闭包

- 作用域分为全局和局部
- 闭包：函数内部返回函数，可以访问外部变量

## 10. 常用内置对象

- `Math`、`Date`、`JSON` 等
  ```js
  Math.random();
  new Date();
  JSON.stringify(obj);
  ```

## 11. DOM 操作（基础）

```js
document.getElementById('id');
document.querySelector('.className');
element.innerHTML = '内容';
element.addEventListener('click', handler);
```

## 12. 异步编程基础

- setTimeout/setInterval（定时器）
- Promise
- async/await

```js
setTimeout(() => {
  console.log('Hello');
}, 1000);

function getData() {
  return new Promise((resolve, reject) => {
    // 异步操作
  });
}

async function asyncFunc() {
  let data = await getData();
}
```

---

**了解更多进阶内容可以继续学习 ES6、面向对象、模块化、原型链、事件循环等。**
