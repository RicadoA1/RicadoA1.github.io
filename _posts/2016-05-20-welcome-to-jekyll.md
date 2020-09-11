---
layout: page
title:  "搭建博客"
subtitle: "A minimal Jekyll theme"
date:   “2020-09-10.周四”
categories: ["general"]
---
> Github Pages + Jekyll 快速部署个人博客

> - github pages 
>  - GitHub给所有用户提供了一个个人主页
>  - 如何访问：（用户名）.github.io  （RicadoA1.github.io）
>  - 如何编写主页：建立一个用个人域名为项目名的远程版本仓库，只需要向远程版本仓库的master分支提交代码即可（代码中必须有一个文件index.html文件）
> - jekyll
>  - 它是一个可以将Markdown语法自动编译为html语法的工具
>  - 安装：不需要自己安装，当访问gihthub中已经预安装完毕
>  - 使用：不需要人为使用，当请求个人域名时，GitHub服务器会读取仓库（以个人域名命名的远程版本仓库）中的master分支中的代码，如果该代码为markdown语法将会自动使用jekyll编译为html语法，并返回客户端

- 建立一个以个人域名为项目名的远程版本仓库
- 访问一个网址：主题网址：http://jekyllthemes.org/ 选择一个主题将代码复制到我方仓库master分支中
- 将远程版本库中代码copy到本地电脑中
   - 点击头像，code，复制链接
   - 在文件打开终端执行克隆：git clone -b master https://github.com/RicadoA1/RicadoA1.github.io.git myblog
   - 从远程版本仓库克隆下载的代码会自动创建本地版本仓库
- 修改配置文件
- 书写博客
