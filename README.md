# 🍌 Banana Prompt Quicker

> Prompts quicker is ALL you 🍌 need

一个 Chrome 扩展,让你在 Google AI Studio 和 Gemini 官网快速插入热门提示词。

## ✨ 功能特性

- 🚀 **快速插入** - 一键插入全网热门提示词（Twitter）
- 🎯 **多平台支持** - 支持 Google AI Studio 和 Gemini 官网
- ✏️ **自定义提示词** - 添加和管理你自己的提示词

## 📸 预览

![](/images/modal.png)

![](/images/input.png)

## 🚀 安装

### Chrome Web Store 安装
WIP, 上架中

### 从 Release 安装

1. 下载最新的 [Release 版本](https://github.com/glidea/banana-prompt-quicker/tree/main/release)

2. 在 Chrome 中加载扩展
   - 打开 Chrome 浏览器,访问 `chrome://extensions/`
   - 开启右上角的「开发者模式」
   - 点击「加载已解压的扩展程序」
   - 选择项目根目录

3. 访问 [Google AI Studio](https://aistudio.google.com/) 或 [Gemini](https://gemini.google.com/) 开始使用


## 🤝 贡献提示词

1. Fork 本仓库
2. 编辑 `prompts.json` 文件,添加你的提示词:
```json
{
  "title": "提示词标题",
  "preview": "效果预览图片",
  "prompt": "提示词内容",
  "author": "作者",
  "link": "https://来源链接（可选）",
  "mode": "generate or edit"
}
```
3. 提交 Pull Request
