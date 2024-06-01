# 博客配置仓库

- **[简体中文](./README-cn.md)**
- **[English](./README.md)**

***

- [博客配置仓库](#博客配置仓库)
  - [关于本项目](#关于本项目)
  - [如何使用本模板](#如何使用本模板)
    - [使用typora生成html页面](#使用typora生成html页面)
    - [部署到项目中](#部署到项目中)
    - [链接到博客主页面中](#链接到博客主页面中)
  - [引用](#引用)

***

## 关于本项目

**这里是我的个人博客配置**

本模板是我根据我的个人主页模板设计的，没有使用任何框架。

本模板是我根据我的个人主页模板设计的，没有使用任何框架。它有以下优点：
- 使用markdown编写博客
- 容易理解
- 易于使用
- 简洁大方
- 博客正文页面主题和风格可以随意切换
- 非常轻量

## 如何使用本模板

### 使用typora生成html页面

首先，本博客部署需要Typora这个软件的帮助。

- [Typora官网](https://typora.io/)

使用markdown便携完博客之后，使用Typora生成对应的html文件。

![](./assets/1.png)

如果您有任何问题，请在本仓库或我的个人主页仓库留下您的问题，我会主动联系您。

### 部署到项目中

`./blogs`目录中是所有博客的目录中，目录中需要有html文件和对应的assets存放图片的目录。

```bash
├── blogs
│   ├── Apache-and-Nginx
│   │   ├── Apache-and-Nginx.html
│   │   ├── Apache-and-Nginx.md
│   │   └── assets
│   │       ├── 1.png
│   │       └── 2.png
```

### 链接到博客主页面中

`./index.html`中

```html
<h2>📚<strong>Blogs</strong></h2>
```

下面就是博客的链接，对应修改博客的名称、链接、图片和时间即可。

```html
<li>
    <div class="blog-item">
        <img src="blogs/Apache-and-Nginx/assets/2.png" class="blog-image">
        <div class="blog-info">
            <a href="./blogs/Apache-and-Nginx/Apache-and-Nginx.html" target="_blank">
                <strong class="kaishu">Apache和Nginx是什么？｜Nginx和Reactor是什么？｜网路IO的本质｜阻塞队列｜异步非阻塞IO</strong>
            </a>
            <span class="date">2023-08</span>
        </div>
    </div>
</li>
```

## 引用

设计部分基于 [Qiaolin Yu](https://github.com/Qiaolin-Yu) 的个人主页。