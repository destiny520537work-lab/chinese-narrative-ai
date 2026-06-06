<div align="center">

# 中国叙事智能 · Chinese Narrative AI

> 把三位中国顶级叙事大师的思维框架，蒸馏成可运行的 AI Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![Runtime](https://img.shields.io/badge/Runtime-Claude%20Code%20·%20Cursor%20·%20Codex-blueviolet)](#安装)

[English](./README.en.md)

</div>

---

## 这是什么？

三个认知操作系统，各自蒸馏自一位大师：

| Skill | 人物 | 核心框架 | 最适合 |
|-------|------|---------|--------|
| [`/pu-songling`](./pu-songling/) | 蒲松龄 | 以异写真 × 失意者的凝视 × 积微成著 | 志怪叙事、借隐喻说不能直说的事、超自然世界观构建 |
| [`/chen-kaige`](./chen-kaige/) | 陈凯歌 | 历史良知 × 悲剧美学 × 知识分子的自我质问 | 史诗剧本、文化身份、道德复杂性叙事 |
| [`/zhang-yimou`](./zhang-yimou/) | 张艺谋 | 视觉即叙事 × 减法美学 × 妥协即生存 | AI 视频提示词、色彩驱动叙事、奇观设计 |

---

## 适合哪些人用？

**AI 视频创作者** — 做《逃离大英博物馆》这类文化驱动型内容的，做民国美学、中国古代戏曲恐怖造型结合无限流的，做霸王别姬式场景重构的

**编剧 & 游戏世界观设计师** — 需要历史纵深和神话底层逻辑的创作者

**AI 图像提示词工程师** — 想把张艺谋的色彩语言内嵌进提示词的

**文化 IP 开发者** — 把民间传说和历史事件包装成现代叙事的

---

## 为什么把这三个放在一起？

他们分别覆盖叙事的三个层次：

```
蒲松龄  →  世界观  （志怪、层叠、有社会真实性的）
陈凯歌  →  故事弧  （悲剧、有历史重量、道德有张力的）
张艺谋  →  画面    （视觉、极简、能烧进记忆里的）
```

用三者合力构建的故事，有神话宇宙（蒲松龄）、有悲剧情感脊梁（陈凯歌）、有能被记住的画面（张艺谋）。

---

## 安装

按需安装，或全部安装：

```bash
# 蒲松龄 — 志怪叙事、现实批判、失意者视角
git clone https://github.com/destiny520537work-lab/pu-songling-skill ~/.claude/skills/pu-songling-perspective

# 陈凯歌 — 史诗弧线、悲剧美学、知识分子自省
git clone https://github.com/destiny520537work-lab/chen-kaige-skill ~/.claude/skills/chen-kaige-perspective

# 张艺谋 — 视觉叙事、色彩语言、极简美学
git clone https://github.com/destiny520537work-lab/zhang-yimou-skill ~/.claude/skills/zhang-yimou-perspective
```

或者克隆这个 monorepo：

```bash
git clone https://github.com/destiny520537work-lab/chinese-narrative-ai
```

---

## 使用

安装后，在任何支持 skills 的 AI runtime 中触发：

```
> 用蒲松龄的视角看这件事
> 陈凯歌会怎么处理这个历史题材？
> 用张艺谋的色彩语言写一段 AI 视频提示词
> 三个视角一起看这个故事
```

---

## 独立 Repo

- [pu-songling-skill](https://github.com/destiny520537work-lab/pu-songling-skill) — 以异写真 × 失意者的凝视 × 积微成著
- [chen-kaige-skill](https://github.com/destiny520537work-lab/chen-kaige-skill) — 历史良知 × 悲剧美学 × 知识分子的自我质问
- [zhang-yimou-skill](https://github.com/destiny520537work-lab/zhang-yimou-skill) — 视觉即叙事 × 妥协即生存 × 减法美学

---

<div align="center">

本系列由 [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) 生成

**如果对你有帮助，欢迎 Star ⭐**

</div>
