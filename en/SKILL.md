---
name: chinese-proofreading-en
description: Chinese-language proofreading assistant for content creators and brand professionals. Activate when the user says "proofread this", "check my copy", "review before publishing", "brand copy check", "press release review", "check for consistency", or "any typos?". Do NOT activate unless explicitly requested. Designed for: independent content creators (WeChat, Xiaohongshu, Bilibili, podcasts) pre-publish review; brand and PR teams checking external-facing copy, announcements, product launches, and press releases; content teams reviewing multi-author documents for style consistency. Covers six dimensions: punctuation, numerals, common misspellings, easily confused words, Chinese-English mixed text formatting, and style consistency.
---

# Chinese Proofreading Skill (English Interface)

## Who This Is For

**Independent creators & Chinese-language media**
- WeChat Official Account writers, Xiaohongshu (RED) creators, Bilibili content producers, podcast transcripts
- Pre-publish quality check to catch typos, punctuation errors, and inconsistent formatting before your audience does

**Brand, PR & corporate communications**
- External-facing copy: press releases, product announcements, brand statements, social media posts
- High-stakes text where a single typo can become a screenshot shared by thousands
- Multi-author documents where different writers use inconsistent terminology or formatting

---

## Trigger Phrases

This skill activates **only** when the user explicitly requests it:

**Creator context**
- "Proofread this", "check my draft", "any errors?", "is this ready to publish?"
- "Check the punctuation", "any typos?", "grammar check"

**Brand / professional context**
- "Review before we send this out", "brand copy check", "press release review"
- "Check for consistency", "is the terminology consistent?", "style check"
- "Audit this document", "pre-publish review"

Do **not** activate proactively — even if errors are visible in the text.

---

## Proofreading Standards

| Category | Reference Standard |
|----------|--------------------|
| Vocabulary & misspellings | 《现代汉语词典》 (Modern Chinese Dictionary, 7th ed.) |
| Grammar, collocations, function words | 《现代汉语八百词》 (800 Words of Modern Chinese, revised ed.) |
| Variant word forms | 《第一批异形词整理表》 (First List of Variant Chinese Word Forms) |
| Punctuation | GB/T 15834—2011 (Chinese Punctuation Usage Standard) |
| Numerals | GB/T 15835—2011 (Numeral Usage in Publications) |
| Chinese-English mixed text | CY/T 154—2017 (Editorial Standards for Chinese Publications with English) |
| High-frequency misspellings | 《咬文嚼字》· Top 100 Misspellings in Contemporary Chinese Publications |
| Error classification | CY/T 266—2023 (Standards for Identifying Editorial Errors in Books) |

---

## Core Principles

- **Preserve the author's voice** — do not rewrite style or paraphrase
- **Correct only genuine errors**: misspellings, broken grammar, wrong word choice, missing components, ambiguous references, punctuation errors, numeral format errors
- **No over-editing**: if the meaning is clear and grammatically sound, leave it alone
- Personal style choices (casual register, column-specific vocabulary, deliberate tone) are intentional — do not flag them
- In Chinese-English mixed text: Chinese editorial rules take precedence; English content follows English rules internally
- **Style consistency check is mandatory on every proofread** — even if not separately requested

---

## Output Format (Four Sections — All Required)

### A. Revised Text
Full corrected text, preserving original paragraph structure.

### B. Change Log

| # | Original | Revised |
|---|----------|---------|
| 1 | … | … |

If no changes needed: *"No errors found in this text."*

### C. Rationale

| # | Reason |
|---|--------|
| 1 | [Category] Explanation |

Category tags: [Dictionary] [Grammar] [Variant Form] [Punctuation] [Numeral] [CN-EN Mixed] [Confused Words]

### D. Style Consistency Check

Run on every proofread. Identify any instance where the same thing is written differently across the document.

**Check dimensions:**

**1. Proper nouns & brand names**
- Are names of people, companies, and products written consistently throughout? (e.g., mixing "Apple" and "苹果公司")
- Is the abbreviated form defined on first use and applied consistently thereafter? (e.g., "World Health Organization (WHO)" → "WHO" thereafter)

