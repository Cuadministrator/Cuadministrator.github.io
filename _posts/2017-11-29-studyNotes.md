---
layout: post
title: 前端学习总结
date: 2017-11-28
categories: blog
tags: [study,note]
description: 总结
---
# 介绍

1. JavaScript: 
- 简称：js 
- 类型：编程语言
- 原生js，前端世界的 hello world。

2. jquery：
- 简称：jq 
- 类型：类库
- 对js进行封装后简化版js 应用很方便 可以学习也可以不学习，简单了解一下也可以。

3. ECMAScript 6： 
- 简称：es6
- 类型：标准化
- 对于js进行标准化规定。

4. Cascading Style Sheets：
- 简称：css 
- 类型：样式表
- 如何显示html

5. Asynchronous JavaScript and XML：
- 简称：ajax 
- 类型：创建交互式网页应用的网页开发技术
- 在不重新加载整个页面的情况下与服务器交换数据并更新部分网页。(异步 JavaScript 和 XML)

6. vue.js react.js： 
- 简称：vue/react
- 类型：框架
- 当前热门框架，核心库是为了对视图层渲染，为复杂单页应用提供驱动。

7. webpack：
- 简称： webpack
- 类型：javascript应用程序的模块打包器
- webpack 是一个JavaScript 应用程序的模块打包器。处理应用程序时，它会递归地构建一个依赖关系图，其中包含应用程序需要的每个模块，然后将所有这些模块打包成一个或多个 bundle。

**简单来说，目前需要学习： 原生js(推荐原生js)/类库jq + es6标准化 + css样式表 + ajax数据交互 + vue/react 框架 + webpack 打包工具**

# 内容

#### 一、javascript高级编程 

1. 前端最重要的东西 多读几遍都行，工作后jquery都可以不用会，原生js必须很熟悉。

2. Ajax 相关知识可以粗略的过一遍后，在es6的promise和async看完后再来细看。

(ps:意思就是，里面的东西即使..有些看起来不重要，也很重要，不需要划重点，都很重要，包括什么标记回收机制这种东西都是很重要的请认真的对待。)

##### 学习完成后尝试一些我做过的小任务： 

1. 浏览器相关  获取可视区域宽高   文档宽高  屏幕宽高  兼容处理

2. 滚动条高度top  height    返回顶部  动画

3. 键盘相关 按键的 key   鼠标事件   做一个鼠标拖拽  鼠标滑动轨迹

4. 尝试 贪吃蛇(因为进度问题 我没有做过关于js写的贪吃蛇)

5. 静态新浪首页

- ps：需求对所有实现的功能进行 ie chrome Firefox 兼容处理

#### 二、css

1. css3在动画方面的支持不错可以去看看(实现伪弹幕) css的学习方法是多写，没有其他很好的学习途径。

#### 三、es6(*)

<a href="http://es6.ruanyifeng.com/#README">es6中文文档</a> 

##### 重点：

1. let和const命令。

2. 字符串、正则、数值、函数、数组、对象的扩展，不懂的可以放放，后面有解释，再不懂得就去百度。

3. set 和 map数据结构 区分两种数据结构的差异 以及实际应用的不同。

4. proxy 代理进行拦截的机制。

5. reflect和proxy相似 看看能不能懂，能懂就慢慢看，不懂可以暂时跳过。

6. promise(*) 重点学习，异步操作的实现重点，请认真看，可以对ajax进行封装实现异步请求数据。

7. Iterator 和 for...of循环 这个也比较复杂 关于遍历器方面的知识。

8. Generator 实现异步 状态机 数据结构 控制流 以及协程的一些知识，同样可以对ajax进行封装实现异步请求数据。

9. async(*) 实现异步 和 promise 结合 完善ajax异步请求数据 很重要，实际用的很多，需要重点学习。

10. class(*) 类和类的继承js里很重要的东西，es6中也很重要请认真对待

11. decorator 类的修饰，可以看看，后面再来学习的时候搞懂，终究是需要搞懂的东西。

12. module 引用 加强代码耦合程度 实现模板化。

13. arraybuffer 多用多熟悉就好，可以后面在学习。

14. 编程风格，读懂规格都需要融入平时coding中的，以便以后的适应。

#### 四、Ajax

1. 提交form表单，请求接口，获取数据 需要学习 (在JavaScript高级编程中有相关章节，涉及异步请求等知识，所以放在了最后，请提前把 es6 中 promise以及async结合起来看。)

#### 五、框架

- <a href="https://cn.vuejs.org/v2/guide/installation.html">vue.js中文文档</a>

- <a href="https://doc.react-china.org/docs/installation.html">react.js中文文档</a>

- <a href="http://www.ruanyifeng.com/blog/2015/03/react.html">react.js阮一峰教程</a> 

- vue.js react.js 选择一个框架进行学习，框架的内容我会在后期学习后进行补充。

#### 六、webpack

- <a href="https://doc.webpack-china.org/concepts/">webpack中文文档</a>

- 还没有学习完...这个真的没法写，webpack内容同样在后期学习后进行补充。

# 总结

  - 目前 我勉强吧js基础学习了一遍，css方面在工作学习中应用比较多也熟悉了一些，es6的学习因为工作有些拖延，原生ajax数据请求学习完不是很熟悉，vue.js 和 react.js 最后应该会选择vue，不过还会对react进行学习，后续会补充关于框架学习中的一些我认为比较重要的东西。

#### 微信小程序相关：

  - 在学习过程中觉得小程序可以作为前端入门，虽然坑很多，不过对于api的查询，css js es6的锻炼比较好，入门比较轻松，理解起来也比较容易，而且属于目前开发需求的东西，可以作为自己简历的竞争优势。
  - 坑和一些遇到的问题会在写一篇文章来简述。

  - 暂时目标和学习记录如上，很多东西需要在实际应用中才能更进一步，希望自己继续努力下去。