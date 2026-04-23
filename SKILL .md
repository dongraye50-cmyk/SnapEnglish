---
name: snapenglish
version: 3.0.0
author: SnapEnglish
description: "Upload a photo or screenshot → get challenged to express it in English → see how a native speaker actually thinks. Adapts to your IELTS speaking target (5.0–7.0+). Outputs feel like real speech, not textbook English — drawing on the rhythm of shows like Succession and The Crown for 7.0+ targets. Built on cognitive linguistics (Lakoff's conceptual metaphor, Langacker's cognitive grammar). No grammar rules. No translation drills. Export your practice as SVG, auto-flip GIF, or interactive HTML flashcard."
tags: [english, speaking, IELTS, cognitive-linguistics, language-learning, flashcard, chinese]
language: zh-CN
requires: knowledge-base
---

## 这个 Skill 做什么

开场先问你一个问题，然后进入完整三步练习：

```
开场    → 告诉 AI 你的雅思口语目标分数（只问一次）
          ↓
轮次一  → 上传图片或截图，AI 出题，等你先说
          ↓
轮次二  → 你发出英文答案，AI 给出四张卡
          推荐表述 · 解析 · 病句 · 收藏
          ↓
轮次三  → 选择是否生成闪卡（SVG / GIF / HTML）
```

**关键：AI 出完题会停下来等你。先自己说，再看答案。**

## 根据目标分数调整输出

| 目标分数 | 推荐表述风格 |
|---|---|
| 5.0–5.5 | 清晰简洁，词汇难度适中 |
| 6.0–6.5 | 地道短语 + 稍复杂句式（默认）|
| 7.0+ | 高口语质感，借鉴 Succession / The Crown 的说话节奏 |

## 两种输入

| 类型 | 例子 | 出题感觉 |
|---|---|---|
| 实景图 | 咖啡馆、街景、旅行照 | 「用英文描述你看到的这一刻」|
| 内容截图 | 微博、公众号、歌词 | 「你有没有过这种感受 / 你怎么看这件事」|

截图类不是让你翻译——AI 把内容核心化成一个问你感受或观点的问题。

## 闪卡三种格式

练习结束后可以选择：

| 选项 | 说明 |
|---|---|
| A · 静态图片 | SVG 格式，截图保存到相册 |
| B · GIF 动画 | 5秒自动翻面的网页，录屏后保存成 GIF |
| C · 网页版 | 点击翻转 + 复制英文按钮，在浏览器打开 |

## 安装方法

1. 打开 Claude.ai → 新建 Project
2. 把 `SYSTEM_PROMPT.md` 全部内容粘贴进「Project instructions」
3. 上传 `knowledge-base/` 里的 5 个 `.md` 文件
4. 在这个 Project 里开始对话，AI 会先问你目标分数

## 它不做什么

- 不帮你翻译（先让你自己想）
- 不讲语法规则（只讲母语者脑中的画面）
- 不重复问你目标分数
- 不夸你「英语进步神速」
