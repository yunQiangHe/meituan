# Vue全家桶+SSR+Koa2全栈开发美团网

## 第1章 课程导学
这门课主讲以Vue SSR+Koa2全栈技术为目标，最终实现美团网项目。本章节旨在告诉大家我们会用到哪些技能、教学方法、课程内容分布、学习方法等。备注：我们会涉及Vue2.5、Nuxt、Koa2、element-ui、Mongodb等

1. 课程导学

## 第2章 Vue基础知识
整个SSR部分都是用的Vue框架，需要给初级用户讲解Vue的基础语法，不会让他们在学习实战的时候感到迷茫，这个章节会通过vue-cli搭建一个简单的demo，让大家快速的掌握Vue的基础应用，即使他没有学习过。

1. 概述&脚手架
2. 模板语法（1）
3. 模板语法（2）
4. 样式与遍历
5. 事件
6. 组件（1）
7. 组件（2）
8. 路由基础
9. Vuex基础用例（1）
10. Vuex基础用例（2）
11. Vuex高级用例（1）
12. Vuex高级用例（2）

## 第3章 Koa2基础知识
Node服务是全栈的核心，异步操作是为了提高并发数，koa2最大的特色就是灵活、轻巧，这都要归功于中间件机制。路由、数据库连接都是中间件的一种，通过这个章节的学习让大家掌握服务端开发基本技能。

1. Koa-generator
2. Koa异步async
3. Koa中间件
4. koa路由和cookie

## 第4章 Mongoose和Redis基础
mongoose是mongodb的对象模型管理工具，使用mongoose可以更简单的操作mongodb数据库，通过可视化工具的robo 3t的介绍，任何数据库操作都可以直观的感受到，非常利于数据库操作的学习。redis是服务端开发必备的工具之一，通过本章的学习可以快速掌握常用redis命令以及在node中的应用。...

1. mongoose（1）
2. mongoose（2）
3. Redis（1）
4. Redis（2）

## 第5章 Nuxt.js基础知识
Nuxt是Vue实现SSR最好的方案，我们整个项目都是基于Nuxt框架来实现的，我们需要了解如何通过脚手架快速初始化一个工程项目，熟悉每个目录的含义，知道如何配置各个页面的视图、模板、异步获取数据等。这个章节让学员快速掌握Nuxt本身的知识点，为实战做好准备。...

1. Nuxt.js基础（1）
2. Nuxt.js基础（2）
3. Nuxt.js基础（3）
4. Nuxt.js基础（4）

## 第6章 实战准备
工程搭建使用Nuxt脚手架快速搭建工程，这块是通用的，所有学员都可以直接应用到自己的项目。

1. 环境准备与项目安装
2. 辅助工具安装与配置改装

## 第7章 开发美团网首页
从需求分析到设计思路讲述再通过手把手的引导实现首页设计，在功能上包括城市定位服务，头部引导导航，搜索等。

1. 需求分析
2. 首页Header开发-城市定位服务设计
3. 首页Header开发-头部引导导航设计
4. 首页Header开发-搜索界面设计
5. Bug修复
6. 首页搜索
7. 首页菜单（1）
8. 首页菜单（2）
9. 章节小结
10. Footer补充

## 第8章 开发美团网首页-登录注册
从静态页面实现到真实的业务逻辑，一步一步带领大家实现注册、登录、退出，其中还用到了第三方RTMP服务，在技术上mongodb，passport,redis一应俱全

1. 注册（1）
2. 注册（2）
3. 注册（3）
4. 注册（4）
5. 注册（5）
6. 注册（6）
7. 注册（7）
8. 注册&登录（1）
9. 注册&登录（2）

## 第9章 开发美团网首页-Search搜索
只用7个模板dom节点实现复杂的搜索框，一改传统的dom结构设计，充分利用组件设计特性，让业务做到极致。除了交互，也使用了搜索、推荐等真实的线上数据服务，为大家提供真实的体验。

1. 城市服务
2. 菜单数据
3. Geo接口实现
4. Search接口实现（1）
5. Search接口实现（2）

## 第10章 切换城市页
切换城市页的难点是如何把复杂的数据内容利用数据结构设计、Vue语法并使用最简单的DOM结构完成开发。整个页面介绍了如何自定义常用的级联操作、远程搜索、中文转拼音等内容，精彩不可错过。

1. 切换城市（1）
2. 切换城市（2）
3. 切换城市（3）

## 第11章 美团网产品列表页
点击产品列表可以进入到产品详情页，详情页也有类似的推荐列表和地图服务，我们会在搜索页的时候考虑好接口的复用，重点内容在于数据结构的设计和接口的复用设计能力。

1. 页面设计（1）
2. 页面设计（2）
3. 地图组件开发
4. 入口文件编写（1）
5. 入口文件编写（2）
6. 页面调试

## 第12章 美团网产品详情页开发
产品详情页有购买入口，点进去进入到订单页，点击支付进入到支付页，购买完成进入到订单详情页。这块涉及较复杂的后端接口设计和数据库操作。学员可以进一步掌握真实的开发场景。

1. 需求分析
2. 静态模板
3. 产品详情页入口-静态文件
4. 产品详情页-接口

## 第13章 购物车开发
购物车难点在于数据库的设计、是于订单相融合的一个页面，在前端页面交互上的难点是element-ui对于表格的数据绑定

1. 购物车&订单-需求分析
2. 购物车&订单-页面创建
3. 购物车接口实现
4. 购物车调试

## 第14章 订单页开发
订单页是对整个产品的最后呈现页面，是课程完整性的一部分，难点在于数据库设计，前端页面无难点。

1. 订单页面
2. 订单接口
3. 订单调试

## 第15章 课程总结
对课程整体进行回顾与总结

1. 课程总结