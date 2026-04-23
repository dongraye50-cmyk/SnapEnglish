# SnapEnglish · 英语思维教练

> *Turn a moment into English.*

把你拍的照片、刷到的帖子发过来——不是让你翻译，而是让你先自己说，再看母语者脑中的画面。

---

## 它做什么

三步，一次完整练习：

```
1. 上传图片或截图
   ↓
2. AI 出题，你先用英文说出来
   ↓（AI 等你，不会自顾自给答案）
3. 发出你的回答
   ↓
🗣 推荐表述   🔍 解析   🩺 病句   ✨ 收藏
```

**关键：AI 出完题会停下来等你。先自己说，再看答案。**

---

## 两种输入

| 类型 | 例子 | 出题感觉 |
|---|---|---|
| 实景图 | 咖啡馆、街景、旅行照 | 「用英文描述你看到的这一刻」|
| 内容截图 | 微博、公众号、歌词 | 「你有没有过这种感受/你怎么看这件事」|

截图类不是让你翻译——AI 会把内容的核心意思化成一个问你感受或观点的问题，你用英文回答。

---

## 适合谁

- 有词汇量但说出来不自然
- 背过语料但感觉和自己没关系
- 备考雅思口语 Part 2 / Part 3
- 想把日常生活变成英语素材库

---

## 快速安装

**方式一：Claude Project（推荐）**

1. 打开 [claude.ai](https://claude.ai) → 新建 Project
2. 把 [`SYSTEM_PROMPT.md`](./SYSTEM_PROMPT.md) 全部内容粘贴进「Project instructions」
3. 把 `knowledge-base/` 里的 5 个 `.md` 文件上传进 Project
4. 在这个 Project 里上传图片，开始练习

**方式二：直接粘贴（零配置）**

把 `SYSTEM_PROMPT.md` 内容粘贴到对话框开头，然后上传图片。不上传知识库也能用，但解析精准度会降低约 20-30%。

---

## 效果示例

### 示例 A · 实景图（胡同咖啡馆）

**AI 出题：**

```
📍 胡同转角，一家藏在花里的咖啡馆

✏️ 挑战

我穿过胡同，突然被一抹蓝拦住——
绣球花从红门边溢出来，墙上挂着一顶草帽。

用英文说说看 ↓
```

**用户作答 → AI 给出推荐表述：**

> *I was cutting through a hutong when the blue stopped me — hydrangeas spilling out around a red door, a straw hat on the wall, the whole place perfectly still.*

**解析片段：**

```
🔍 the blue stopped me

颜色做主语，它有力量，它把你的身体拦住了。
用户写的 "a blue color attracted my attention" 是人做主语，颜色是被动的；
母语者反过来，让颜色出击——一个词的主语选择，画面感完全不同。
```

🎯 `雅思口语 Part 2 · 描述一处印象深刻的地方`

---

### 示例 B · 内容截图（微博观点类）

**AI 出题：**

```
📍 来自微博 · 亭林镇无业青年

💬 关于「为别人做事 vs 为自己做事」

你有没有过这种感受：
做某件事，越来越是为了别人的眼光和反应，
而不是因为你真的想做。
等那些眼光消失了，内心反而空了。

用英文说说这种状态，或者你对这件事的看法 ↓
```

**推荐表述：**

> *Praise is addictive — it hooks you slowly, until you're no longer acting from who you are but performing for the next hit. When the applause dries up, there's nothing left to hold you together.*

**解析片段：**

```
🔍 it hooks you slowly

hook 自带一个画面：钩子慢慢刺进来，你感觉不到，直到拔不出来。
不说 "praise attracts you"——attract 是吸引，你还可以走开；
hook 是锁住，你已经跑不了了。
```

🎯 `雅思口语 Part 3 · 社交媒体与心理健康 / 成就感与外部认可`

---

## 知识库说明

本 Skill 包含 5 个认知语言学模块，共 42 条检索优化条目：

| 文件 | 覆盖范围 |
|---|---|
| `kb_metaphors.md` | up/down 情绪、动词图式（hook/drift/spill）|
| `kb_cognitive_grammar.md` | 介词图式、物体做主语、被动焦点 |
| `kb_sentence_structure.md` | 嵌套 vs 线性、关系从句 |
| `kb_impersonal_subject.md` | 无灵主语、状态代替动作 |
| `kb_tense.md` | 时态镜头 × 动作状态 |

所有条目以「触发场景」开头，为向量检索优化。

---

## 与 SnapEnglish App 的关系

| | Skill | SnapEnglish App |
|---|---|---|
| 使用门槛 | 需要 Claude 账号 | 直接访问 |
| 出题逻辑 | ✅ 完全相同 | ✅ 完全相同 |
| 知识库 | ✅ 完全相同 | ✅ 完全相同 |
| 闪卡保存 | ❌ 对话结束即消失 | ✅ 永久保存 |
| 复习系统 | ❌ | ✅ SM-2 遗忘曲线 |

---

## 常见问题

**Q：AI 出完题为什么不继续？**

设计如此。它在等你先说。发出你的英文版本，它才会继续。

**Q：我可以直接要答案吗？**

回复「直接给我答案」，AI 会跳过等待直接给推荐表述和解析。

**Q：截图类为什么不是让我翻译原文？**

因为翻译练不了思维。AI 会把内容核心化成一个让你表达感受或观点的问题——你用英文回答，练的是「用英语思考」，不是「把中文换成英文」。

**Q：上传什么截图效果最好？**

有观点、有情感、有画面感的内容出题质量最高——微博、公众号文章、歌词、影视台词。纯信息类（菜单、价格表）效果偏低。

---

## License

MIT — 可自由使用、修改、分发。

---

*SnapEnglish · My English, my moments.*
