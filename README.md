# One-question-a-day
留给自己看的题

题目大部分来自 [木易杨的每天一道题面试题](https://github.com/Advanced-Frontend/Daily-Interview-Question) 和
[前端 100 问](https://github.com/yygmind/blog/issues/43)

## js基础
1. [['1', '2', '3'].map(parseInt) what & why ?](https://github.com/lovelmh13/One-question-a-day/issues/3)
2. [有以下 3 个判断数组的方法，请分别介绍它们之间的区别和优劣Object.prototype.toString.call() 、 instanceof 以及 Array.isArray()](https://github.com/lovelmh13/One-question-a-day/issues/4)
3. [关于 const 和 let 声明的变量不在 window 上](https://github.com/lovelmh13/One-question-a-day/issues/5)
4. [打印var b = 10; (function b() { b = 20; console.log(b) })()结果](https://github.com/lovelmh13/One-question-a-day/issues/6)
5. [setTimeout、Promise、Async/Await 的区别](https://github.com/lovelmh13/One-question-a-day/issues/12)
6. [ES5/ES6 的继承除了写法以外还有什么区别？](https://github.com/lovelmh13/One-question-a-day/issues/13)
7. [浏览器和Node 事件循环的区别](https://github.com/lovelmh13/One-question-a-day/issues/16)
8. [下面代码中 a 在什么情况下会打印 1？（京东）](https://github.com/lovelmh13/One-question-a-day/issues/18)
9. [下面代码输出什么](https://github.com/lovelmh13/One-question-a-day/issues/20)
```js
var a = 10;
(function () {
	console.log(a)
	a = 5;
	console.log(window.a)
	var a = 20;
	console.log(a)
})()
```
10. [实现一个 sleep 函数，比如 sleep(1000) 意味着等待1000毫秒，可从 Promise、Generator、Async/Await 等角度实现](https://github.com/lovelmh13/One-question-a-day/issues/21)

## 编程
1. [手写防抖](https://github.com/lovelmh13/One-question-a-day/issues/1)
2. [手写节流](https://github.com/lovelmh13/One-question-a-day/issues/2)
3. [将数组扁平化并去除其中重复数据，最终得到一个升序且不重复的数组](https://github.com/lovelmh13/One-question-a-day/issues/7)
4. [根据以下要求，写一个数组去重函数(蘑菇街) ](https://github.com/lovelmh13/One-question-a-day/issues/8)
5. [如果实现一个 new](https://github.com/lovelmh13/One-question-a-day/issues/9)
6. [请把俩个数组 [A1, A2, B1, B2, C1, C2, D1, D2] 和 [A, B, C, D]，合并为 [A1, A2, A, B1, B2, B, C1, C2, C, D1, D2, D]](https://github.com/lovelmh13/One-question-a-day/issues/10)
7. [简单改造下面的代码，使之分别打印 10 和 20](https://github.com/lovelmh13/One-question-a-day/issues/11)

## CSS
1. [介绍下重绘和回流（Repaint & Reflow），以及如何进行优化](https://github.com/lovelmh13/One-question-a-day/issues/15)
2. [介绍下BFC及其应用](https://github.com/lovelmh13/One-question-a-day/issues/19)

## HTTP
1. [谈谈你对 TCP 三次握手和四次挥手的理解](https://github.com/lovelmh13/One-question-a-day/issues/14)
2. [cookie 和 token 都存放在 header 中，为什么不会劫持 token？](https://github.com/lovelmh13/One-question-a-day/issues/17)
