# Mineradio-OREN

Mineradio 是一款 Windows 桌面沉浸式音乐播放器，把天气电台、搜索播放、歌词舞台、粒子视觉和 3D 歌单架组合成一个更接近现场感的私人音乐空间。

> 本项目 Fork 自 [XxHuberrr/Mineradio](https://github.com/XxHuberrr/Mineradio)，新增了**酷狗音乐登录**支持。

## 新增功能

- **酷狗音乐登录**：支持通过 Cookie 导入登录酷狗音乐，同步歌单和个人收藏
- 酷狗音乐搜索、歌曲播放、歌词获取
- 与网易云音乐、QQ 音乐并列的第三方登录入口

## 酷狗音乐使用说明

1. 打开 Mineradio，在登录弹窗中选择「酷狗音乐」
2. 在浏览器中打开 [www.kugou.com](https://www.kugou.com/) 并登录
3. 从浏览器 DevTools -> Application -> Cookies 复制含 token 或 userid 的 Cookie
4. 粘贴到 Mineradio 的「手动导入」框中，点击保存
5. 登录成功后歌单自动同步

## 核心特性（原版）

- Open-Meteo 天气电台
- Emily / 默认播放态视觉，歌词舞台与粒子舞台同步
- 基于节奏的电影镜头视觉系统
- 3D 歌单架
- 网易云音乐、QQ 音乐账号接入

## 开发运行

`ash
npm install
npm start
npm run build:win
`

## 版权与授权

本项目基于 [XxHuberrr/Mineradio](https://github.com/XxHuberrr/Mineradio)，采用 GPL-3.0 授权。

Copyright (C) 2026 XxHuberrr. Mineradio-OREN 新增代码同样采用 GPL-3.0。
