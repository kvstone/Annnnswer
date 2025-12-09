# Annnnswer - 问答游戏

一个使用HTML、CSS和JavaScript构建的互动问答游戏。

## 概述

Annnnswer 是一款基于网页的问答游戏，通过引人入胜的界面让用户与测验内容进行互动。该游戏利用现代网络技术提供交互式体验。

## 功能特点

- 互动问答界面
- 使用 Swiper.js 实现响应式设计，提供流畅导航
- 基于 JSON 的问题数据，便于内容管理
- 使用 TweenMax 实现动画过渡效果

## 使用的技术

- HTML5
- CSS3
- JavaScript (ES6+)
- jQuery
- Swiper.js - 触摸滑块功能
- TweenMax - 动画和过渡效果

## 项目结构

```
.
├── index.html          # 主HTML文件
├── css/
│   └── swiper.min.css  # Swiper CSS库
├── js/
│   ├── TweenMax.min.js # 动画库
│   ├── jquery-1.10.1.min.js # jQuery库
│   └── swiper.min.js   # Swiper JS库
└── q/
    ├── demo.json       # 示例问题数据
    ├── demo1.json      # 额外的问题数据
    └── demo2.json      # 额外的问题数据
```

## 安装设置

1. 克隆或下载此仓库
2. 在您喜欢的网页浏览器中打开 `index.html`
3. 游戏应该会加载并准备就绪

## 数据结构

游戏在 `q/` 目录中的JSON文件存储问题数据。您可以修改这些文件来自定义游戏中的问题和答案。

## 在线演示

访问游戏的在线版本：https://kvstone.github.io/Annnnswer/

## 许可证

此项目是开源的，采用MIT许可证。
