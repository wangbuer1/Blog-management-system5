# 基于springboot的博客管理系统

## 1、项目介绍

基于springboot的博客管理系统拥有两个角色，分别为管理员和博主，具体功能如下：

管理员：个人中心、博主管理、文章分类管理、文章信息管理、留言管理、公告管理等

博主：个人中心、发布文章、文章管理、收藏管理、前端查看博客和公告


## 2、项目技术

后端框架：springboot

前端框架：Bootstrap、VUE、jsp、css、JavaScript、JQuery

前后端分离项目

## 3、开发环境

- JAVA版本：JDK1.8，其它版本理论上可以
- IDE类型：IDEA、Eclipse、Myeclipse都可以。推荐IDEA与Eclipse
- tomcat版本：Tomcat 7.x、8.x、9.x版本均可
- 数据库版本：MySql 5.7
- maven版本：无限制
- 硬件环境：Windows 或者 Mac OS


## 4、功能介绍

### 4.1 登录

![后台登陆](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252322588.jpg)

![博主前端登陆 ](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252322156.jpg)

博主和管理可以登录至后台，博主也可以登录至前台页面

### 4.2 博主前端模块

![前端首页](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252323331.jpg)

![前端所有文章](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252323668.jpg)

![前端-博客内容](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252323461.jpg)

![博主-前端个人中心](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252323014.jpg)

![博主-前端个人收藏](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252323323.jpg)

博主可以在前端根据分类浏览博客内容，可以评论博客、收藏博客、查看个人信息、个人收藏等功能

### 4.3博主后台 模块

![博主-后台-发布博客](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252325236.jpg)

![博主-后台-收藏管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252325234.jpg)

![博主-后台-文章信息管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252325861.jpg)

- 发布文章：博主可以发布文章，文章内容共包括标题、类型、图片、日期、内容，其中内容采取富文本编辑器
- 文章管理：博主可以根据标题和账号查询博客，修改和删除博客，查看博客评论
- 收藏管理：博主可以根据博客名称查询博客，也可以查看博客详情、删除博客

### 4.4 管理员后台模块

![管理员-博主管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252328777.jpg)

![管理员-文章分类管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252328578.jpg)

![管理员-文章管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252328583.jpg)

![管理员-公告管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252328919.jpg)

![管理员-投诉管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252332774.jpg)

![管理员-轮播图管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252328558.jpg)

- 博主管理：管理员可以根据博主账号和姓名查询博主信息，并能够增加、修改和删除博主
- 文章分类管理：管理员可以根据分类名查询博客分类信息，并能够增删改分类
- 文章信息管理：管理员可以根据文章标题、博主账号查询博客，并能够修改和删除博客，查看博客评论
- 投诉管理：管理员可以根据标题和博主账号查询投诉信息，并能删除和修改投诉信息
- 公告管理：管理员可以根据标题查询公告，并能增删改公告信息

### 4.4 设计文章目录

![文档目录](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205252332274.jpg)

## 5、获取方式

关注公众号 ：程序员王不二，后台回复关键词“**博客5**”获取源码

![公众号](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205261246794.png)
