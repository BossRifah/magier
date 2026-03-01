# Research SOP — Standard Operating Procedure

## Purpose

This SOP defines how Magier conducts market research and competitive intelligence. Follow this process for every research task.

---

## Research Hierarchy

Use sources in this priority order:

1. **Perplexity MCP** (if connected) — Real-time, sourced web research. Always preferred.
2. **WebSearch tool** — Fallback when Perplexity is not available.
3. **Provided documents** — Any files the user shares (audits, reports, data).
4. **Claude's knowledge** — Use only as background context, never as primary research data.

Always cite sources for competitive claims or market data.

---

## Competitive Intelligence Framework

### Step 1: Identify Competitors

**Primary competitors** (design subscription services):
- Design Pickle
- Penji
- Superside
- ManyPixels
- Kimp
- Designjoy (Studio)

**Secondary competitors** (adjacent alternatives):
- 99designs / Dribbble (freelance marketplace)
- Fiverr / Upwork (gig platforms)
- In-house design team
- Local design agencies

**Research prompt to use:**
> "What are the top-rated graphic design subscription services in [year]? Compare pricing, turnaround time, Webflow capabilities, and target market."

### Step 2: Competitive Analysis Template

For each competitor, document:

| Attribute | Competitor Name |
|-----------|----------------|
| Pricing | |
| Turnaround | |
| Services offered | |
| Webflow capability | |
| Target market | |
| Trustpilot / G2 rating | |
| Key messaging / positioning | |
| Strengths vs. Magier | |
| Weaknesses vs. Magier | |

### Step 3: SEO & Search Opportunity Research

Always research:
- What keywords competitors rank for that Magier doesn't
- What "alternatives" and "vs." queries exist (e.g., "magier vs design pickle")
- What questions people ask on forums (Reddit, Quora, Product Hunt) about design subscriptions
- Current Google search volume for key terms

---

## Market Research Framework

### Industry Context
Always look for:
- Market size for graphic design services / subscription services
- Growth trends (is subscription-based design growing?)
- Key industry shifts (AI design tools, budget changes)
- Regional data (European market, German startup ecosystem)

### Customer Research
Always look for:
- Reviews and complaints on Trustpilot, G2, Reddit about design subscription services
- What customers praise vs. complain about with competitors
- Common objections to design subscriptions
- Emerging pain points in 2026

**Research prompt to use:**
> "What do customers say about design subscription services in reviews? What are the most common complaints and praise points?"

---

## Research Output Standards

All research outputs must include:

### Executive Summary (1 page)
- 3–5 key findings
- Strategic implications for Magier
- Recommended actions

### Source Documentation
- List all URLs/sources consulted
- Date of research (data becomes stale)
- Confidence level for each major claim (High / Medium / Low)

### Data Freshness
- Competitive data: Note when each data point was last verified
- Market sizing: Always note the source date
- Flag anything older than 6 months as "may be outdated"

---

## Research Prompts Library

Copy-paste these prompts when running research with Perplexity MCP:

**Competitor Pricing:**
> "What are the current prices for Design Pickle, Penji, Superside, ManyPixels, and Kimp as of [current date]? Compare their plans and what's included."

**Market Trends:**
> "What are the latest trends in the graphic design subscription market in 2026? How is AI affecting demand for human design services?"

**Customer Pain Points:**
> "What do companies commonly complain about when using design subscription services like Design Pickle or Penji? Search recent reviews and forum discussions."

**SEO Opportunities:**
> "What search terms related to 'design subscription service' or 'unlimited graphic design' have high search volume and low competition in 2026?"

**Webflow Market:**
> "What is the growth of Webflow usage in Europe among startups in 2025-2026? What percentage of startups use Webflow?"

---

## File Naming Convention

Save research outputs to:

```
campaigns/[campaign-name]/research-[topic]-[date].md

Examples:
campaigns/march-2026-launch/research-competitive-landscape-2026-03-01.md
campaigns/webflow-push/research-webflow-market-trends-2026-03-01.md
```
