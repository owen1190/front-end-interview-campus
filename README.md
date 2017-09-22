# 前端面试题目及答案（校招）

## 前言

现在正处于校招季，本responsity找了大部分校招面试时候都会问到相关题目，并整理了答案。

对于不足之处，欢迎大家可以issue

>本responsity只是为了大家面试前查缺补漏之用，请大家还是踏踏实实学习好前端面试，不要在面试前突击使用，毕竟下面答案有的很浅显，希望大家去阅读相关书籍或相关文档，深刻理解。

>题目来源[牛客前端工程师300道面试题整理](https://zhuanlan.zhihu.com/p/28911400)及论坛各位同学发的面经


## HTML

题目|答案|备注
:--:|:--:|:--:
常用meta标签 |[常用meta整理](https://segmentfault.com/a/1190000002407912)
DOCTYPE作用|[DOCTYPE作用及用法详解](http://www.cnblogs.com/flyingzqx/archive/2009/12/16/1625427.html)
老版本不支持html5标签怎么办|[html5shiv让IE6-IE8支持HTML5标签](http://caibaojian.com/html5shiv.html)
web语义化 | [如何理解 Web 语义化？](https://www.zhihu.com/question/20455165)、[语义化的HTML结构到底有什么好处？](http://www.css88.com/archives/1668)
meta中viewport|[移动前端开发之viewport的深入理解](https://www.cnblogs.com/2050/p/3877280.html)
block 和 inline-block区别|[block，inline和inline-block概念和区别](http://www.cnblogs.com/KeithWang/p/3139517.html)

## CSS

题目|答案|备注
:--:|:--:|:--:
清除浮动方法| [清除浮动解决方案](http://www.w3cplus.com/solution/clearfloat/clearfloat.html)|还可以添加一个`br`空元素
 两栏布局，左边固定，右面自适应|[左边固定，右边自适应布局(四种方法：负边距、flex)](https://segmentfault.com/a/1190000010415257)|还有grid方法
三栏布局，左右固定，中间自适应 |[CSS三栏布局——中间固定两边自适应宽度](http://www.w3cplus.com/blog/104.html)|别忘grid
垂直水平居中 |[CSS居中完整指南](https://www.w3cplus.com/css/centering-css-complete-guide.html)|别忘grid
隐藏元素方法比较|[CSS“隐藏”元素的几种方法的对比](http://www.imooc.com/article/4849)
外边距合并|[前端面试必备——外边距合并](http://blog.csdn.net/owen1190/article/details/75016205)
盒模型|[盒子模型 MDN](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
重排和重绘|[重排重绘，看这一篇就够了](https://juejin.im/entry/582f16fca22b9d006b7afd89)
css实现各种形状|[纯CSS画的基本图形（矩形、圆形、三角形、多边形、爱心、八卦等）](http://www.cnblogs.com/jscode/archive/2012/10/19/2730905.html)
z-index层叠上下文|[关于z-index 那些你不知道的事](https://webdesign.tutsplus.com/zh-hans/articles/what-you-may-not-know-about-the-z-index-property--webdesign-16892)
等高布局|[八种创建等高列布局](https://www.w3cplus.com/css/creaet-equal-height-columns)

## JavaScript

题目|答案|备注
:--:|:--:|:--:
 深拷贝和浅拷贝 |[javaScript中浅拷贝和深拷贝的实现](https://github.com/wengjq/Blog/issues/3)
 JS数组扁平化 |[Javascript多维数组扁平化](http://www.jstips.co/zh_cn/javascript/flattening-multidimensional-arrays-in-javascript/)
 new操作符作用及构造new函数 | [javascript中，new操作符的工作原理是什么?](https://www.zhihu.com/question/36440948)|参考何幻和鲁小夫的答案
`prototype` `__proto__` `constructor` | [知乎中苏墨橘、doris的答案](https://www.zhihu.com/question/34183746)|尤其doris答案中的图非常经典。
数组去重|[也谈JavaScript数组去重](https://www.toobug.net/article/array_unique_in_javascript.html)
实现bind|[深入学习JavaScript之一：bind函数的实现](https://github.com/shhdgit/blogs/issues/1)
事件监听函数，支持匿名函数|[javascript支持匿名函数的事件监听封装](http://www.111cn.net/wy/js-ajax/55335.htm)
setTimeout和setInterval为什么不在指定时间之后执行|《JavaScript高级程序设计》中第22章高级定时器
EventLoop机制|[理解事件循环一(浅析)](https://github.com/ccforward/cc/issues/47)
JavaScript中异步操作方法|回调函数、Promises、Generator、Async/await|[阮一峰 ES6入门](http://es6.ruanyifeng.com/#README)中后三种都有讲解
defer和async区别|[defer和async的区别](https://segmentfault.com/q/1010000000640869)|文中图片很容易让人理解
减速滚动到页面顶部|[常见效果实现之返回顶部(结合淡入、淡出、减速滚动)](http://www.cnblogs.com/rentj1/archive/2011/12/31/2308443.html)
javascript中this问题|[深入理解 js this 绑定](https://segmentfault.com/a/1190000011194676?utm_source=weekly&utm_medium=email&utm_campaign=email_weekly)
promise源码|[es6 promise源码实现](https://segmentfault.com/a/119000000610360
## HTTP

题目|答案|备注
:--:|:--:|:--:
浏览器缓存机制？ |[浅谈浏览器http的缓存机制](http://www.cnblogs.com/vajoy/p/5341664.html)、[浏览器缓存机制](https://www.cnblogs.com/skynet/archive/2012/11/28/2792503.html)
HTTP状态码？ |[HTTP状态码](http://www.cnblogs.com/starof/p/5035119.html)
GET与POST区别| [99%的人都理解错了HTTP中GET与POST的区别](https://zhuanlan.zhihu.com/p/22536382)
输入url到页面加载的过程 |[最经典的前端面试题之一，你能答出什么幺蛾子？](https://zhuanlan.zhihu.com/p/28946087)
跨域 | [浏览器同源政策及其规避方法](http://www.ruanyifeng.com/blog/2016/04/same-origin-policy.html)、[跨域资源共享 CORS 详解](http://www.ruanyifeng.com/blog/2016/04/cors.html)、[前端常见跨域解决方案（全）](https://mp.weixin.qq.com/s?__biz=MjM5NTEwMTAwNg==&mid=2650212085&idx=1&sn=07abf81aade39a7684c813cb9c31df7b&chksm=befe06d489898fc20124e9623f33db6b28f5c7a3659e6ffd9ffc99308ba8fb0fa33fb5b04e9f&mpshare=1&scene=1&srcid=0916D9blfb6UjdC4KyjI7Puw#rd)
cookie sessionStorage localStorage|[详说 Cookie, LocalStorage 与 SessionStorage](http://jerryzou.com/posts/cookie-and-web-storage/)
cookie seesion|[COOKIE和SESSION有什么区别？](https://www.zhihu.com/question/19786827)、[用户登录状态 验证权限的时代变迁](https://zhuanlan.zhihu.com/p/29101305?group_id=890897262773927936)
xss、csrf|[前端安全知多少](https://mp.weixin.qq.com/s/tgIWXcfzswcKcKcb-Dzt_g)
HTTP2新特性|[一文读懂 HTTP/2 特性](https://tech.upyun.com/article/227/%E4%B8%80%E6%96%87%E8%AF%BB%E6%87%82%20HTTP%2F2%20%E7%89%B9%E6%80%A7.html)
跨页面通信方法|[跨页面通信的各种姿势](https://mp.weixin.qq.com/s?__biz=MjM5MTA1MjAxMQ==&mid=2651226988&idx=1&sn=4a06315e384a16fdf9ce53b82d4a7347&chksm=bd495ae88a3ed3febae21ce2475117e1c4cc162bd7db2d339764f7a4d0ddcf731410bafc6cbd&mpshare=1&scene=1&srcid=0919GEhT9msLmCY2Qevc7nhc#rd)

## React/Redux

题目|答案|备注
:--:|:--:|:--:
React生命周期 | 《深入react技术栈》第一章中React生命周期
React setState源码 | 《深入react技术栈》第三章中解密setState机制
当view界面发生改变时，Redux的过程 |[看漫画，学 Redux](https://github.com/jasonslyvia/a-cartoon-intro-to-redux-cn)
在React中使用ajax，在哪个生命周期调用 |[【译】React如何抓取数据](https://zhuanlan.zhihu.com/p/28623518)
virtual dom源码|[如何实现一个 Virtual DOM 算法](https://github.com/livoras/blog/issues/13)
组件之间通信方式|[React 组件间通讯](http://taobaofed.org/blog/2016/11/17/react-components-communication/)
diff算法|《深入react技术栈》第三章中diff算法
Redux源码|[React小书](http://huziketang.com/books/react/lesson30)


>React中的好多问题可以通过阅读《深入React技术栈》这本书


## 算法

题目|答案|备注
:--:|:--:|:--:
《剑指offer》 |[牛客平台](https://www.nowcoder.com/ta/coding-interviews)/[JavaScript版剑指offer](http://blog.csdn.net/column/details/16574.html)
 javascript常用的排序算法 |[前端面试必备——基本排序算法](http://blog.csdn.net/owen1190/article/details/76215932)
JavaScript图遍历算法|[前端面试必备——图](http://blog.csdn.net/owen1190/article/details/77752078)
JS能力测评经典题|[JS能力测评经典题](https://www.nowcoder.com/ta/js-assessment)
前端技能大挑战|[前端技能大挑战](https://www.nowcoder.com/ta/front-end)
codewars专门针对js的基础练习|[codewars](https://www.codewars.com)

## 移动web

题目|答案|备注
:--:|:--:|:--:
移动端适配方案|[移动端适配方案(上)](https://github.com/riskers/blog/issues/17)、[移动端适配方案(下)](https://github.com/riskers/blog/issues/18)

## NodeJS

题目|答案|备注
:--:|:--:|:--:
饿了么nodejs面试|[如何通过饿了么 Node.js 面试](https://github.com/ElemeFE/node-interview/tree/master/sections/zh-cn)

## 其他

题目|答案|备注
:--:|:--:|:--:
性能优化|[Web前端性能优化](https://www.w3ctech.com/topic/1767)、[Web 的现状：网页性能提升指南](https://segmentfault.com/a/1190000011213814?utm_source=weekly&utm_medium=email&utm_campaign=email_weekly)
浏览器渲染原理|[浏览器的渲染原理简介](https://coolshell.cn/articles/9666.html)、[How browsers work【中文版】](https://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/)