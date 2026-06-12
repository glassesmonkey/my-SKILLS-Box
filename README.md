<div align="center">

# my-SKILLS-Box

**一个用来收藏、整理和维护个人 AI Skills 的工具箱仓库。**

[![Skill Box](https://img.shields.io/badge/Skill_Box-curated-black?style=for-the-badge)](#skill-index)
[![Maintained by glassesmonkey](https://img.shields.io/badge/Maintained_by-glassesmonkey-2563eb?style=for-the-badge)](https://github.com/glassesmonkey)

</div>

---

## Why This Repo

这个仓库用来集中整理我自己写过、维护过或常用的 skill 地址。

它的目标很简单：

- 找 skill 时不用到处翻链接。
- 每个 skill 都有一句话说明，降低理解成本。
- 后续新增 skill 时，有固定格式可以直接补充。

---

## Skill Index

| Skill | 适合解决什么问题 | Repository |
| --- | --- | --- |
| `seo-code-diagnostic` | 网站 SEO、技术 SEO、AdSense 审核相关的代码诊断 | [glassesmonkey/seo-code-diagnostic](https://github.com/glassesmonkey/seo-code-diagnostic) |
| `ga4-gsc-growth-analysis` | 基于 GA4 / GSC 数据做增长分析、流量诊断和优化建议 | [Alex-giao/ga4-gsc-growth-analysis](https://github.com/Alex-giao/ga4-gsc-growth-analysis) |
| `new-keyword-opportunity-evaluator` | 高召回评估新发现/上升趋势关键词的早期 SEO 机会 | [Alex-giao/new-keyword-opportunity-evaluator](https://github.com/Alex-giao/new-keyword-opportunity-evaluator) |

---

## Skill Cards

### `seo-code-diagnostic`

> 面向网站项目的 SEO 代码诊断 skill。

**适合场景**

- 检查页面标题、描述、canonical、robots、sitemap 等基础 SEO 配置。
- 排查结构化数据、图片 SEO、内链和页面可索引性问题。
- 辅助判断网站是否存在影响 AdSense 审核的低价值内容或技术问题。

**地址**

[glassesmonkey/seo-code-diagnostic](https://github.com/glassesmonkey/seo-code-diagnostic)

---

### `ga4-gsc-growth-analysis`

> 面向 GA4 和 Google Search Console 数据的增长分析 skill。

**适合场景**

- 分析自然搜索流量变化。
- 结合 GA4 / GSC 数据定位页面、关键词和转化机会。
- 生成更适合增长复盘和 SEO 优化的分析结论。

**地址**

[Alex-giao/ga4-gsc-growth-analysis](https://github.com/Alex-giao/ga4-gsc-growth-analysis)

---

### `new-keyword-opportunity-evaluator`

> 面向新增关键词、上升趋势关键词和 Cloudflare D1 候选词的机会评估 Hermes skill。

**适合场景**

- 快速筛选新发现或正在上升的关键词机会。
- 判断关键词是否适合做工具页、可玩页面、数据库、模板、指南或对比类 MVP。
- 做 24-72 小时 SEO / site experiment 的早期机会评估。

**注意边界**

它更适合做高召回的机会初筛，不适合作为最终 SERP 竞争难度判断。

**地址**

[Alex-giao/new-keyword-opportunity-evaluator](https://github.com/Alex-giao/new-keyword-opportunity-evaluator)

---

## Add A New Skill

新增 skill 时，建议保持这个格式：

```markdown
| `skill-name` | 一句话说清它解决什么问题 | [owner/repo](https://github.com/owner/repo) |
```

如果需要更详细的说明，可以继续在 `Skill Cards` 里补充：

```markdown
### `skill-name`

> 一句话说明这个 skill 的核心用途。

**适合场景**

- 场景 1
- 场景 2
- 场景 3

**地址**

[owner/repo](https://github.com/owner/repo)
```

---

## Maintenance Notes

- 新增 skill 时，优先补充到 `Skill Index`。
- 如果某个 skill 已经不维护，建议标注状态，而不是直接删除。
- 描述要写“它能帮我解决什么问题”，不要只写技术名词。
