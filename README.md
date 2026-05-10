# When2Buy Markets — Growth Assets
# When2Buy Markets — 增长资产包

This repository contains all growth-related content assets for **When2Buy Markets** (when2buy.ai), a quant-reviewed daily and weekly briefing service for US stock investors.
本仓库包含 When2Buy Markets（when2buy.ai）全套增长内容资产——这是一个由量化团队审核的美股每日/每周事件简报服务。

---

## 📦 文件清单 / What's Inside

| 文件名 | 说明 / Description |
|--------|-------------------|
| `when2buy_blog_post.md` | SEO 优化博文（英文，Iris 文风）|
| `when2buy_x_thread.md` | X/Twitter 推文串 — 15条，可单独截图转发 |
| `when2buy_xiaohongshu.md` | 小红书笔记 — 5图格式，含标题公式 |
| `when2buy_linkedin_carousel.md` | LinkedIn 轮播图 — 10页，B2B格式 |
| `when2buy_devto.md` | dev.to 二发版（发布前需等待7天以上）|
| `when2buy_ph_launch_prep.md` | Product Hunt 发布剧本 — 14天时间线 + maker comment |
| `when2buy_llms.txt` | GEO工具：供 AI 爬虫索引的 llms.txt |
| `when2buy_faq_schema.html` | GEO工具：博客页 FAQ JSON-LD 结构化数据 |
| `when2buy_citable_stats.md` | GEO工具：可引用数据块，直接插入博文 |

---

## 🚀 快速上手 / Quick Start

### 发布博文 / Publishing the Blog Post
1. 将 `when2buy_blog_post.md` 内容复制到你的 Jekyll 博客
2. 将 `when2buy_faq_schema.html` 注入到文章页的 `<head>` 中
3. 在 H1 正下方插入 `when2buy_citable_stats.md` 数据块
4. 按 frontmatter 设置 canonical URL 和 hreflang 标签

### 社媒分发节奏 / Social Media Cadence
| 平台 | 对应文件 | 建议发布日 |
|------|----------|-----------|
| X/Twitter | `when2buy_x_thread.md` | 第一天，周一 |
| 小红书 | `when2buy_xiaohongshu.md` | 第二天，周三 |
| LinkedIn | `when2buy_linkedin_carousel.md` | 第三天，周五 |
| dev.to | `when2buy_devto.md` | 最后（需等7天以上再发）|

### Product Hunt 发布 / PH Launch
按 `when2buy_ph_launch_prep.md` 的 14 天清单执行，关键节点：
- **T-14**：准备物料、联系 hunter
- **T-7**：在 Reddit 和社交平台预热（不贴 PH 链接）
- **T-1**：终检，准备第一条 comment
- **T-0**：00:01 PST hunter 发帖，你 00:15 发 first comment

### GEO 配置 / GEO Setup
1. 将 `when2buy_llms.txt` 放到 `https://when2buy.ai/llms.txt`（必须返回 HTTP 200）
2. 在每篇博文页的 `<head>` 加入 `when2buy_faq_schema.html`
3. 在每篇博文前 1000 字内插入 `when2buy_citable_stats.md`

---

## 📌 产品简介 / About the Product

**When2Buy Markets** 为散户投资者提供量化团队审核过的美股事件信号。

- 🔇 噪音过滤率 87%（对比普通财经新闻推送）
- 🎯 信号预测准确率 78%（基于 3000+ 历史事件回测）
- 💼 仅推送与你的持仓/自选股相关的 события
- 💰 $19/月 — 免费试用 7 天

→ [when2buy.ai](https://when2buy.ai)
