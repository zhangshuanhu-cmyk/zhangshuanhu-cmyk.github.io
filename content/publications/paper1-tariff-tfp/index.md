---
title: 'Causal Evidence from China''s Staggered Tariff Liberalization: Firm-Level TFP Effects'

# Authors
authors:
  - me

# Date (working paper, use expected completion date)
date: '2026-08-31'
doi: ''

# Schedule page publish date (NOT paper date)
publishDate: '2026-05-25'

# Publication type
# 0=Uncategorized 1=Conference paper 2=Journal article 3=Preprint 4=Report 5=Book 6=Book section 7=Thesis 8=Patent
publication_types: ['3']

# Publication name and optional abbreviated name
publication: '*Working Paper*'
publication_short: 'WP'

abstract: |
  This paper estimates the causal effect of tariff liberalization on firm-level total factor productivity (TFP)
  using China's WTO accession as a natural experiment. I exploit the staggered, sector-specific timing of
  tariff reductions (2002, 2004, 2006, 2007, 2010) as quasi-random variation in treatment timing.
  Using the Callaway & Sant'Anna (2021) estimator — robust to heterogeneous treatment effects across cohorts —
  I find evidence that [preliminary results pending data assembly]. I further decompose effects by input versus
  output tariff channels and examine heterogeneity across firm ownership type (SOE vs. private) and export status.

# Featured (appears on homepage)
featured: true

# Tags
tags:
  - Trade Policy
  - TFP
  - Difference-in-Differences
  - China
  - WTO

# Links
links:
  - name: Code
    url: https://github.com/zhangshuanhu-cmyk/research
    icon_pack: fab
    icon: github
url_pdf: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Focal image (place image in same folder as index.md)
image:
  caption: ''
  focal_point: ''
  preview_only: false
---

## Status

**Active** — data assembly phase. Results expected Q3 2026.

## Identification Strategy

**Setting**: China's WTO accession (2001) triggered pre-negotiated, sector-specific tariff reductions
across five rounds (2002, 2004, 2006, 2007, 2010). This staggered timing is exogenous to firm outcomes
because reduction schedules were determined during pre-accession negotiations, not in response to
contemporaneous firm performance.

**Estimator**: Callaway & Sant'Anna (2021) staggered DiD, which is robust to treatment effect
heterogeneity across cohorts and allows for non-parallel pre-trends to be tested formally.

**Instrument** (robustness): WTO-bound tariff schedule, which provides a pre-negotiated, binding ceiling
on applied tariffs — exogenous to Chinese firm productivity shocks.

## Data

| Source | Variable | Status |
|--------|----------|--------|
| CEPII BACI (HS92) | Bilateral trade flows | Available |
| WTO Tariff Facility | MFN applied tariffs | Download pending |
| CSMAR | Firm financials (A-share) | Access pending |
| FRED | Macro controls | Available |

## Target Journal

Journal of International Economics (JIE) / Review of Economics and Statistics (REStat)
