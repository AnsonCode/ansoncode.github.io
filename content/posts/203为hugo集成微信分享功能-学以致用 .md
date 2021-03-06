---
title: "203为hugo博客集成微信分享功能"
date: 2021-01-22T16:37:29+08:00
tags: [ "hugo"]
categories:
  - "学以致用"
draft: true
---

# 前言
本文详细介绍了“如何用hugo**免费**搭建个人博客并自动化发布部署”，

# 絮絮叨
很久

# 需求分析

核心诉求如下：
- 安全性高：对于博客，文章是最主要的资产，一定要保证数据安全不容易丢失；
- 拓展性强：博客就是一个乐高玩具，一定要能自由定制功能，承载我的小创意；
- 写作方便：写博客主要时间都花费再写文章上，那么写作体验一定要好；
- 体验良好：本身是一名产品经理，产品体验肯定要考虑（交互设计及UI设计）；
- 成本要低：搭建博客本身就是为了“玩”，花太多金钱就不太值得了；

# 技术选型

目前市场上有很多博客搭建工具，主要分为两类：静态博客和动态博客。
- 动态博客：一套web系统，博文存入数据库，访问文章时从数据库读取博文，并基于模板渲染为html展示给用户。我之前用过的wordpress属于动态博客。
- 静态博客：通过工具，直接将博文编译成最终的html文件，放入服务器接口访问。当前用的最多的静态博客是hexo。


# 操作步骤（window10)

- 配置博客：安装hugo->新建站点->安装模板及预览->新增文章->配置站点
- 部署博客：新建仓库->授权travis->修改配置->提交站点->域名配置（可选）
## 配置博客

### 安装hugo


# 后记
恭喜你，看到这里，说明你已经掌握了 用hugo**免费**搭建个人博客并自动化发布部署 的所有技巧！心动不如行动，马上搭建你的BLOG吧！

# 参考
- Nodejs获取微信签名并使用JSSDK：https://juejin.cn/post/6844903941478547470#heading-0
- js微信分享接口调用详解：https://www.jb51.net/article/166053.htm
- 【公众号开发】用Serverless快速上手微信公众号开发：https://www.jianshu.com/p/ed0ce24b1e3a
- 微信公众平台开发指南：https://developers.weixin.qq.com/doc/offiaccount/Basic_Information/Access_Overview.html
- nodejs 中koa框架下的微信公众号开发初始篇:https://www.cnblogs.com/shtyhome/p/5676845.html
- 微信 JS 接口签名校验工具：https://mp.weixin.qq.com/debug/cgi-bin/sandbox?t=jsapisign
- 微信开发 遇到 config:invalid url domain:https://blog.csdn.net/u010575112/article/details/52661936
