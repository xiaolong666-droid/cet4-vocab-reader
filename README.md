# CET-4 Core Vocabulary Reader | 英语四级核心词点击朗读

一个纯静态的英语四级词汇学习网页，点击任意单词卡片即可朗读，支持搜索、按单元筛选和语速调节。

## 功能特性

- **点击朗读** — 点击单词卡片，浏览器即时朗读该单词
- **中文语音** — 使用 `zh-CN` 中文语音引擎朗读英文单词，模拟中式发音
- **2327 个核心词** — 涵盖四级全部 10 个单元，已去重
- **即时搜索** — 支持按单词或中文释义实时搜索
- **单元筛选** — 按 Unit 1 - Unit 10 筛选词汇
- **语速调节** — 0.5x ~ 2.0x 可调
- **纯静态** — 单个 HTML 文件，无后端依赖，双击即用

## 使用方法

1. 下载 `英语四级核心词_点击朗读.html`
2. 用浏览器打开（推荐 Chrome / Edge）
3. 点击任意单词卡片即可朗读

> 朗读功能依赖浏览器的 Web Speech API。首次使用时，浏览器可能需要加载语音引擎，稍等片刻即可。

## 技术栈

- HTML5 + CSS3 + 原生 JavaScript
- Web Speech API（`speechSynthesis`）
- Google Fonts（Playfair Display / JetBrains Mono / Noto Serif SC）

## 项目结构

```
CET4-Vocabulary-Reader/
├── 英语四级核心词_点击朗读.html   # 主文件（自包含，含全部单词数据）
└── README.md
```

## 数据来源

单词数据提取自《英语四级核心词》PDF，包含单词、音标和中文释义，按 10 个单元组织，共 2327 个去重词条。

## License

MIT
