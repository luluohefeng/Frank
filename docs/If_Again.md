# 学习建立一个网站

## 我希望你最后得到的不是“会跟着教程部署一个网站”，而是真的理解一个网站为什么能运行。

<details markdown="block">
  <summary>✳️ 目录</summary>
- TOC
{:toc}
</details>

---

## 网站建立的主要方式

目前主流有 5 种方式：

1. 手写代码开发
2. 使用网站构建工具
3. 使用CMS系统
4. 使用开源框架开发
5. 使用云服务/低代码平台

### 方式1：纯代码开发（传统开发）

前端代表技术

- HTML
- CSS
- JavaScript

我们的Frank AI Lab属于代码开发方式。[点击查看Frank AI Lab](https://luluohefeng.github.io/Frank-AI-Lab/)

自由度大，但是开发周期长，维护成本高。

### 方式2：网站构建工具（拖拽建站）

适合：

- 企业官网
- 个人主页
- 活动页面

类似 PPT 制作，几小时可以完成网站，不需要编程知识。但是定制能力有限。

上传PDF

↓

RAG检索

↓

AI回答 这种功能不能实现。

### 方式3：CMS建站（内容管理系统）

适合：

- 博客
- 新闻网站
- 企业官网
- 论坛

### 方式4：现代框架开发（专业互联网开发）

前端

React/Vue

↓

API接口

↓

后端

Spring Boot/FastAPI

↓

数据库

MySQL   这是现在互联网公司的主流，学习成本高。

### 方式5：云服务/低代码平台

很多基础功能（如登录功能）已经提供，适合：快速验证想法。

例如：

一个AI产品Demo：

一天上线。


## 明确目标

我们做：Frank AI Lab
> 个人 AI 工程主页。

建立这样的文件夹  D:\luluohefeng\Frank-AI-Lab

## 第一步：HTML（结构）+CSS（样式）

在Frank-AI-Lab文件夹内建立： index.html文件 + style.css文件 + image文件夹。

index.html = 定义对象和结构（像 C++ 的类结构）
> 只管创造，不管美丑

style.css = 控制外观（像给对象设置属性）
> 只管美化，不管功能
CSS负责：颜色、大小、位置、间距、动画、布局

image文件夹 = 存储图片文件的文件夹

> 这是index.html的内容：

![i_html](assets/image/Again/i_html.png)

> 这是style.css的内容：

![i_css](assets/image/Again/i_css.png)

回到文件资源管理器，点击index.html文件，即可在浏览器中打开。

得到这样的网站：

![1lab](assets/image/Again/1lab.png)

我小小修改了一下index.html文件 + style.css文件，得到这样的网站：

![2lab](assets/image/Again/2lab.png)

## 须知

HTML(结构) -> CSS(样式) -> JavaScript(行为) -> 浏览器显示的网站

HTML(创造一个按钮) -> CSS(美化这个按钮) -> JavaScript(实现点击按钮后发生的事情) -> 浏览器显示的网站

- div是容器，是装汉堡的纸袋子（属于HTML）

浏览器看到的是

<div>

   里面装了一些东西

</div>

有点像C++的类，但是没有方法。

- class 是标签，是汉堡纸袋子上的取餐号。

取餐号是让你找的自己的汉堡，class 是让 CSS 找到它的标签。

- flex 是布局，控制盒子里面东西怎么排列（属于CSS）











