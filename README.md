<div align="center">

# 🎬 ad-creative

## 3–5 个角度 × 每角度 5 条变体，一次出满创意池
## 3–5 angles × 5 variants each, one validated ad copy pool

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

面向任意付费广告平台（Google Ads RSA、Meta、LinkedIn、TikTok、Twitter/X）规模化生成、迭代与扩展广告创意：标题、描述、正文或整体广告变体。输入是产品/受众/平台上下文，或已有广告加投放表现数据（CSV、粘贴文本、API 返回）；输出是按角度组织、通过各平台字数限制校验的变体池，有投放数据时额外输出一份 iteration 报告。先用一次提问收齐九个结构化字段，字段没答齐不推进。

### ✨ 能做什么

- 一次提问收齐九个字段：平台、格式、模式、产品与 offer、受众认知阶段、角度数量、每角度变体数、品牌调性/禁用词、排序指标
- 默认 3–5 个角度，每个角度默认 5 条 headlines / descriptions 起
- 输出按角度组织的创意池（如痛点、场景、对比等 angle），并按各平台字数上限逐条校验
- 有投放数据时出 iteration 报告：按 CTR／转化／ROAS 排 winner 再迭代
- 先读取 .agents/product-marketing-context.md 或用户给的投放 CSV，命中就跳过多余提问
- 交付物直接可用于创意 A/B 测试与批量铺量

### 📦 包含的技能

- `ad-creative` —— 见 [`ad-creative/SKILL.md`](ad-creative/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/ad-creative.git
cp -r ad-creative/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Scales, iterates and expands paid-ad creative for any platform (Google Ads RSA, Meta, LinkedIn, TikTok, Twitter/X) — headlines, descriptions, primary text or full ad variants. Input is product/audience/platform context, or existing ads plus performance data (CSV, pasted text, API output); output is a variant pool organised by angle and validated against each platform's character limits, plus an iteration report when performance data exists. One question collects all nine structured fields up front and the run does not proceed until they are answered. With performance data it ranks winners by CTR, conversions or ROAS before iterating.

### ✨ What it does

- One question collects all nine fields: platform, format, mode, product and offer, audience awareness stage, angle count, variants per angle, brand tone/banned words, ranking metric
- Defaults to 3–5 angles with 5 headlines/descriptions per angle
- Outputs a variant pool organised by angle (pain point, scenario, comparison and more), each line checked against platform character limits
- With performance data it writes an iteration report and ranks winners by CTR, conversions or ROAS before iterating
- Reads .agents/product-marketing-context.md or your performance CSV first and skips redundant questions on a hit
- Deliverables drop straight into creative A/B tests and bulk campaigns

### 📦 Skills included

- `ad-creative` — [`ad-creative/SKILL.md`](ad-creative/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/ad-creative.git
cp -r ad-creative/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
