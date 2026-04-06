[中文](./README.zh-CN.md) | English

# Chinese Proofreading Skill for Claude

A Claude skill that catches the typos, punctuation errors, and inconsistencies your eyes skip over — before your audience sees them.

Built for Chinese-language content creators and brand professionals who publish without an editor.

---

## The problem

You wrote the piece. You read it three times. You still missed the typo in paragraph two.

That's not carelessness — it's how the human brain works. We auto-correct familiar text. Professional editors exist precisely because writers cannot reliably proofread their own work.

Most Chinese-language creators and brand teams don't have one.

---

## What this skill does

Point it at any Chinese text. It runs six checks and returns four outputs:

**① Revised text** — the corrected version, structure unchanged, voice preserved

**② Change log** — every edit listed, nothing hidden

**③ Rationale** — the exact rule behind each change (punctuation standard, numeral format, high-frequency misspelling list, etc.)

**④ Style consistency audit** — scans the full document for the same thing written two different ways: brand names, Chinese/English term switching, numeral formats, quotation mark style, forms of address

---

## Who it's for

**Content creators** — WeChat Official Account writers, Xiaohongshu creators, Bilibili producers, podcast transcript editors. The last quality gate before you hit publish, when you're a one-person operation.

**Brand and PR teams** — press releases, product announcements, brand statements, social copy. One misspelling on an official channel becomes a screenshot. The style consistency audit is especially useful when multiple writers contribute to the same document.

---

## What it checks

| Dimension | Standard |
|-----------|----------|
| Punctuation | GB/T 15834—2011 |
| Numerals | GB/T 15835—2011 |
| High-frequency misspellings | 《咬文嚼字》Top 100 (松弛感 not 松驰感, 震撼 not 震憾, 宣泄 not 渲泄…) |
| Confused word pairs | 20+ pairs: 营利/盈利, 定金/订金, 作/做, 即/既… |
| Chinese-English mixed text | CY/T 154—2017 |
| Style consistency | Brand names, terminology language, numeral format, punctuation style, forms of address |

The skill does not rewrite. It corrects errors and flags inconsistencies — your voice stays yours.

---

## How to activate

Say any of the following:

> "Proofread this" · "Check my copy" · "Any typos?" · "Is this ready to publish?" · "Brand copy check" · "Press release review" · "Check for consistency"

The skill does not activate automatically. It only runs when you ask.

---

## Installation

### Claude.ai (Projects)

1. Open [claude.ai](https://claude.ai) and go to your Project
2. Click **Project Settings** → **Skills** → **Upload Skill**
3. Upload `en/SKILL.md`
4. Done — say "proofread this" to activate

### File structure

```
chinese-proofreading-skill/
├── README.md          ← this file (English)
├── README.zh-CN.md    ← 中文版
├── en/
│   └── SKILL.md       ← English-interface skill
└── zh/
    └── SKILL.md       ← 中文界面 skill
```

---

## Standards referenced

- GB/T 15834—2011 · GB/T 15835—2011 · CY/T 154—2017 · CY/T 266—2023
- 《现代汉语词典（第7版）》· 《现代汉语八百词（增订本）》
- 《第一批异形词整理表》
- 《咬文嚼字》· 当代汉语出版物中最常见的100个别字
- 《图书编辑校对实用手册（第五版）》
- CUHK Editorial Guide for University Publications (Chinese), 2021

---

## About

Built by **[Vinson Liang](https://www.linkedin.com/in/yingchenliang/)**

MSc Digital Transformation & Technology Innovation, City University of Hong Kong · 4 years internet industry · Chinese-language content creator writing about AI, productivity, and health

*Developed from a real publishing workflow. Not a generic tool — a production-ready quality check for Chinese-language content.*

---

MIT License
