---
layout: about
title: about
permalink: /
subtitle: Ph.D. student @ UMN CSE · Personal agents · Memory · Mid-/post-training · Test-time adaptation

profile:
  align: left
  image: yosemite.jpg
  image_circular: false

selected_papers: false
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5
---

I’m **Wenya Xie**, a Ph.D. student in Computer Science at the **University of Minnesota (UMN)**, advised by [**Prof. Zirui Liu**](https://zirui-ray-liu.github.io/). Previously, I worked as a research assistant at CUHK (Shenzhen) with Prof. Benyou Wang and Feng Jiang. I received my bachelor’s degree from Wuhan University.

I’m excited by how the way people work with AI is changing. As AI starts acting on our behalf, people rarely spell out everything they want, so models need to understand the person they work with. Here is how my work fits together:

<div class="research-diagram-wrap">
<svg class="research-diagram" viewBox="0 0 900 332" xmlns="http://www.w3.org/2000/svg" role="img" aria-labelledby="rd-title">
<title id="rd-title">A person gives partial signals; an AI that understands the person, built through training, memory and test-time methods, acts for the person as a personal agent or as the person in user simulation.</title>
<defs><marker id="rd-arrow" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="7" markerHeight="7" orient="auto-start-reverse"><path d="M0,0 L10,5 L0,10 z" class="rd-arrowhead"/></marker></defs>
<circle cx="46" cy="93.0" r="16" class="rd-person"/>
<path d="M18,149.0 Q18,115.0 46,115.0 Q74,115.0 74,149.0 Z" class="rd-person"/>
<text x="46" y="171.0" text-anchor="middle" class="rd-label">A person</text>
<text x="158.0" y="63.0" text-anchor="middle" class="rd-muted rd-small">says only part of</text>
<text x="158.0" y="77.0" text-anchor="middle" class="rd-muted rd-small">what they want</text>
<rect x="102" y="89" width="112" height="22" rx="11" class="rd-signal"/>
<text x="158.0" y="104" text-anchor="middle" class="rd-text rd-small">vague requests</text>
<rect x="102" y="119" width="112" height="22" rx="11" class="rd-signal"/>
<text x="158.0" y="134" text-anchor="middle" class="rd-text rd-small">daily activity</text>
<rect x="102" y="149" width="112" height="22" rx="11" class="rd-signal"/>
<text x="158.0" y="164" text-anchor="middle" class="rd-text rd-small">feedback</text>
<line x1="220" y1="125" x2="262" y2="125" class="rd-line" marker-end="url(#rd-arrow)"/>
<rect x="266" y="8" width="630" height="234" rx="12" class="rd-box"/>
<text x="286" y="38" class="rd-title-text">AI that understands the person</text>
<line x1="280" y1="52" x2="882" y2="52" class="rd-divider"/>
<text x="286" y="74" class="rd-stage">TRAINING</text>
<text x="286" y="89" class="rd-muted rd-small">learn how people decide</text>
<rect x="434" y="60" width="197" height="25" rx="6" class="rd-chip rd-ongoing"/><text x="452" y="77" class="rd-text rd-chiptext">Mid-training on synthetic data</text>
<rect x="640" y="60" width="203" height="25" rx="6" class="rd-chip rd-ongoing"/><text x="658" y="77" class="rd-text rd-chiptext">Post-training on user feedback</text>
<line x1="280" y1="102" x2="882" y2="102" class="rd-divider"/>
<text x="286" y="124" class="rd-stage">MEMORY</text>
<text x="286" y="139" class="rd-muted rd-small">remember this person</text>
<a href="https://wenyaxie023.github.io/DynamicMem/" target="_blank" rel="noopener" class="rd-link"><rect x="434" y="110" width="105" height="25" rx="6" class="rd-chip"/><text x="449" y="127" class="rd-text rd-chiptext">DynamicMem</text></a>
<a href="https://arxiv.org/abs/2505.16067" target="_blank" rel="noopener" class="rd-link"><rect x="548" y="110" width="237" height="25" rx="6" class="rd-chip"/><text x="568" y="127" class="rd-text rd-chiptext">Memory management · ACL’26 <tspan class="rd-oral">Oral</tspan></text></a>
<line x1="280" y1="152" x2="882" y2="152" class="rd-divider"/>
<text x="286" y="174" class="rd-stage">TEST TIME</text>
<text x="286" y="189" class="rd-muted rd-small">ask, reason, act</text>
<a href="https://arxiv.org/abs/2511.00536" target="_blank" rel="noopener" class="rd-link"><rect x="434" y="160" width="253" height="25" rx="6" class="rd-chip"/><text x="454" y="177" class="rd-text rd-chiptext">Word Salad Chopper · EMNLP’25 <tspan class="rd-oral">Oral</tspan></text></a>
<a href="https://arxiv.org/abs/2601.22139" target="_blank" rel="noopener" class="rd-link"><rect x="434" y="194" width="197" height="25" rx="6" class="rd-chip"/><text x="452" y="211" class="rd-text rd-chiptext">Ask while reasoning · ACL’26</text></a>
<rect x="640" y="194" width="219" height="25" rx="6" class="rd-chip"/><text x="659" y="211" class="rd-text rd-chiptext">Adobe: AJO Orchestration Guard</text>
<line x1="416" y1="244" x2="416" y2="280" class="rd-line" marker-end="url(#rd-arrow)"/>
<text x="416" y="298" text-anchor="middle" class="rd-out">Personal agents</text>
<text x="416" y="315" text-anchor="middle" class="rd-muted rd-small">act for the person</text>
<line x1="696" y1="244" x2="696" y2="280" class="rd-line" marker-end="url(#rd-arrow)"/>
<text x="696" y="298" text-anchor="middle" class="rd-out">User simulation</text>
<text x="696" y="315" text-anchor="middle" class="rd-muted rd-small">act as the person</text>
<rect x="818" y="305" width="20" height="11" rx="3" class="rd-chip rd-ongoing"/>
<text x="844" y="315" class="rd-muted rd-small">ongoing</text>
</svg>
<p class="rd-also">Also: <a href="https://arxiv.org/abs/2506.09501">reproducible reasoning evaluation</a> (NeurIPS 2025 <strong>Oral</strong>).</p>
</div>

<div class="research-map">
  <section class="rm-card">
    <h3 class="rm-stage">Training</h3>
    <ul>
      <li><span class="rm-title">Mid-training on synthetic data to predict how individuals decide</span><span class="rm-venue">Ongoing</span></li>
      <li><span class="rm-title">Post-training from vague, real-world user feedback</span><span class="rm-venue">Ongoing</span></li>
    </ul>
  </section>
  <section class="rm-card">
    <h3 class="rm-stage">Test time</h3>
    <ul>
      <li><a class="rm-title" href="https://arxiv.org/abs/2505.16067">How memory management shapes agent behavior</a><span class="rm-venue">ACL 2026 · <strong>Oral</strong></span></li>
      <li><a class="rm-title" href="https://arxiv.org/abs/2601.22139">Asking clarifying questions while reasoning</a><span class="rm-venue">ACL 2026</span></li>
      <li><a class="rm-title" href="https://arxiv.org/abs/2511.00536">Cutting repetitive reasoning during decoding</a><span class="rm-venue">EMNLP 2025 · <strong>Oral</strong></span></li>
      <li><span class="rm-title">AJO Orchestration Guard: executing agent skills on underspecified requests</span><span class="rm-venue">Adobe internship 2026</span></li>
    </ul>
  </section>
  <section class="rm-card">
    <h3 class="rm-stage">Memory &amp; evaluation</h3>
    <ul>
      <li><a class="rm-title" href="https://wenyaxie023.github.io/DynamicMem/">DynamicMem: tracking users’ changing preferences</a><span class="rm-venue">Benchmark 2026</span></li>
      <li><a class="rm-title" href="https://arxiv.org/abs/2506.09501">Reproducible reasoning evaluation</a><span class="rm-venue">NeurIPS 2025 · <strong>Oral</strong></span></li>
    </ul>
  </section>
</div>

I’m always excited to connect. Questions, ideas, and early-stage thoughts are all welcome.
If you have anything you'd like to discuss, feel free to reach out!
