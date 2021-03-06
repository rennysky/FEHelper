

自从Vue2.0发布后，Vue就成了前端领域的热门话题，github也突破了三万的star，那么对于新手来说，如何高效快速的学习Vue2.0呢。

## Vue基础
对于没有接触过es6和webpack的童鞋来说，不建议直接用官方的脚手架vue-cli构件项目。

先按文档顺序最少学习完组件那一章。直接在html文件中引入vue.js开始学习,了解vue的基础指令，和整个vue实例的基础架构。

vue的生命周期很重要，了解这点以后可以免去很多问题。

学完这些可以做一些练手的小项目，比如万年不变的todolist。。。

现在可以开始学习使用vue-cli构件项目了，学习组件化之前，推荐先看一下es6关于模块的介绍。阮一峰《ECMAScript6》 Module光会这些还是不够的，还得会一些npm基础，知道如何用git-bush来安装模块依赖，会一些常用的命令。这方面的知识可以参阅npm入门文档
看完这些就可以试着将之前的写的demo用搭建的vue-cli来实现。附上我写的一个入门小demovue-demo-search
多看看组件那里，看看如何在vue-cli中怎么实现组件化。

到这里vue基础篇就结束了。你还可以有条件的参阅剩下的官方文档里面的进阶篇，如果时间有限，就直接进入vue-router

## Vue-router
和之前一样，推荐直接用html+js过一遍文档
对路由导航钩子得好好看一看。

看完文档就可以上手vue-cli，一般新手在这几天都会死活跑不出来。偷笑最直接的方法就是去github上搜一些关于vue-router2.0的demo，看如何构件路由，如何构件项目目录。

我这里有一个传送门如果能跑出来，就可以做一些小项目了，比如写一个知乎日报啊偷笑，这些demo在github上很多。

可以结合一些组件库写demo，这样可以更加了解组件化。比如饿了么团队的Element、mint-ui

## Vuex

什么是vuex？

Vuex 是一个专门为 Vue.js 应用设计的 状态管理模型 + 库。它为应用内的所有组件提供集中式存储服务，其中的规则确保状态只能按预期方式变更。说白了就是控制应用的一些全局状态。状态改变了，对应的视图也会改变。

在学习Vuex时，会有一些ES6特性，当遇到这些时，最好不要一带而过，去好好看一看这些es6特性。

比如在学习Action时可以看看ES6新增的Promise和参数解构。

实践的方法一样是先看别人别人写的代码，比如官方的购物车实例的应用结构把之前写的demo优化一下，有些地方可以用用vuex

vuex主要是用来对不同组件间进行通信，它构建了一个Vue实例的全局数据与方法，这些数据与方法可以在该Vue实例的所有组件中get与set

## 入门到放弃整理

### 一、vue基础

[Vue2.0最全文档 ](https://router.vuejs.org/zh/ "Vue2.0最全文档 ")

[探索之路——vue-router入门教程和总结](https://segmentfault.com/a/1190000009651628 "探索之路——vue-router入门教程和总结")

[Vue.js 2.0 快速上手](https://zhuanlan.zhihu.com/p/23078117 "Vue.js 2.0 快速上手")

[Vuejs2.0 文档攻略](http://larabase.com/collection/2/post/126 "Vuejs2.0 文档攻略")

[“Vue2.0”跟俺一起全面入坑 01](vue/1.md "“Vue2.0”跟俺一起全面入坑 01")

[“Vue2.0”跟俺一起全面入坑 02](vue/2.md " “Vue2.0”跟俺一起全面入坑 02")

[“Vue2.0”跟俺一起全面入坑 03](vue/3.md " “Vue2.0”跟俺一起全面入坑 03")

 
### 二、vue提高

[vuejs心法和技法](vue/summaryvue10-20kills.md " vuejs心法和技法")

[Vue2.0 探索之路——生命周期和钩子函数的一些理解](vue/vuelifecycle.md" "Vue2.0 探索之路——生命周期和钩子函数的一些理解")

[用webpack（2.x语法）手动搭建Vue项目](vue/careateVUEforwebpack.md "用webpack（2.x语法）手动搭建Vue项目")
 
---

