# 😩「能不能好好说话？」 拼音首字母缩写翻译工具

社交平台上通过拼音首字母缩写指代特定词句的情况越来越多，为了让常人勉强能理解这一门另类沟通方式、做了这一个划词翻译油猴脚本。

## 独立网页版本

https://lab.magiconch.com/nbnhhsh/

## 安装脚本

安装好用户脚本浏览器插件之后，访问 [nbnhhsh.user.js](https://github.com/itorr/nbnhhsh/raw/master/nbnhhsh.user.js) 完成脚本安装

>脚本版本目前仅会在 `https://weibo.com/` 页面下运行，划词时会提交所选文字以用于转义。

## 用户脚本是什么？

用户脚本是一段代码，它们能够优化您的网页浏览体验。安装之后，有些脚本能为网站添加新的功能，有些能使网站的界面更加易用，有些则能隐藏网站上烦人的部分内容。用户脚本都是由用户编写并向全世界发表的，您可以免费安装，轻松体验。

安装过程可参考 [https://greasyfork.org/zh-CN/](https://greasyfork.org/zh-CN/#home-step-1) 首页的，**第一步：安装一个用户脚本管理器** 章节

## 如何在更多网站上使用这个用户脚本？

在对应的用户脚本配置里可以设置 **用户匹配**，添加对应 URL 规则即可。

## 贡献词条

在每一个词条右上角都有 `+` 图标的按钮，点击可以提交对应文字，审核后会整理录入。

## 有更离谱的例文？

请用任意方式发我！😖

## 仓库地址

[https://github.com/itorr/nbnhhsh](https://github.com/itorr/nbnhhsh)

## 构建方式

本项目使用 TypeScript+Webpack 开发，应该安装以下工具

```bash
npm install -g typescript webpack
npm install #webpack: raw-loader
```

静态资源需由修改者执行自动生成程序，一并提交～

```bash
npm run build #输出 nbnhhsh.user.js
```