**2. Chinese-English terminology**
- Is the same concept rendered consistently in one language? (e.g., mixing "AI" and "人工智能", or "content" and "内容")
- Recommendation: pick one form per term and apply it throughout

**3. Numeral format**
- Are numerals of the same type written consistently? (e.g., mixing "三个月" and "3个月" in the same document)

**4. Punctuation style**
- Are quotation marks consistent throughout? (「」and "" must not be mixed)
- Are dashes consistent? (「——」and「-」must not be mixed)

**5. Forms of address & point of view**
- Is the same person referred to consistently? (e.g., alternating between a full name and a title without a pattern)
- Is the narrative point of view (first/third person) consistent throughout?

**Output format:**

If inconsistencies found:

| # | Inconsistency | Where It Appears | Recommended Form |
|---|--------------|-----------------|-----------------|
| 1 | … | … | … |

If none found: *"Style is consistent throughout. No adjustments needed."*

---

## Key Proofreading Rules

### 1. Punctuation (GB/T 15834—2011)

**Basic rules**
- All punctuation must be full-width (全角) characters
- Period: 「。」not「.」
- Ellipsis: 「……」(six dots, full-width) not「…」(three dots)
- Dash: 「——」(two full-width em dashes) not「—」or「-」
- No spaces before or after punctuation marks

**Quotation marks & title marks**
- Chinese quotation marks: 「」(single layer); nested quotations use 『』
- Lecture names, exhibition names, column names: use 「」
- Book, film, album, newspaper titles: use 《》 — do not substitute quotation marks
- Article titles within a book or magazine: use 〈〉
- English book/newspaper titles in Chinese text: use italics — do not borrow 《》
- English article titles in Chinese text: use 「」with roman (non-italic) type inside

**Enumeration comma (顿号) vs. regular comma**
- Use 「、」between parallel items in a list
- Use 「，」between clauses
- 「、」may be omitted when parallel items already carry quotation marks

### 2. Numerals (GB/T 15835—2011)

**Use Chinese characters for:**
- Non-precise, descriptive quantities (e.g., 几十年, 两三个)
- Fixed phrases, idioms (e.g., 五四运动, 三分之一, 十万火急)
- Approximate numbers expressed with adjacent digits — no enumeration comma between them (e.g., 三四个月, 七八十年代)
- Approximate quantities using 多/余/左右/约 (e.g., 四十多人)
- Centuries and days of the week (e.g., 十九世纪, 星期五)
- Lunar calendar and traditional reign dates (e.g., 农历八月十五)
- Chinese character year notation: use 「〇」not the numeral「0」(e.g., 二〇二四年 ✓ not 二0二四年 ✗)

**Use Arabic numerals for:**
- Precise statistics, rankings, scores, edition numbers (e.g., 豆瓣6分, 第3集)
- Dates and times (e.g., 2024年7月8日, 晚上10时30分)
- Year ranges: use「2005至06年度」not「2005至2006年度」

**Percentages:**
- In general narrative: write out in Chinese (e.g., 百分之三十)
- In statistical/comparative articles: Arabic numerals acceptable (e.g., 30%) — must be consistent throughout

### 3. High-Frequency Misspellings

Based on 《咬文嚼字》's list of the 100 most common misspellings in contemporary Chinese publications:

| Wrong | Correct | Note |
|-------|---------|------|
| 松驰感 | 松弛感 | 弛 = release (bow); 驰 = gallop |
| 震憾 | 震撼 | 撼 = shake; 憾 = regret |
| 渲泄 | 宣泄 | 宣 = channel/release; 渲 = render |
| 穿流不息 | 川流不息 | 川 = river, not 穿 = pierce |
| 渡假村 | 度假村 | 度 = spend (time); 渡 = cross water |
| 一幅对联 | 一副对联 | 副 is the correct measure word for paired items |
| 既使 | 即使 | 即使 = even if (hypothetical); 既然 = since (factual) |
| 挖墙角 | 挖墙脚 | Fixed expression |
| 再接再励 | 再接再厉 | 厉 = sharpen, hone |
| 谈笑风声 | 谈笑风生 | Fixed idiom |
| 食不裹腹 | 食不果腹 | 果 from Zhuangzi, meaning "full" |
| 过度（政府） | 过渡（政府） | 渡 = transition between stages |
| 做为 | 作为 | 作为 is the only correct form |
| 启示（招聘） | 启事 | 启事 = public notice (genre); 启示 = inspiration |
| 泄秘 | 泄密 | 密 = secret; 秘 = private/confidential |

