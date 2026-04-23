# SnapEnglish · 英语思维教练

> *Turn a moment into English.*

把你拍的照片、刷到的帖子发过来——不是让你翻译，而是让你先自己说，再看母语者脑中的画面。

---

## 它做什么

四步，一次完整练习：

```
开场    告诉 AI 你的雅思口语目标分数（只问一次，之后自动调整难度）
  ↓
上传    图片或截图，AI 出题，停下来等你
  ↓
作答    先用英文说出来，再发给 AI
  ↓
解析    推荐表述 · 解析卡 · 病句卡 · 收藏卡
  ↓
闪卡    选择是否生成 SVG / GIF / HTML 格式闪卡
```

---

## 根据目标分数调整

| 目标分数 | 推荐表述风格 |
|---|---|
| 5.0–5.5 | 清晰简洁，词汇难度适中 |
| 6.0–6.5 | 地道短语 + 稍复杂句式（默认）|
| 7.0+ | 高口语质感，借鉴 Succession / The Crown 的说话节奏感 |

7.0+ 的推荐表述会是这种感觉：

> *Here's the thing — praise feels good, and then it feels necessary, and then you're not doing it for yourself anymore. You're performing. And the moment the applause stops? There's nothing left.*

而不是书面腔：

> ~~Praise is a substance that causes addiction and gradually affects people's behavior.~~

---

## 两种输入

| 类型 | 例子 | 出题感觉 |
|---|---|---|
| 实景图 | 咖啡馆、街景、旅行照 | 「用英文描述你看到的这一刻」|
| 内容截图 | 微博、公众号、歌词 | 「你有没有过这种感受 / 你怎么看这件事」|

截图类不是让你翻译——AI 会把内容的核心意思化成一个问你感受或观点的问题。

---

## 闪卡三种格式

练习结束后可以选：

| 选项 | 说明 | 适合场景 |
|---|---|---|
| A · 静态图片 | SVG，截图保存 | 存相册、发朋友圈 |
| B · GIF 动画 | 5秒自动翻面，录屏保存 | 发给朋友、发群里 |
| C · 网页版 | 点击翻转 + 复制英文 | 在电脑上复习 |

---

## 适合谁

- 有词汇量但说出来不自然
- 备考雅思口语 Part 2 / Part 3
- 想把日常生活和刷到的内容变成英语素材
- 目标 7.0+，想练出真正有质感的口语

---

## 快速安装

**方式一：Claude Project（推荐，效果最好）**

1. 打开 [claude.ai](https://claude.ai) → 新建 Project
2. 把 [`SYSTEM_PROMPT.md`](./SYSTEM_PROMPT.md) 全部内容粘贴进「Project instructions」
3. 把 `knowledge-base/` 里的 5 个 `.md` 文件上传进 Project
4. 开始对话，AI 会先问你目标分数

**方式二：直接粘贴（零配置）**

把 `SYSTEM_PROMPT.md` 内容粘贴到对话框开头，然后开始对话。不上传知识库也能用，但解析精准度会降低约 20-30%。

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

**推荐表述（6.5目标）：**

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

### 示例 B · 内容截图（微博观点类，目标 7.0+）

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

**推荐表述（7.0+ 口语感）：**

> *Here's the thing — praise feels good, and then it feels necessary, and then you're not doing it for yourself anymore. You're performing. And the moment the applause stops? There's nothing left to hold you together.*

🎯 `雅思口语 Part 3 · 社交媒体与心理健康 / 成就感与外部认可`

---

## 知识库说明

5 个认知语言学模块，共 42 条检索优化条目：

| 文件 | 覆盖范围 |
|---|---|
| `kb_metaphors.md` | up/down 情绪、动词图式（hook/drift/spill）|
| `kb_cognitive_grammar.md` | 介词图式、物体做主语、被动焦点 |
| `kb_sentence_structure.md` | 嵌套 vs 线性、关系从句 |
| `kb_impersonal_subject.md` | 无灵主语、状态代替动作 |
| `kb_tense.md` | 时态镜头 × 动作状态 |

---

## 与 SnapEnglish App 的关系

| | Skill | SnapEnglish App |
|---|---|---|
| 使用门槛 | 需要 Claude 账号 | 直接访问 |
| 出题逻辑 | ✅ 完全相同 | ✅ 完全相同 |
| 知识库 | ✅ 完全相同 | ✅ 完全相同 |
| 分数自适应 | ✅ | ✅ |
| 闪卡导出 | ✅ SVG / GIF / HTML | ✅ 永久保存 |
| 复习系统 | ❌ | ✅ SM-2 遗忘曲线 |

---

## 常见问题

**Q：AI 出完题为什么不继续？**
设计如此。它在等你先说。发出你的英文，它才会继续。

**Q：我可以直接要答案吗？**
回复「直接给我答案」，AI 会跳过等待直接给推荐表述和解析。

**Q：GIF 选项怎么用？**
AI 会生成一个5秒自动翻面的网页，你在浏览器打开后用录屏工具（Mac 的 QuickTime、手机的屏幕录制）录成 GIF。

**Q：目标分数可以中途改吗？**
直接告诉 AI「我想改成 7.0」就可以，它会立即切换。

---

## License

MIT — 可自由使用、修改、分发。

---

*SnapEnglish · My English, my moments.*
