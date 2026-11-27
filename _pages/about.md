---
layout: about
title: about
permalink: /
subtitle: Ph.D. candidate @ UMN CSE · Data and evaluation for LLM agents

profile:
  align: left
  image: yosemite.jpg
  image_circular: false

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

# Shown between selected publications and news (rendered by _layouts/about.liquid).
# TODO(Wenya): confirm the Adobe end month (Aug 2026 is taken from the PDF CV).
experience:
  - org: Adobe
    role: Machine Learning Engineer Intern, San Jose
    dates: May 2026 – Aug 2026
    detail: "Agent skills and workflow orchestration: making agents execute skills reliably when user requests are underspecified."
  - org: CUHK (Shenzhen)
    role: Research Assistant
    dates: Jun 2023 – Sep 2024

# Shown after news (rendered by _layouts/about.liquid).
outside_of_research: >
  I read widely: literature, philosophy, psychology, sociology, and economics. Books keep reminding me
  how large and varied the world is, and that makes me genuinely happy. I also exercise regularly. It’s
  where I relearn, every time, that pain is temporary and that my life is mine to steer. And I keep a
  daily journal.
---

I’m **Wenya Xie**, a Ph.D. candidate in Computer Science at the **University of Minnesota**, advised by [Prof. Zirui Liu](https://zirui-ray-liu.github.io/). Previously, I was a research assistant at CUHK (Shenzhen) with Prof. Benyou Wang and Feng Jiang.

I work on data and evaluation for LLM agents. Agents will only be everywhere once they are cheap to build and run, so the question I care about is how much data and how large a model it takes to do a task reliably, and how to measure that. My work on agent memory, efficient reasoning, and evaluation has appeared at ACL, NeurIPS, and EMNLP, including three oral presentations. I’m now working on mid-training: building the data and measuring whether it works.

<div class="intern-callout">
  <p>I’m looking for a <strong>research internship starting as early as January 2027</strong>, and I’m flexible on length (6 to 12 months).</p>
  <a class="intern-callout-btn" href="mailto:{{ site.data.socials.email }}">Email me</a>
</div>

## current work

I’m training a model to predict individual human decisions. So far I have collected real decision data organized by a task taxonomy, and I’m synthesizing reasoning traces.
