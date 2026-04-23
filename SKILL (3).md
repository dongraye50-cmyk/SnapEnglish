---
name: snapenglish
version: 2.0.0
author: SnapEnglish
description: "Upload a photo or screenshot → get challenged to express it in English → see how a native speaker actually thinks. Built on cognitive linguistics (Lakoff's conceptual metaphor, Langacker's cognitive grammar). No grammar rules. No translation drills. Just the picture in a native speaker's mind. IELTS Speaking Part 2/3 tags included."
tags: [english, speaking, IELTS, cognitive-linguistics, language-learning, chinese]
language: zh-CN
requires: knowledge-base
---

## 这个 Skill 做什么

上传一张照片或截图，经历完整的三步练习：

```
1. 出题      AI 出一道挑战，等你用英文表达
2. 你作答    先自己说，再看答案
3. 解析      看母语者脑中的画面，找到你的思维卡点
```

**两种输入：**

| 类型 | 例子 | 出题风格 |
|---|---|---|
| 实景图 | 咖啡馆、街景、旅行照 | 描述类（雅思 Part 2）|
| 内容截图 | 微博、公众号、歌词 | 观点表达类（雅思 Part 3）|

## 安装方法

1. 打开 Claude.ai → 新建 Project
2. 把 `SYSTEM_PROMPT.md` 全部内容粘贴进「Project instructions」
3. 上传 `knowledge-base/` 里的 5 个 `.md` 文件
4. 在这个 Project 里上传图片开始练习

## 使用说明

- 上传图片后，AI 会出一道题，然后停下来等你
- 先自己用英文说出来，再发给 AI
- 收到你的回答后，AI 才会给出推荐表述和解析
- 如果你想直接看答案，回复「直接给我答案」

## 它不做什么

- 不帮你翻译（先让你自己想）
- 不讲语法规则（只讲母语者脑中的画面）
- 不夸你「英语进步神速」
