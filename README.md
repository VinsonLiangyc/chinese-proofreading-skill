[English](README.md) | [中文](README.zh-CN.md)

# Chinese Proofreading Skill · for Claude

You know the feeling — you finish a draft, painstakingly check it n times, hit publish, and then a reader leaves a comment: "There's a typo right here."

It's not carelessness. It's how our brains work — we auto-fill what we expect to see in our own writing. The more we read it, the more flawless it looks, even the parts that are wrong. Eventually, we start believing the mistakes are correct too. After all, we've been staring at the same block of text through round after round of revisions.

Publishing houses solve this with a dedicated proofreading editor. But maybe you're a solo content creator, or maybe you're a copywriter at a company — either way, you don't have a professional proofreader working alongside you.

As a content creator myself, neither did I. 

So I built this Skill — for myself, and for everyone in the same boat.

---

## What it actually does

Paste your Chinese text and say "帮我校对" (proofread this). It runs six checks and returns four things:

**Revised text** — the corrected version, same structure, same voice

**Change log** — every edit listed out, nothing changed in secret

**Reasoning** — why each change was made, citing the specific standard

**Consistency audit** — scans the full text for inconsistencies: did you write "AI" in the first half and "人工智能" in the second? 「」 up top and "" down below?

---

## Six checks, grounded in national standards

| Check | Based on |
| --- | --- |
| Punctuation | GB/T 15834—2011 |
| Number formatting | GB/T 15835—2011 |
| Common misused characters | *Yǎo Wén Jiáo Zì* annual top-100 list (松弛≠松驰, 震撼≠震憾, 宣泄≠渲泄) |
| Confused word pairs | 20+ sets: 营利/盈利, 定金/订金, 作/做, 即/既… |
| Chinese-English mixed usage | CY/T 154—2017 |
| Style consistency | Brand names, terminology, number formats, quotation marks, person reference — unified across the full text |

It only corrects errors and flags inconsistencies. It won't rewrite your article. It won't "improve" your tone. Your voice stays yours.

---

## Who this is for

**Solo content creators.** WeChat public account authors, Xiaohongshu creators, podcast transcript editors, Bilibili columnists — you write and publish with no one to review it first. This Skill is your last checkpoint before hitting send.

**Brand and PR teams.** Press releases, product launch copy, corporate statements. One typo on an official channel gets screenshotted, shared, and remembered. The consistency audit is especially useful for multi-person documents — five people wrote different sections, the formatting drifted, this catches it.

---

## How to trigger

Say any of these to Claude:

> "帮我校对" · "校对一下" · "有没有错别字" · "发布前检查一下" · "对外文案校对" · "新闻稿校对"

It won't activate unless you ask. It's not going to pop up and correct you when you don't want it.

---

## Installation

1. Open [claude.ai](https://claude.ai), go to your Project
2. **Project Settings** → **Skills** → **Upload Skill**
3. Upload `zh/SKILL.md` (Chinese interface) or `en/SKILL.md` (English interface)
4. Say "帮我校对" — done

```
chinese-proofreading-skill/
├── README.md            ← This file
├── README.zh-CN.md      ← 中文版
├── zh/
│   └── SKILL.md         ← Chinese interface
└── en/
    └── SKILL.md         ← English interface
```

---

## Standards referenced

GB/T 15834—2011 · GB/T 15835—2011 · CY/T 154—2017 · CY/T 266—2023 · *Xiàndài Hànyǔ Cídiǎn* (7th ed.) · *Xiàndài Hànyǔ Bābǎi Cí* (revised ed.) · First Standardized List of Variant Chinese Words · *Yǎo Wén Jiáo Zì* top-100 misused characters · *Practical Handbook for Book Editing and Proofreading* (5th ed.) · CUHK *Chinese Editorial Guidelines for University Publications* (2021 rev.)

---

## About

by **[Vinson Liang](https://www.linkedin.com/in/yingchenliang/)**

I write content. I've published posts with typos I didn't catch. So I built this — for myself, and for everyone dealing with the same problem.

MIT License
