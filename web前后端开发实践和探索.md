web前后端开发实践和探索：融合or分离
----------------------------------

## Agenda

* web开发的痛点
* 应对方法
* YOHO！Web前后端演进实践
* 分离OR融合？

## web开发的痛点

1. 需求导致数据定义总是在变
2. 交付的前端代码和上线的代码总是不一样
3. 页面里的业务逻辑
4. 浏览器的兼容
5. 前后端接口粒度不明确，前后端重复的工作

## 应对方法

1. 规范前后端的接口规范化
2. 前后端职责分离
3. 使用模板技术
4. 前端组件化
5. 接口网关，为前端定制

## YOHO！Web前后端演进实践

传统开发方式
	
* 前端页面制作->交付静态页面->前后端集成

模板化开发方式

* 组件式的模板->组件样式编写->页面行为编写->前端完成开发提交CSS，js，静态文件到CDN->模板文件与后端集成

大前端开发方式

* 前后端确定接口定义->建立服务端运行能力->编写页面流->编写组件->组件集成

## Demo

yo是什么？

[https://github.com/h1bomb/yo](https://github.com/h1bomb/yo)

[https://github.com/h1bomb/yo-todos](https://github.com/h1bomb/yo-todos)

[https://github.com/h1bomb/slush-yo](https://github.com/h1bomb/slush-yo)


## 分离OR融合？

1. 分离什么？

* 前端能力封装

> 标准化的组件

> 通用开发模式（MVC，MVVM，FLUX）

> 开箱即用的流程化工具（桩服务生成）


* 后端服务封装

> 标准的数据源(基于资源，RESTful)

> 标准的增删改从的行为封装（如，JSON API,YQL, GraphQL）
 
> 流程化的客户端工具（服务调试，验证，服务文档生成）如：swagger

* 对能力封装的分离（专业的更专业）

2. 融合什么？

* 对前后端标准的共识
* 业务开发的融合（业务理解更透彻）
* 工程化的融合（开发过程，开发工具，系统规范）

# Q&A

# thanks!

 

