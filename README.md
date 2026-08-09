# 🌸 谎言十年 (Lies Ten Years Ago) · 二次元视觉小说

> **Ren'Py 引擎 · 多语言 · Android APK 发布**
> A Ren'Py visual novel with multi-language support & Android builds

[![Ren'Py](https://img.shields.io/badge/引擎-Ren'Py-ff69b4)](https://www.renpy.org/)
[![AVG](https://img.shields.io/badge/类型-视觉小说%20AVG-9cf)](#)
[![Android](https://img.shields.io/badge/平台-Android%20APK-brightgreen)](#)
[![多语言](https://img.shields.io/badge/多语言-tl%20支持-blue)](#)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

基于 **Ren'Py** 引擎的二次元视觉小说（AVG）游戏，讲述十年前谎言背后的故事，已发布 Android APK。

A Chinese visual novel built with the Ren'Py engine — the story of a lie from ten years ago, released on Android APK.

## 📖 故事简介 Story

十年前的一句谎言，如今如何收场？跟随主角在回忆与现实中交错前行，揭开埋藏多年的真相。

How does a lie from ten years ago come to an end? Walk between memories and reality to uncover the long-buried truth.

## 🗂️ 项目组成 Project Structure

```text
game-project/       # Ren'Py 游戏项目
└── game/
    ├── scripts/          # 游戏脚本
    ├── tl/               # 多语言文本
    ├── images/           # 立绘 · CG · 背景（原创 AI 生成素材）
    │   ├── backgrounds/  # 背景图（Web 压缩版 JPG）
    │   ├── heroine/      # 女主角立绘
    │   └── band/         # 乐队角色
    ├── gui/              # 界面
    └── SourceHanSansLite.ttf  # 思源黑体（开源字体）
```

## ▶️ 运行 Run

使用 Ren'Py SDK 打开 `game-project` 目录即可运行。

```powershell
# 下载 Ren'Py SDK: https://www.renpy.org/latest.html
renpy.exe game-project
```

## 📝 Notes / 说明

- 游戏含多语言文本目录 `game/tl/`，支持多语言
- 大型语音工具与模型文件（COEIROINK、语音包等）体积较大，未包含在仓库中
- 背景素材为原创 AI 生成并压缩为 JPG（原版 PNG 未包含）；立绘为原创 AI 生成 PNG（保留透明通道）

## 📄 License

[MIT](LICENSE) © 2026 [sekai-lyr](https://github.com/sekai-lyr)

---

**⭐ If this project helped you, star it! 如果这个项目对你有帮助，欢迎 Star！**
