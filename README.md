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
9. 	<details>
	  <summary><a href="https://github.com/lovelmh13/One-question-a-day/issues/20">下面代码输出什么</a></summary>
	  <pre><code> 
	      	var a = 10;
		 (function () {
			console.log(a)
			a = 5;
			console.log(window.a)
			var a = 20;
			console.log(a)
		 })()
	  </code></pre>
	</details>


10. [实现一个 sleep 函数，比如 sleep(1000) 意味着等待1000毫秒，可从 Promise、Generator、Async/Await 等角度实现](https://github.com/lovelmh13/One-question-a-day/issues/21)
11. [call 和 apply 的区别是什么，哪个性能更好一些](https://github.com/lovelmh13/One-question-a-day/issues/23)
1. 	<details>
	  <summary><a href="https://github.com/lovelmh13/One-question-a-day/issues/24">输出以下代码的执行结果并解释为什么</a></summary>
	  <pre><code> 
	      	var a = {n: 1};
		var b = a;
		a.x = a = {n: 2};
		console.log(a.x)
		console.log(b.x)
	  </code></pre>
	</details>
13. [为什么要用setTimeout代替setInterval？](https://github.com/lovelmh13/One-question-a-day/issues/26)
14. [以下几段代码，分别打印什么（JS基础第4题的变种）](https://github.com/lovelmh13/One-question-a-day/issues/27)
15. [词法作用域与闭包](https://github.com/lovelmh13/One-question-a-day/issues/29)
16. [for in和Object.keys遍历对象的区别](https://github.com/lovelmh13/One-question-a-day/issues/32)
17. [隐式转换与[[ToPrimitive]](关联第8题)](https://github.com/lovelmh13/One-question-a-day/issues/40)
18. [补充第11题，call apply和bind的区别](https://github.com/lovelmh13/One-question-a-day/issues/41)
19. [JS 精度丢失问题](https://github.com/lovelmh13/One-question-a-day/issues/43)

## 编程
1. [手写防抖](https://github.com/lovelmh13/One-question-a-day/issues/1)
2. [手写节流](https://github.com/lovelmh13/One-question-a-day/issues/2)
3. [将数组扁平化并去除其中重复数据，最终得到一个升序且不重复的数组](https://github.com/lovelmh13/One-question-a-day/issues/7)
4. [根据以下要求，写一个数组去重函数(蘑菇街) ](https://github.com/lovelmh13/One-question-a-day/issues/8)
5. [如果实现一个 new](https://github.com/lovelmh13/One-question-a-day/issues/9)
6. [请把俩个数组 [A1, A2, B1, B2, C1, C2, D1, D2] 和 [A, B, C, D]，合并为 [A1, A2, A, B1, B2, B, C1, C2, C, D1, D2, D]](https://github.com/lovelmh13/One-question-a-day/issues/10)
7. [简单改造下面的代码，使之分别打印 10 和 20](https://github.com/lovelmh13/One-question-a-day/issues/11)
8. [老生常谈，手写promise](https://github.com/lovelmh13/One-question-a-day/issues/28)
9. [使用迭代的方式实现 flatten 函数](https://github.com/lovelmh13/One-question-a-day/issues/39)
10. [实现 (5).add(3).minus(2) 功能（Number里的this和this.value）](https://github.com/lovelmh13/One-question-a-day/issues/42)
11. [某公司 1 到 12 月份的销售额存在一个对象里面](https://github.com/lovelmh13/One-question-a-day/issues/44)

## Vue
1. [Vue 2.x 的响应式原理](https://github.com/lovelmh13/One-question-a-day/issues/33)
2. [Vue 2.x 响应数组的更新](https://github.com/lovelmh13/One-question-a-day/issues/34)
3. [Vue 2.x 编译模板（不是虚拟DOM，为了后面的收集依赖，暂时写的）](https://github.com/lovelmh13/One-question-a-day/issues/35)
4. [Vue 2.x 依赖收集](https://github.com/lovelmh13/One-question-a-day/issues/36)
5. [写 React / Vue 项目时为什么要在列表组件中写 key，其作用是什么？](https://github.com/lovelmh13/One-question-a-day/issues/37)
6. [聊聊 Vue 的双向数据绑定，Model 如何改变 View，View 又是如何改变 Model 的](https://github.com/lovelmh13/One-question-a-day/issues/38)

## 算法
1. [冒泡排序如何实现，时间复杂度是多少， 还可以如何改进？](https://github.com/lovelmh13/One-question-a-day/issues/30)
2. [选择排序](https://github.com/lovelmh13/One-question-a-day/issues/31)

## CSS
1. [介绍下重绘和回流（Repaint & Reflow），以及如何进行优化](https://github.com/lovelmh13/One-question-a-day/issues/15)
2. [介绍下BFC及其应用](https://github.com/lovelmh13/One-question-a-day/issues/19)
3. [怎么让一个 div 水平垂直居中](https://github.com/lovelmh13/One-question-a-day/issues/25)

## HTTP
1. [谈谈你对 TCP 三次握手和四次挥手的理解](https://github.com/lovelmh13/One-question-a-day/issues/14)
2. [cookie 和 token 都存放在 header 中，为什么不会劫持 token？](https://github.com/lovelmh13/One-question-a-day/issues/17)
3. [请求时浏览器缓存 from memory cache 和 from disk cache 的依据是什么，哪些数据什么时候存放在 Memory Cache 和 Disk Cache中？](https://github.com/lovelmh13/One-question-a-day/issues/22)
4. [cookies,sessionStorage,LocalStorage区别](https://github.com/lovelmh13/One-question-a-day/issues/45)
