# When2Buy Markets — Growth Assets

This repository contains all growth-related content assets for **When2Buy Markets** (when2buy.ai), a quant-reviewed daily and weekly briefing service for US stock investors.

## What's Inside

| File | Description |
|------|-------------|
| `when2buy_blog_post.md` | SEO-optimized English blog post (Iris writing style) |
| `when2buy_x_thread.md` | X/Twitter thread — 15 tweets, standalone shareable |
| `when2buy_xiaohongshu.md` | Xiaohongshu (Little Red Book) note — 5-slide format |
| `when2buy_linkedin_carousel.md` | LinkedIn carousel — 10 slides, B2B format |
| `when2buy_devto.md` | dev.to cross-post version (wait 7+ days before publishing) |
| `when2buy_ph_launch_prep.md` | Product Hunt launch playbook — 14-day timeline + maker comment |
| `when2buy_llms.txt` | GEO kit: llms.txt for AI crawler indexing |
| `when2buy_faq_schema.html` | GEO kit: FAQ JSON-LD schema for blog posts |
| `when2buy_citable_stats.md` | GEO kit: Citable Statistics block for blog insertion |

## Quick Start

### Publishing the Blog Post
1. Copy `when2buy_blog_post.md` content to your Jekyll blog
2. Inject `when2buy_faq_schema.html` into the `<head>` of the post page
3. Insert `when2buy_citable_stats.md` block right below the H1
4. Set canonical URL and hreflang tags per the frontmatter

### Social Media Distribution
| Platform | File | Cadence |
|----------|------|---------|
| X/Twitter | `when2buy_x_thread.md` | Publish 1st, Monday |
| Xiaohongshu | `when2buy_xiaohongshu.md` | Publish 2nd, Wednesday |
| LinkedIn | `when2buy_linkedin_carousel.md` | Publish 3rd, Friday |
| dev.to | `when2buy_devto.md` | Publish last (7+ day delay) |

### Product Hunt Launch
Follow the 14-day checklist in `when2buy_ph_launch_prep.md`. Key dates:
- **T-14**: Prepare assets, find a hunter
- **T-7**: Pre-warm on Reddit and social channels (no PH link)
- **T-1**: Final checks, prepare first comment
- **T-0**: Hunter posts at 00:01 PST, maker comment at 00:15 PST

### GEO Setup
1. Place `when2buy_llms.txt` at `https://when2buy.ai/llms.txt` (must return HTTP 200)
2. Add `when2buy_faq_schema.html` to blog post `<head>` sections
3. Insert `when2buy_citable_stats.md` into the top 1000 words of each post

## Product Summary

**When2Buy Markets** delivers quant-reviewed US stock market events to retail investors.

- 87% noise reduction vs. typical news feeds
- 78% event prediction accuracy (backtested on 3,000+ events)
- Portfolio-matched: only events relevant to YOUR holdings
- $19/month — free 7-day trial

→ [when2buy.ai](https://when2buy.ai)
