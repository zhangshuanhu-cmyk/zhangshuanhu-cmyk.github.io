---
title: ''
summary: ''
date: 2026-05-25
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research sits at the intersection of international trade and firm-level microeconometrics.
        I use quasi-experimental methods to estimate the causal effects of trade policy on firm performance,
        with a focus on China's integration into the global economy.

        **Current projects**
        - *Trade Policy and Firm TFP*: Staggered DiD analysis of China's WTO tariff liberalization
          (Callaway & Sant'Anna 2021), exploiting sector-specific reduction schedules as quasi-random variation.

        **Methods**: Staggered DiD · RDD · IV/2SLS · Event Study · Synthetic DiD

        **Data**: CEPII BACI · CSMAR · WTO Tariff Facility · FRED · World Bank WDI
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Working Papers
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publications
        exclude_featured: true
    design:
      view: citation
---
