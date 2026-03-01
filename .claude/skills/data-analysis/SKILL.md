---
name: data-analysis
description: Marketing data analysis and performance reporting. Use when the user wants to analyze campaign performance, interpret marketing metrics, build dashboards, identify trends, diagnose underperformance, or generate insights from marketing data.
---

# Data Analysis Skill

Analyze marketing data to surface insights, diagnose performance, and drive data-informed decisions.

## Workflow

Make a todo list for all the tasks in this workflow and work on them one after another.

### 1. Define Analysis Goals

Ask the user for the following if not already provided:
- What decision or question does this analysis need to answer?
- What data is available? (CSV, spreadsheet, GA4, CRM export, ad platform data, etc.)
- Channels covered (paid search, paid social, email, organic, etc.)
- Time period for analysis
- Key metrics to focus on
- Benchmarks to compare against (industry, historical, target)
- Who is the audience for this analysis (exec team, marketing team, investors)?

### 2. Data Audit

Review the provided data for:
- Completeness (missing values, gaps in date ranges)
- Consistency (naming conventions, UTM tracking, attribution model)
- Data quality issues (anomalies, duplicates, tracking errors)
- Coverage (which channels and touchpoints are tracked)

Document any data limitations that affect the analysis.

### 3. Core Metrics Analysis

Analyze key marketing metrics across relevant dimensions:

**Acquisition Metrics:**
- Impressions, Reach, Share of Voice
- Clicks, Sessions, New Users
- Cost Per Click (CPC), Cost Per Mille (CPM)
- Click-Through Rate (CTR)

**Engagement Metrics:**
- Engagement Rate, Time on Page, Scroll Depth
- Email Open Rate, Click-to-Open Rate
- Social Likes, Comments, Shares, Saves
- Video View Rate, Watch Time

**Conversion Metrics:**
- Leads / MQLs / SQLs generated
- Conversion Rate (CVR) by channel and funnel stage
- Cost Per Lead (CPL), Cost Per Acquisition (CPA)
- Pipeline generated, Revenue attributed

**Retention & Loyalty:**
- Repeat Purchase Rate
- Customer Lifetime Value (CLV)
- Churn Rate
- Net Promoter Score (NPS) trends

**ROI Metrics:**
- Return on Ad Spend (ROAS)
- Marketing Efficiency Ratio (MER)
- Return on Investment (ROI)

### 4. Segment & Dimension Breakdowns

Break down metrics by:
- Channel and campaign
- Audience segment or cohort
- Geography or market
- Device type
- Creative / ad variant
- Time period (MoM, QoQ, YoY)

### 5. Trend & Anomaly Detection

- Identify significant trends (growth, decline, plateaus)
- Flag anomalies and investigate root causes
- Correlate performance changes with external events (seasonality, launches, competitor moves)

### 6. Insight Generation

For each key finding, document:
- **Observation:** What the data shows
- **So What:** Why it matters
- **Hypothesis:** What might be causing it
- **Recommendation:** What to do about it

Prioritize insights by business impact.

### 7. Reporting Output

Structure the analysis as:

**Executive Summary:**
- Top 3–5 insights
- Overall performance vs. goals
- Recommended actions

**Performance Dashboard (table format):**
| Metric | Current | Previous | Change | vs. Target |
|--------|---------|---------|--------|------------|
| ...    | ...     | ...     | ...    | ...        |

**Channel Breakdown:**
- Performance summary per channel
- Top performing campaigns/creatives
- Underperformers and why

**Recommendations:**
- Prioritized list of actions with expected impact
- Quick wins vs. strategic shifts
- Experiments to run

## Output Format

Deliver analysis as structured markdown with:
- Tables for quantitative comparisons
- Bullet-pointed insights
- Bold callouts for the most critical findings
- Clearly labeled sections for easy navigation

If data is provided as a file, parse and compute metrics directly before presenting.

## Wrap Up

Summarize what was analyzed and the top 3 recommendations. Offer to:
- Dive deeper into a specific channel or metric
- Build a recurring reporting template
- Feed insights into the campaign-presentation or research-strategy skills
