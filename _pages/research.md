---
permalink: /research/
title: "Research"
excerpt: "Research agenda for active embodied intelligence under partial observability."
author_profile: true
---

<div class="home-profile research-page">
  <header class="research-intro">
    <p class="section-kicker">Research agenda</p>
    <h1>Active embodied intelligence is an evidence problem.</h1>
    <p>{{ site.data.profile.positioning }}</p>
    <p class="research-intro__zh" lang="zh-CN">{{ site.data.profile.positioning_zh }}</p>
  </header>

  <section class="research-pillar">
    <span class="status-label">Ongoing research</span>
    <h2>Active Perception for UAV Inspection</h2>
    <p>A drone rarely begins with all the evidence an inspection task requires. The research question is how to coordinate wide-field sensing, a high-resolution gimbal, and body motion while respecting viewpoint, bandwidth, latency, and safety constraints.</p>
    <p>The goal is a policy that can decide <em>what</em> evidence is missing, <em>where</em> to acquire it, and <em>when</em> the evidence is sufficient. This is a research agenda, not a claim of a completed benchmark or deployed system.</p>
  </section>

  <section class="research-pillar">
    <span class="card-number">02</span>
    <h2>Self-evolving Simulation and Data Engines</h2>
    <p>Evaluation should drive data collection. As an Embodied AI Researcher at Avant Robotics, I work on feedback loops that expose failure modes in embodied UAV tasks, collect targeted interaction data around those failures, and use the resulting evidence to improve navigation and action models.</p>
    <p>The team system produces 39 million valid simulated interaction steps per month, improves sampling throughput by 3× on a single RTX 5090, and supports a 0.8B world/action model reporting 74% navigation-and-avoidance success. These figures describe the integrated team system rather than an individual result.</p>
    <p>The emphasis is on task coverage, repeatability, and real-world grounding. Specific scene sources and named locations remain private.</p>
  </section>

  <section class="research-pillar">
    <span class="card-number">03</span>
    <h2>Reliable Multimodal Intelligence under Partial Observability</h2>
    <p>My earlier work asks how models can learn when views or modalities are missing. That foundation now supports a broader embodied question: how should an agent reason and act when observations are incomplete, uncertain, or viewpoint-dependent?</p>
    <p><a href="{{ '/publications/' | relative_url }}">Read the publications that establish this foundation →</a></p>
  </section>
</div>
