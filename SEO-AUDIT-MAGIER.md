# SEO Audit: magier.com (www.magier.com)

**Date:** February 17, 2026
**Platform:** Webflow (Webflow Premium Partner)
**Previous Domain:** magicdesign.io
**Business:** Graphic Design & Webflow Development Subscription Service (Berlin, Germany)

---

## Table of Contents

1. [Executive Summary](#executive-summary)
2. [Page-by-Page Title Tag & Meta Audit](#page-by-page-title-tag--meta-audit)
3. [Duplicate & Templated Copy Problems (with Exact Examples)](#duplicate--templated-copy-problems-with-exact-examples)
4. [Site Architecture & Internal Linking Failures](#site-architecture--internal-linking-failures)
5. [Technical SEO](#technical-seo)
6. [Off-Site SEO](#off-site-seo)
7. [Content Gaps with Specific Pages to Build](#content-gaps-with-specific-pages-to-build)
8. [Blog Audit: Specific Posts & Issues](#blog-audit-specific-posts--issues)
9. [Case Studies Audit](#case-studies-audit)
10. [Recommendations (Prioritized with Specific Actions)](#recommendations-prioritized-with-specific-actions)

---

## Executive Summary

Magier.com has ~60+ indexable pages across services, customer segments, blog, case studies, and resources. The site has strong brand positioning and excellent social proof (5 stars on Trustpilot, 96+ reviews). However, there are concrete, fixable SEO problems dragging down organic performance:

1. **At least 6 service pages use near-identical templated copy** — the phrase "Professional [X] from top graphic designers with first results in 48h, all in one subscription" appears verbatim across `/social-media-content-design`, `/social-ad-design`, `/ad-creatives`, `/product-design`, `/landing-page-design`, and `/interface-design`. Google sees this as thin/duplicate content.
2. **Two Webflow pages cannibalize each other** — `/webflow-development` ("Expert Webflow Development - magier") and `/webflow-design` ("Webflow Design and Development - magier") compete for the same queries with overlapping titles and copy.
3. **Blog posts are stuck in 2025** — titles like "The Ultimate Guide to Unlimited Graphic Design Services in 2025" and "11 Best Designjoy Alternatives in 2025" are already stale.
4. **9 case studies exist but aren't linked from service pages** — the Plancraft case study mentions a 20% conversion rate increase, but `/webflow-development` doesn't link to it.
5. **Zero competitor comparison pages** — third-party sites rank for "magier vs design pickle" and "magier alternative" while magier owns none of this traffic.
6. **Schema markup is missing or minimal** — no evidence of FAQ schema on `/pricing`, no AggregateRating schema leveraging the 96 Trustpilot reviews, no Service schema on any service page.

---

## Page-by-Page Title Tag & Meta Audit

### Homepage: `/`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `magier - Your Graphic Design & Webflow Subscription` | Brand-first. Google gives more weight to the first words of a title. The keyword "graphic design subscription" is buried after the brand name. | `Unlimited Graphic Design & Webflow Subscription \| magier` |
| **Snippet** | "creative subscription service, trusted by the world's top brands to get exceptional design faster, more reliably and at scale" | Generic — doesn't mention pricing, turnaround time, or Webflow. No CTA. | "Unlimited graphic design & Webflow development for €2,290/mo. 48h turnaround, dedicated project manager. Trusted by 100+ startups. Start free." |

### Pricing: `/pricing`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `magier Pricing: Unlimited Graphic Design & Webflow Subscription` | Actually good — keyword-rich, includes "unlimited" and "pricing". One of the better titles on the site. | Minor: move "Pricing" to the front → `Unlimited Design Subscription Pricing - €2,290/mo \| magier` |
| **Missing** | No FAQ schema | The pricing page almost certainly has an FAQ section ("Can I pause?", "How many requests?"). This is free rich-result real estate Google is not showing. | Add FAQ schema for every question on the page. |

### Design Services Hub: `/design-services`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Our Graphic Design Services - magier` | "Our" wastes title space. Doesn't mention "unlimited" or "subscription". | `Graphic Design Services - Unlimited Subscription \| magier` |
| **Content role** | Hub/index page linking to 10+ sub-service pages | If this page is just a list of links with no substantive copy, Google may treat it as a thin doorway page. | Add 300+ words of unique copy explaining the subscription model, how services work together, and why magier's approach is different. |

### Landing Page Design: `/design-services/landing-page-design`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Landing Page Designer - Unlimited Design Subscription` | Targets "landing page designer" (person) instead of "landing page design service" (what people actually search). | `Landing Page Design Service - 48h Turnaround \| magier` |
| **Copy** | "Professional Landing Page Designs from top graphic designers with first results in 48h — all your designs in one subscription." | Same template as 5 other service pages. See [Duplicate Copy section](#duplicate--templated-copy-problems-with-exact-examples). | Write unique copy: what makes magier's landing page design different? Include conversion rate stats from case studies, specific deliverables (Figma, Webflow-ready), industries served. |

### Social Media Content Design: `/design-services/social-media-content-design`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Professional Social Media Design in <48 Hours – Design Subscription` | The `<` character may render as HTML entity in SERPs. Awkward phrasing. | `Social Media Design Service - Unlimited Subscription \| magier` |
| **Copy** | "Professional Social Media Designs from top graphic designers with first results in 48h, all in one subscription." | Templated. See duplicate copy section. | Differentiate: mention specific platforms (Instagram, LinkedIn, TikTok), content types (carousels, stories, reels covers), and that templates can be made reusable. |

### Social Ad Design: `/design-services/social-ad-design`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Social Ad Designs – magier` | Far too short. Wastes ~35 characters of title space. No keywords like "service," "subscription," or "Facebook/Instagram ads." | `Social Media Ad Design Service - Facebook, Instagram, LinkedIn \| magier` |
| **Copy** | "Professional Social Ad Designs from top graphic designers with first results in 48 hours, all within one subscription." | Templated. Nearly identical to social media content design page. Google has no reason to rank both. | Unique angle: focus on conversion optimization, A/B test variations, platform-specific sizing, ad creative strategy. |

### Ad Creatives: `/design-services/ad-creatives`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Ad Creatives for your Startup – magier` | Narrow targeting ("your Startup"). Misses agencies, ecommerce, SaaS. | `Ad Creative Design Service - Unlimited Subscription \| magier` |
| **Cannibalization** | This page AND `/design-services/social-ad-design` both target ad design | Two pages competing for the same keyword cluster. | Merge into one definitive page or clearly differentiate: `/ad-creatives` = strategy + creative concepts, `/social-ad-design` = platform-specific ad production. |

### App Design: `/design-services/app-design`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `App Design for your Startup – magier` | Same "for your Startup" pattern as Ad Creatives. Limits audience. | `App Design Service - Mobile & Web App UI \| magier` |

### UI/UX Design: `/design-services/ui-ux-design`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `UI / UX Design – magier` | Extremely thin title. Doesn't mention service, subscription, or any modifier. | `UI/UX Design Service - Design Systems & User Experience \| magier` |
| **Copy** | "Individual design of user interfaces for your web or mobile app including the creation of a design system, with experts who help design a state-of-the-art user experience." | Better than the templated pages — actually mentions design systems. But still thin. | Expand with specific deliverables: wireframes, prototypes, user flows, design system components. Link to relevant case studies. |

### Web Design: `/design-services/webdesign`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Professional Custom Web Design – Unique & Responsive Websites` | Good — keyword-rich, no brand (unusual). But "Unique" is filler. | `Custom Web Design Service - Responsive Websites \| magier` |
| **URL** | `/design-services/webdesign` | "webdesign" is one word in the URL but "web design" is two words everywhere else. Minor inconsistency. | Not worth a redirect, but note for future pages. |

### Interface Design: `/design-services/interface-design`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Top Interface Design – magier` | "Top" is meaningless to Google. This page overlaps heavily with `/design-services/ui-ux-design`. | Consider merging into UI/UX page, or differentiate clearly (e.g., interface design = enterprise dashboards, admin panels). |
| **Cannibalization** | Competes with `/design-services/ui-ux-design` | Both target "interface design" and "UI design" keywords. | Merge or add canonical from one to the other. |

### Product Design: `/design-services/product-design`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Product Graphic Designs – magier` | Confusing — "Product Graphic Designs" conflates product design (UX) with graphic design for products (packaging, mockups). | `Product & Packaging Design Service \| magier` |
| **Copy** | "Eye-catching and carefully designed packaging for digital and physical products..." mixed with "Custom promotional products for your company, such as jumpers, goodies or promotional items." | This page is trying to be 3 things: product design, packaging design, and promotional merchandise design. | Pick one angle or split into separate pages. There's already a `/design-services/packaging-design` page. |

### Brand Design: `/design-services/brand-design`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Stunning Brand Design – magier` | "Stunning" is filler. Doesn't mention "branding service," "brand identity," or "logo." | `Brand Identity Design Service - Logo, Guidelines & More \| magier` |

### Packaging Design: `/design-services/packaging-design`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Top Packaging Design – magier` | Same "Top [X]" lazy pattern. | `Packaging Design Service - Product Packaging \| magier` |
| **Overlap** | Overlaps with `/design-services/product-design` which also mentions packaging | Two pages competing for "packaging design." | Consolidate packaging content here, remove it from product design page. |

### Flyer Design: `/design-services/flyer-design`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Flyer Design – magier` | Thin title. | `Flyer & Brochure Design Service \| magier` |

### Webflow Development: `/webflow-development`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Expert Webflow Development - magier` | Good. But lives at root instead of under `/design-services/`. | Keep title, fix architecture (see below). |
| **Copy** | Mentions "100+ happy clients", "Client-First methodology", and Webflow Premium Partner status. | This is the strongest service page on the site — actual differentiators, not templates. Other service pages should follow this model. | Add links to Plancraft case study (20% CR increase) and other Webflow case studies. |

### Webflow Design: `/webflow-design`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Webflow Design and Development - magier` | Directly overlaps with `/webflow-development`. What's the difference between "Webflow Design and Development" and "Expert Webflow Development"? | Either merge these pages (canonical from `/webflow-design` to `/webflow-development`) or clearly differentiate: `/webflow-design` = design in Webflow's visual editor, `/webflow-development` = custom code, CMS, integrations. |

### How It Works: `/how-it-works`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `How Does magier Work? - Design Subscription` | Acceptable. Could be stronger. | `How It Works - Unlimited Design Subscription in 3 Steps \| magier` |
| **Missing** | No FAQ schema | This page likely explains the process with Q&A-style content. Perfect candidate for FAQ rich results. | Add FAQ schema. |

### About Us: `/about-us`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Who's magier? - About Us` | Zero keyword value. "Who's magier?" means nothing to someone who hasn't heard of the brand. | `About magier - Design & Webflow Agency, Berlin \| 30+ Experts` |

### One-Time Project: `/one-time-project`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `One Time Design & Webflow Project - magier` | Targets users who don't want a subscription — important conversion page. | `One-Time Design & Webflow Projects - No Subscription Required \| magier` |
| **Linking** | Appears isolated in the site architecture | Users comparing pricing options may not discover this page. | Link from `/pricing` ("Not ready for a subscription? Try a one-time project →") and from every service page footer. |

### Startups: `/customer/startups`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Graphic Design for Startups - magier` | Good keyword targeting. | Minor: `Graphic Design & Webflow for Startups \| magier` |

### SaaS: `/customer/saas`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Best-Rated Graphic Design Services for SaaS - magier` | Good — targets SaaS vertical specifically. | Keep. Consider adding "& Webflow" to capture SaaS Webflow searches. |

### Agencies: `/customer/agencies`

| Element | Current | Problem | Fix |
|---------|---------|---------|-----|
| **Title** | `Expert White Label Graphic Design for Agencies` | Strong — targets "white label graphic design" which is a high-intent commercial query. | Good as-is. Add magier brand to end. |

---

## Duplicate & Templated Copy Problems (with Exact Examples)

This is the single biggest on-page SEO problem. At least 6 service pages open with a near-identical sentence:

### The Template

> "Professional **[Service Name]** from top graphic designers with first results in 48h, all in one subscription."

### Where It Appears (Exact Matches)

| Page | Opening Line |
|------|-------------|
| `/design-services/landing-page-design` | "Professional Landing Page Designs from top graphic designers with first results in 48h — all your designs in one subscription." |
| `/design-services/social-media-content-design` | "Professional Social Media Designs from top graphic designers with first results in 48h, all in one subscription." |
| `/design-services/social-ad-design` | "Professional Social Ad Designs from top graphic designers with first results in 48 hours, all within one subscription." |
| `/design-services/ad-creatives` | "Professional Ad Creatives from top graphic designers with first results in 48h, all in one subscription." |
| `/design-services/product-design` | "Professional Product Graphic Designs from top graphic designers with first results in 48 hours, all within one subscription." |
| `/design-services/interface-design` | "magier acts as an extended workbench to design interfaces, giving access to talented designers with extensive experience in creating user interfaces." |

### Second Repeated Block

A separate template also repeats across pages:

> "magier is a graphic design service that helps you create **[service type]** like an extended workbench, giving access to talented designers with extensive experience and guaranteeing fast turnaround times."

This appears on:
- `/design-services/social-media-content-design`
- `/design-services/social-ad-design`
- `/design-services/product-design`
- `/design-services/interface-design`

### Why This Matters

Google's Helpful Content system specifically penalizes pages that are "substantially similar to other pages." When 6 pages share the same opening paragraph and the same mid-page boilerplate, Google consolidates them or suppresses the duplicates. This means only 1-2 of your 10+ service pages are likely getting meaningful organic traffic — the rest are dead weight.

### The Fix

Each service page needs:
1. **A unique opening paragraph** that addresses the specific pain point for that service (e.g., "Your LinkedIn ads aren't converting because the creative looks like stock photography" — not "Professional ad designs from top designers")
2. **Specific deliverables** unique to that service (e.g., social media: carousel templates, story templates, profile graphics, content calendars)
3. **A relevant case study link** (e.g., social media page → Social Heaven case study)
4. **Unique FAQ content** addressing questions specific to that service type
5. **At minimum 400 words of unique copy** per page

---

## Site Architecture & Internal Linking Failures

### Problem 1: Orphaned Root-Level Pages

```
/webflow-development    ← Lives at root, not under /design-services/
/webflow-design         ← Lives at root, not under /design-services/
/one-time-project       ← Lives at root, no clear parent
```

These pages sit outside the `/design-services/` hierarchy. If the main navigation doesn't prominently link to them AND `/design-services` doesn't list them, they're semi-orphaned — getting less internal PageRank than the nested service pages.

### Problem 2: Case Studies Not Connected to Service Pages

Magier has **9 published case studies** — this is a significant asset that's being wasted:

| Case Study | Key Result | Should Link FROM → |
|-----------|------------|-------------------|
| [Plancraft](https://www.magier.com/case-studies/vc-backed-startup-plancraft) | **20% increase in conversion rate**, paid for itself in 30 days | `/webflow-development`, `/webflow-design`, `/customer/saas` |
| [Growdash](https://www.magier.com/case-studies/how-growdash-doubled-their-leads-and-built-a-recognizable-brand-with-magier) | **Doubled their leads**, complete rebrand | `/design-services/brand-design`, `/customer/startups` |
| [Social Heaven](https://www.magier.com/case-studies/social-heaven-branding-web-design) | **Doubled leads** after website migration | `/webflow-development`, `/design-services/webdesign` |
| [NextRep](https://www.magier.com/case-studies/how-nextrep-launched-with-a-website-that-converts-from-day-one) | **60 active users in 4 weeks** post-launch | `/design-services/landing-page-design`, `/customer/startups` |
| [ParoSwiss](https://www.magier.com/case-studies/ecommerce-design-paroswiss) | Global brand modernization across 30+ countries | `/design-services/brand-design`, `/design-services/packaging-design` |
| [Jupus](https://www.magier.com/case-studies/jupus-scales-to-500-law-firms-and-builds-a-standout-legal-tech-brand-with-magier) | **Scaled to 500+ law firms** | `/customer/saas`, `/design-services/ad-creatives` |
| [Next Level E-Commerce](https://www.magier.com/case-studies/from-wordpress-to-webflow-next-level-e-commerces-transformation) | WordPress → Webflow migration | `/webflow-development` |
| [Weglot](https://www.magier.com/case-studies/how-weglot-built-a-scalable-sub-brand-with-magier) | Scalable sub-brand for SaaS company | `/design-services/brand-design`, `/customer/saas` |
| [Pouncer AI](https://www.magier.com/case-studies/ai-freelancer-startup-pouncer-ai) | Product design + website redo + marketing design | `/design-services/app-design`, `/design-services/ui-ux-design` |

**Current state:** These case studies appear to live only on `/case-studies` and are not contextually linked from the service pages they're relevant to. This means:
- Service pages lack social proof (no "See how Plancraft increased conversions 20%")
- Case study pages get less internal link equity
- Users on service pages don't see real results

### Problem 3: Blog → Service Page Links Are Weak

Specific blog posts that should link to specific service pages but likely don't (or bury the link):

| Blog Post | Should Link To |
|-----------|---------------|
| [Find the Best Webflow Design Agency in 2026](https://www.magier.com/blog/best-webflow-design-agency) | `/webflow-development` and `/webflow-design` with strong anchor text |
| [Unlimited Graphic Design Services: Pros, Cons & Options](https://www.magier.com/blog/unlimited-graphic-design-services-pros-cons) | `/pricing` and `/design-services` |
| [Outsource Graphic Design](https://www.magier.com/blog/outsource-graphic-design) | `/design-services` and `/customer/agencies` |
| [Subscription Based Design Services](https://www.magier.com/blog/subscription-based-design-services) | `/pricing` and `/how-it-works` |
| [Graphic Design Packages](https://www.magier.com/blog/graphic-design-packages) | `/pricing` |

### Problem 4: Cannibalization Map

These page pairs are competing with each other in Google:

| Page A | Page B | Overlapping Keyword Cluster |
|--------|--------|---------------------------|
| `/webflow-development` | `/webflow-design` | "webflow development service", "webflow agency" |
| `/design-services/ui-ux-design` | `/design-services/interface-design` | "UI design service", "interface design" |
| `/design-services/ad-creatives` | `/design-services/social-ad-design` | "ad design service", "social media ad design" |
| `/design-services/product-design` | `/design-services/packaging-design` | "product packaging design" |

---

## Technical SEO

### Crawlability

| Issue | Status | Severity |
|-------|--------|----------|
| 403 blocking on automated fetches | Detected | **HIGH** |
| XML Sitemap | Could not verify (403) | MEDIUM |
| Pages indexed (estimated from site: search) | ~60+ pages | OK |
| Domain migration (magicdesign.io → magier.com) | Completed Feb 2025 | MONITOR |

**The 403 issue is real and must be verified.** If Cloudflare's bot protection is also blocking SEO tool crawlers (Ahrefs, SEMrush, Screaming Frog), then the site cannot be properly audited or monitored. Verify in Cloudflare dashboard that "Verified Bots" are allowed through.

### Core Web Vitals

Cannot measure externally due to 403. Must be tested from:
- Google Search Console → Core Web Vitals report
- PageSpeed Insights (uses real Chrome user data, not blocked by 403)
- Magier's own blog post [Reduce Webflow Bandwidth](https://www.magier.com/blog/reduce-webflow-bandwith) recommends WOFF2 fonts and edge caching — verify these are actually implemented on magier.com itself.

### URL Structure Issues

```
INCONSISTENT:
/webflow-development              ← root level
/webflow-design                   ← root level
/design-services/webdesign        ← nested
/design-services/ui-ux-design     ← nested
/design-services/app-design       ← nested

INCONSISTENT NAMING:
/design-services/webdesign              ← one word
/design-services/social-media-content-design  ← hyphenated words
/design-services/ui-ux-design          ← abbreviation with slashes

BLOG CATEGORIES USE DIFFERENT PATTERN:
/blog-category/marketing          ← "blog-category" prefix
/design-services/app-design       ← nested under parent
/customer/startups                ← nested under parent
```

### Missing Structured Data (Specific)

| Schema Type | Where | Why |
|------------|-------|-----|
| **Organization** | Homepage | Company name, logo, founders (Maximilian Fleitmann, Sina Sadegh), founding date (Feb 2023), social profiles, 30+ team members |
| **AggregateRating** | Homepage, pricing, all service pages | 5 stars, 96 reviews on Trustpilot — this gets star ratings in Google SERPs |
| **Service** | Every `/design-services/*` page | Service name, description, provider, price range (from €2,290/mo) |
| **FAQ** | `/pricing`, `/how-it-works` | These pages contain Q&A content perfect for FAQ rich results |
| **Article/BlogPosting** | Every `/blog/*` page | Author, date published, date modified, publisher |
| **BreadcrumbList** | All nested pages | e.g., Home > Design Services > Landing Page Design |
| **LocalBusiness** | Homepage or `/about-us` | Berlin office, serves clients globally |

---

## Off-Site SEO

### Backlink Profile

**Known referring domains:**
- [Trustpilot](https://www.trustpilot.com/review/www.magier.com) — 96 reviews, 5 stars (previously listed as 75+, now grown)
- [Clutch](https://clutch.co/profile/magier) — 5 reviews
- [DesignProject.io](https://designproject.io/design-agencies/Magier) — Directory listing
- [Founderoo](https://www.founderoo.co/posts/maximilian-fleitmann-magic-design) — Founder profile (still uses "Magic Design" name)
- [Webflow Experts Directory](https://experts.webflow.com/) — Premium Partner listing
- Competitor comparison articles on Renlar, Reel Unlimited mention magier

**Specific problems:**

1. **Founderoo still says "Magic Design"** — The profile at founderoo.co still references the old brand name. This should be updated to "magier" and the URL should point to magier.com.

2. **Glassdoor and Indeed list "Magic Design"** — Employer review sites still use the old name. These pages rank for brand searches and create confusion.

3. **No Product Hunt launch page** — For a startup-focused design subscription, a Product Hunt launch is a high-authority backlink + awareness play that's completely missing.

4. **No G2 or Capterra listing** — Both are high-DA SaaS directories. Competitors like Design Pickle and Penji are listed; magier is not.

5. **Zero guest posts or PR links found** — No evidence of links from TechCrunch, startup blogs, design publications (Smashing Magazine, Creative Bloq, etc.).

6. **Domain migration risk** — magicdesign.io → magier.com migration happened ~12 months ago. Any backlinks pointing to magicdesign.io that aren't 301-redirecting are lost equity. The Founderoo and Glassdoor examples above suggest not all external references have been updated.

---

## Blog Audit: Specific Posts & Issues

### Posts with Stale Year References

These posts have the year baked into the title and are already outdated or will be soon:

| Post | Title | Problem |
|------|-------|---------|
| [Unlimited Design Guide](https://www.magier.com/blog/unlimited-graphic-design-service) | "The Ultimate Guide to Unlimited Graphic Design Services in **2025**" | Stale — it's 2026 |
| [Designjoy Alternatives](https://www.magier.com/blog/best-designjoy-alternatives) | "11 Best Designjoy Alternatives in **2025**" | Stale |
| [Freelance vs Agency](https://www.magier.com/blog/freelance-graphic-designer-vs-agency) | "Freelance Graphic Designer vs Agency – Which is Best in **2025**?" | Stale |
| [Outsource Graphic Design](https://www.magier.com/blog/outsource-graphic-design) | "11 High-Quality & Affordable Platforms to Outsource Graphic Design in **2025**" | Stale |
| [99Designs Alternatives](https://www.magier.com/blog/websites-like-99designs) | "9 Websites Like 99Designs (**2026**)" | Current — good |
| [Upwork Alternatives](https://www.magier.com/blog/upwork-alternatives) | "Top 15 Upwork Alternatives in **2026**" | Current — good |
| [Free Illustrations](https://www.magier.com/blog/best-43-websites-for-free-illustrations) | "Best 44 Websites for Free Illustrations in **2026**" | Current — good |

**Action:** Update all 2025 titles and content to 2026. This is a 1-hour task that immediately makes 4+ posts more competitive.

### Blog Keyword Gaps (Specific Missing Articles)

These are high-intent queries where magier has no content but competitors do:

| Target Keyword | Est. Monthly Volume | Why Magier Should Own This |
|---------------|--------------------|-----------------------------|
| "how much does graphic design cost" | High | Magier's pricing is a key differentiator (€2,290/mo vs competitors at $5,000+). A comprehensive cost guide funnels readers to `/pricing`. |
| "design subscription vs freelancer" | Medium | Magier's blog covers freelancer vs agency but NOT freelancer vs subscription specifically. This is their core value prop. |
| "magier vs design pickle" | Low but high-intent | Zero results for this query from magier.com. Third-party sites fill the gap. |
| "webflow vs wordpress for startups" | Medium | Magier is a Webflow Premium Partner and has a case study about WordPress → Webflow migration. Perfect content fit. |
| "how to brief a designer" | Medium | Educational content that positions magier as an expert and can link to `/how-it-works`. |
| "startup branding checklist" | Medium | Links to `/design-services/brand-design` and `/customer/startups`. |
| "saas website design best practices" | Medium | Links to `/customer/saas` and Webflow services. |

### Blog Posts That Should Cross-Link but Likely Don't

| Blog Post | Mentions | Should Link To |
|-----------|----------|----------------|
| "Best Webflow Design Agency in 2026" | Magier as a Webflow agency | `/webflow-development` (not just homepage) |
| "Subscription Based Design Services" | Design subscription model | `/pricing` with anchor text "see magier's pricing" |
| "Unlimited Graphic Design Services: Pros & Cons" | Pros/cons of the model | `/how-it-works` and `/pricing` |
| "Outsource Graphic Design" | Magier as an outsourcing option | `/design-services` and `/customer/agencies` |
| "Graphic Design Packages" | Package vs subscription comparison | `/pricing` |

---

## Case Studies Audit

### What's Good

- **9 published case studies** — this is more than most competitors
- **Real metrics** in some: Plancraft (20% CR increase), Growdash (doubled leads), Social Heaven (doubled leads), NextRep (60 users in 4 weeks), Jupus (500+ law firms)
- **Diverse industries**: SaaS (Weglot, Plancraft), e-commerce (ParoSwiss, Next Level), legal tech (Jupus), UGC agency (Social Heaven), AI (Pouncer AI)

### What's Missing

| Gap | Specific Example | Fix |
|-----|-----------------|-----|
| **No case study schema markup** | The Plancraft case study mentions "20% increase in conversion rates" and "paid for itself in 30 days" — this should be in structured data. | Add Article schema with speakable sections for key metrics. |
| **Case studies not linked from service pages** | `/webflow-development` doesn't mention Plancraft (20% CR increase) or Next Level E-Commerce (WordPress→Webflow migration) anywhere. | Add a "See Results" section to every service page with 2-3 relevant case studies. |
| **Case study titles are too long for SERPs** | "How Growdash Doubled Their Leads and Built a Recognizable Brand With magier" is 74 chars — Google truncates at ~60. | Shorten: "Growdash Case Study: 2x Leads with magier" |
| **No vertical-specific case study pages** | SaaS companies searching "design subscription for SaaS" don't land on a page showing Weglot + Plancraft + Pouncer AI together. | Create `/case-studies/saas`, `/case-studies/ecommerce` filtered views. |
| **Missing case studies for key services** | No case study specifically showcasing social media design, ad creatives, or packaging design work. | Publish at least one case study per major service offering. |

---

## Recommendations (Prioritized with Specific Actions)

### P0: Do This Week (High Impact, Low Effort)

**1. Fix the 4 stale blog post titles.**
Change "2025" to "2026" in titles and refresh the content of:
- `/blog/unlimited-graphic-design-service`
- `/blog/best-designjoy-alternatives`
- `/blog/freelance-graphic-designer-vs-agency`
- `/blog/outsource-graphic-design`
Effort: ~2 hours. Impact: Immediate SERP freshness signal.

**2. Add FAQ schema to `/pricing` and `/how-it-works`.**
Extract the existing Q&A content on these pages and wrap it in FAQ structured data. Use Google's Rich Results Test to validate.
Effort: ~1 hour per page. Impact: FAQ rich results in Google = more SERP real estate.

**3. Add AggregateRating schema to the homepage.**
You have 96 Trustpilot reviews at 5 stars. Add this as AggregateRating schema:
```json
{
  "@type": "AggregateRating",
  "ratingValue": "5",
  "reviewCount": "96",
  "bestRating": "5"
}
```
Effort: 30 minutes. Impact: Star ratings in search results.

### P1: Do This Month (High Impact, Medium Effort)

**4. Rewrite the 6 templated service pages with unique copy.**
Priority order (by likely search volume):
1. `/design-services/landing-page-design` — rewrite with conversion stats, link to NextRep case study
2. `/design-services/social-media-content-design` — specific platforms, content types, link to Social Heaven case study
3. `/design-services/ad-creatives` — focus on ROI, A/B variations, link to Jupus case study
4. `/design-services/ui-ux-design` — design systems, prototyping, link to Pouncer AI case study
5. `/design-services/brand-design` — brand strategy, guidelines, link to Growdash + ParoSwiss case studies
6. `/design-services/product-design` — clarify scope (remove packaging overlap)

Each page needs minimum 400 words of unique copy, a relevant case study, and a unique FAQ section.

**5. Resolve the 4 cannibalization pairs.**

| Action | Pages |
|--------|-------|
| **Merge** | `/webflow-development` + `/webflow-design` → Keep `/webflow-development`, 301 redirect `/webflow-design` |
| **Merge** | `/design-services/ui-ux-design` + `/design-services/interface-design` → Keep `/ui-ux-design`, 301 redirect `/interface-design` |
| **Differentiate** | `/design-services/ad-creatives` (strategy + concepts) vs `/design-services/social-ad-design` (platform-specific production) — rewrite both to be clearly distinct |
| **Consolidate** | Remove packaging content from `/design-services/product-design`, keep it only on `/design-services/packaging-design` |

**6. Add case study links to every service page.**
Use the mapping in the [Internal Linking Failures](#problem-2-case-studies-not-connected-to-service-pages) section. Each service page should have a "Results" or "Case Studies" section with 2-3 relevant links.

**7. Flip all brand-first title tags to keyword-first.**
Change pattern from `magier - [keyword]` to `[Keyword] | magier`. Priority pages:
- Homepage: `Unlimited Graphic Design & Webflow Subscription | magier`
- Design Services: `Graphic Design Services - Unlimited Subscription | magier`
- About Us: `About magier - Design & Webflow Agency, Berlin`

**8. Create 3 competitor comparison pages.**
Start with the competitors most mentioned in magier's own blog content:
- `/vs/design-pickle` — magier's blog already discusses Design Pickle. Turn that into a dedicated comparison.
- `/vs/penji` — mentioned in alternatives articles.
- `/vs/superside` — enterprise-level competitor, different positioning.

Each page: feature comparison table, pricing comparison, honest pros/cons, CTA.

### P2: Do This Quarter (Medium Impact)

**9. Implement full schema markup suite.**
- Organization schema on homepage
- Service schema on all `/design-services/*` pages
- BreadcrumbList on all nested pages
- Article schema on all blog posts
- LocalBusiness schema on `/about-us`

**10. Publish 5 missing blog articles.**
Priority order:
1. "How Much Does Graphic Design Cost in 2026?" (high volume, links to `/pricing`)
2. "Webflow vs WordPress for Startups" (medium volume, links to `/webflow-development`, references Next Level E-Commerce case study)
3. "Design Subscription vs Hiring a Freelancer: Real Cost Comparison" (core value prop)
4. "SaaS Website Design Best Practices" (links to `/customer/saas`)
5. "How to Brief a Designer" (links to `/how-it-works`)

**11. Fix external brand references.**
- Update Founderoo profile from "Magic Design" to "magier"
- Update Glassdoor and Indeed company names
- Verify all magicdesign.io 301 redirects are working
- Contact top linking sites to update URLs

**12. List on missing directories.**
- Product Hunt (launch page)
- G2 (SaaS category)
- Capterra
- Webflow Showcase

**13. Add internal cross-links from blog to service pages.**
Use the specific mapping in [Blog Posts That Should Cross-Link](#blog-posts-that-should-cross-link-but-likely-dont). Each blog post should have at least one contextual link to the most relevant service page.

### P3: Ongoing

**14. Set up quarterly content refresh schedule.**
Every quarter, update year references in blog titles, refresh pricing/competitor data, add new case studies.

**15. Run PageSpeed Insights on the top 10 pages.**
Verify Core Web Vitals pass. Check if magier follows its own blog advice (WOFF2 fonts, edge caching, image optimization).

**16. Build link-worthy assets.**
- "State of Design Subscriptions 2026" report (linkable from design blogs)
- Free Webflow templates (linkable from Webflow community)
- Design brief template (linkable from startup blogs)

---

## Summary Scorecard

| Category | Score | Key Issue |
|----------|-------|-----------|
| **Technical SEO** | 6/10 | 403 crawler blocking unverified, zero structured data, CWV unknown |
| **Title Tags** | 4/10 | Brand-first pattern, thin titles ("UI / UX Design – magier"), 4 cannibalization pairs |
| **Content Quality** | 4/10 | 6+ service pages with templated duplicate copy, stale 2025 blog titles |
| **Internal Linking** | 3/10 | 9 case studies disconnected from service pages, blog→service links weak, orphaned root pages |
| **Off-Site SEO** | 4/10 | Old brand references, missing from major directories, no PR/guest post links |
| **Content Coverage** | 5/10 | Good blog foundation but missing comparison pages, cost guides, vertical content |
| **Schema/Rich Results** | 2/10 | No FAQ, AggregateRating, Service, or BreadcrumbList schema found |
| **Overall** | 4/10 | Strong brand and product, but the SEO fundamentals are leaking traffic to competitors |

---

*Audit conducted February 17, 2026. Data gathered from Google search index, SERP title/snippet extraction, and web search analysis across 60+ indexed pages. Direct on-page crawl data limited due to 403 access restrictions — a full Screaming Frog crawl with whitelisted IP is recommended to validate heading structure, image alt text, and internal link counts.*