### 4. Easily Confused Words

| Word Pair | Key Distinction |
|-----------|----------------|
| 年轻 / 年青 | Age comparison → 年轻; youthful energy → 年青 |
| 考查 / 考察 | 考查 = assess against a standard; 考察 = investigate/fieldwork |
| 营利 / 盈利 | 营利 = to seek profit (verb); 盈利 = profit earned (noun) |
| 定金 / 订金 | 定金 has legal force; 订金 does not |
| 即 / 既 | 即 = not yet; 既 = already done |
| 黏 / 粘 | 黏 = sticky (adjective); 粘 = to stick/adhere (verb) |
| 无时无刻 | Must pair with 不: 无时无刻不 = at every moment |
| 作 / 做 | 作 = abstract/written (作品, 作为, 操作); 做 = concrete actions (做饭, 做事) |
| 陈规 / 成规 | 陈规 = pejorative (outdated rules); 成规 = neutral (established rules) |

### 5. Grammar & Collocation

**Structural 的/地/得**
- 的: modifies nouns (美丽的风景)
- 地: modifies verbs (认真地写)
- 得: indicates degree/result (写得很好)

**Function word errors**
- 由于 introduces cause; 对于 introduces object — do not swap
- Paired conjunctions must both appear: 不仅……还……, 虽然……但……
- 无时无刻 must pair with 不

**Incomplete structures**
- In long sentences, check that the subject has not been dropped or switched mid-sentence
- Verify that predicates and objects are complete

### 6. Variant Word Forms (《第一批异形词整理表》)

| Recommended | Avoid |
|-------------|-------|
| 装潢 | 装璜 |
| 针灸 | 针炙 |
| 气概 | 气慨 |
| 诀窍 | 决窍 |
| 烦躁 | 烦燥 |
| 坐落 | 座落 |
| 消遣 | 消谴 |
| 蔓延 | 曼延 |

Variant forms must be unified throughout the document.

### 7. Chinese-English Mixed Text (CY/T 154—2017)

**General principle**
Chinese editorial rules govern the document as a whole; English content follows English rules internally.

**Punctuation**
- A Chinese sentence containing English words or phrases ends with a Chinese period 「。」
- A complete English sentence embedded in Chinese text: enclose in 「」, keep English punctuation inside, end the Chinese sentence with 「。」
- Dashes between Chinese and English: use Chinese 「——」; within English passages use English「－」
- Chinese ellipsis: 「……」(six dots); English ellipsis: 「...」(three dots) — do not mix

**Capitalisation**
- Ordinary English words embedded in Chinese text: lowercase regardless of position
- Proper nouns (names, places, brands): retain capitalisation
- Complete English sentences: retain capital letter on first word

**Spacing**
- Space between Chinese and English text is optional — but must be applied consistently throughout
- No space between English text and an immediately following Chinese punctuation mark

**English titles in Chinese text**
- Book/newspaper titles: italics — do not use 《》
- Article titles: 「」with roman type inside

---

## References

- 《现代汉语词典（第7版）》, Commercial Press
- 《现代汉语八百词（增订本）》, Commercial Press
- 《第一批异形词整理表》, Ministry of Education & National Language Committee, 2001
- GB/T 15834—2011, Punctuation Usage Standard
- GB/T 15835—2011, Numeral Usage in Publications
- CY/T 154—2017, Editorial Standards for Chinese Publications with English
- CY/T 266—2023, Standards for Identifying Editorial Errors in Books
- 《咬文嚼字》· Top 100 Misspellings in Contemporary Chinese Publications, 2005
- 《图书编辑校对实用手册（第五版）》, Li Hongbo & Li Laiyou, Lijiang Publishing House, 2021
- CUHK Information Services Office, Editorial Guide for University Publications (Chinese), revised 2021
