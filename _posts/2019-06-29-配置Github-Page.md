---
layout: post
title: 配置Github Page
date: '2019-06-29 20:27:37 +0800'
categories: 日常Log
published: true
author: Lison
---
### 关于配置的主要操作流程

可以参照Github Page提供的操作指南不赘述，传送门：
[Github配置官方操作流程](https://pages.github.com)
![](/assets/blog-img0001.png)

### 本小记主要分享操作过程中几个问题

1. 如果打算用github.io的二级域名，创建的repo必须二级域名的名字跟github帐号名一致，否则只能以github帐号名的二级域名下的文件的形式访问到；
2. 开始直接自己在repo中添加了md文档和_config.yml，虽然可以把Page跑起来，但并没有基于Jekyll更为方便。因为Jekyll帮我们做好了**文件目录**、**预设各默认页面**，同时Jekyll本身还有很多插件可用，虽然我现在还没用到；
3. 如果需要使用非系统自带主题，需要在_config.yml里面添加remote_theme，且前提需要在gemfile里面添加对于jekyll-remote-theme的依赖，具体是下面两步：
	1. 在根目录的Gemfile里添加如下内容：
```shell
gem "jekyll-remote-theme"
```
	2. 运行下面的命令，完成所以依赖组件的安装：
```shell
$ bundle
```

### 如何编写内容

网上提供了很多方式编写Github Page上内容的方法、工具，这里分享下自己的常用的工具**Typora**（一款肥肠精致的Markdown编辑工具），传送门：
[Typora官网](https://typora.io)

另外推荐款在线编辑的工具。直接授权访问Github账户，可以非常方便访问以及编辑，传送门：
[Prose.io](https://prose.io)
