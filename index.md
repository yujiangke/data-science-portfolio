---
layout: default
title: Guanyu Ke — Data Science Portfolio
---
<div class="hero"><div class="eyebrow">Data science · Clear evidence · Honest limits</div><h1>Making patterns<br>understandable.</h1><p class="intro">I’m Guanyu Ke, an M.Sc. Data Science student at the University of Macau, studying Computational Linguistics. This portfolio documents my ongoing work in data analysis and visualization.</p></div>

## Technical skills

<div class="tags"><span>Python</span><span>pandas & NumPy</span><span>Matplotlib</span><span>Jupyter Notebook</span><span>Data validation</span><span>Git & GitHub</span></div>

<div id="projects"></div>

## Selected project

<div class="card" markdown="1">
<span class="status">Ongoing · 2023–2025 monthly data</span>

### Macao tourism: a changing visitor mix

**Research question:** Which visitor type supplied the increase in arrivals, and how did hotel occupancy change over the same 36 months?

**Main finding:** Same-day visitors accounted for approximately **90% of the increase in visitor arrivals from 2024 to 2025**.

![Monthly visitor arrivals and hotel room occupancy in Macao, 2023–2025](assets/monthly_arrivals_occupancy.png)

<p class="caption">Same-day and overnight arrivals use one scale; occupancy uses a separate aligned panel with a 0–100% scale. Source: DSEC via MGTO Tourism Statistics; author calculations.</p>

Same-day visitors supplied approximately **90% of the increase from 2024 to 2025**. Their share of all arrivals rose from about 50% to 59% across 2023–2025. The simple mean of monthly hotel occupancy rates rose from about 81% to 89% over the same period.

![Decomposition of the annual increase in Macao visitor arrivals by visitor type](assets/annual_growth_contributions.png)

<p class="caption">Each stacked bar adds to the annual increase. The same-day contribution is printed beside each bar. Annual totals hide within-year variation.</p>

<aside><strong>What these data cannot establish</strong><br>Co-movement does not prove that high occupancy caused more same-day visits. Arrivals count trips, and overnight visitors need not stay in hotels. Room supply, prices, market mix and earlier baseline years are absent.</aside>

**Next steps:** Add room supply, prices and visitor-market detail; inspect seasonality and improve the source-data retrieval workflow.

<div class="links"><a href="https://github.com/yujiangke/data-science-project">Explore code & methods ↗</a><a href="https://github.com/yujiangke/data-science-project/blob/main/macao_tourism_analysis.ipynb">Read the Notebook ↗</a><a href="https://dataplus.macaotourism.gov.mo/">Official data source ↗</a></div>
</div>

## How I approach analysis

I keep the research question, data definitions and transformations visible. I check joins and missing values before plotting, use charts that support meaningful comparisons, and separate observed patterns from causal explanations.

This page presents an ongoing course project. See the repository for source details, reproduction instructions and usage limitations.
