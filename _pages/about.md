---
permalink: /
title: "Guanzhou Ke"
excerpt: "Active embodied intelligence under partial observability, focused on active perception, world models, and self-improving agents, with current work grounded in UAV autonomy and inspection."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="home-profile">
  <section class="home-hero" aria-labelledby="home-title">
    <p class="home-hero__eyebrow">Guanzhou Ke · 柯冠舟</p>
    <h1 id="home-title">Active embodied intelligence<br />under partial observability</h1>
    <p class="home-hero__themes">Active perception <span aria-hidden="true">·</span> World models <span aria-hidden="true">·</span> Self-improving agents</p>
    <p class="home-hero__positioning">{{ site.data.profile.positioning }}</p>
    <nav class="home-actions" aria-label="Primary links">
      <a class="btn btn--primary" href="{{ '/research/' | relative_url }}">Research</a>
      <a class="btn" href="{{ '/publications/' | relative_url }}">Publications</a>
      <a class="btn" href="{{ '/cv/' | relative_url }}">CV</a>
      <a class="btn" href="{{ site.data.profile.author.googlescholar }}" target="_blank" rel="noopener noreferrer">Google Scholar</a>
      <a class="btn" href="https://github.com/{{ site.data.profile.author.github }}" target="_blank" rel="noopener noreferrer">GitHub</a>
    </nav>
  </section>

  <section id="bio" class="home-section" aria-labelledby="bio-title">
    <h2 id="bio-title">Bio</h2>
    <p>I am Guanzhou Ke, an Embodied AI Researcher at Avant Robotics in Shenzhen, working on active embodied intelligence under partial observability. My current work studies how autonomous drones can actively acquire task-relevant evidence, learn from difficult simulated and real-world scenarios, and improve through an evaluation–data–training loop.</p>
    <p>I received my Ph.D. from Beijing Jiaotong University and was a CSC visiting Ph.D. researcher at Singapore Management University. My earlier research on multi-view representation learning and missing-modality completion provides the foundation for studying decision-making under partial observability.</p>
  </section>

  <section id="agenda" class="home-section" aria-labelledby="agenda-title">
    <div class="section-heading">
      <div>
        <p class="section-kicker">Research agenda</p>
        <h2 id="agenda-title">A closed loop for reliable autonomy</h2>
      </div>
      <a href="{{ '/research/' | relative_url }}">Explore the agenda →</a>
    </div>
    <div class="agenda-grid">
      <article class="agenda-card">
        <span class="status-label">Ongoing research</span>
        <h3>Active Perception for UAV Inspection</h3>
        <p>How should a drone coordinate wide-field cameras, a high-resolution gimbal, and body motion to obtain sufficient evidence for an inspection task?</p>
      </article>
      <article class="agenda-card">
        <span class="card-number">02</span>
        <h3>Self-evolving Simulation and Data Engines</h3>
        <p>Building evaluation-driven loops that identify failure modes, generate targeted interaction data, and improve navigation and action models.</p>
      </article>
      <article class="agenda-card">
        <span class="card-number">03</span>
        <h3>Reliable Multimodal Intelligence</h3>
        <p>Learning and reasoning when observations are incomplete, missing, uncertain, or viewpoint-dependent.</p>
      </article>
    </div>
  </section>

  <section id="featured" class="home-section" aria-labelledby="featured-title">
    <p class="section-kicker">Featured systems and research</p>
    <h2 id="featured-title">From evaluation to evidence</h2>
    <div class="featured-list">
      <article class="featured-item">
        <div class="featured-item__index">01</div>
        <div>
          <h3>Simulation-driven embodied learning loop</h3>
          <p><strong>Problem.</strong> UAV policies need repeatable evaluation across navigation, exploration, object search, and obstacle-avoidance tasks—not only more undirected data.</p>
          <p><strong>Individual role.</strong> As an Embodied AI Researcher, I work on the simulation, evaluation, and data-engine pipeline that connects hard-case discovery, targeted interaction collection, and model improvement across VLN/VLA, object search, exploration, navigation, and obstacle avoidance.</p>
          <p class="evidence-note"><strong>Team evidence.</strong> The resulting team system produces 39 million valid simulated interaction steps per month, improves sampling throughput by 3× on a single RTX 5090, and supports a 0.8B world/action model reporting 74% navigation-and-avoidance success.</p>
        </div>
      </article>
      <article class="featured-item">
        <div class="featured-item__index">02</div>
        <div>
          <h3>Real-world-grounded scenario construction</h3>
          <p><strong>Problem.</strong> Useful simulated environments must preserve real-world coordinates, task executability, and repeatability rather than act as generic text-to-3D assets.</p>
          <p><strong>Contribution.</strong> Current work studies geospatially aligned scenario construction and the return of evaluation failures into the data loop.</p>
          <p class="evidence-note"><strong>Disclosure boundary.</strong> Specific scene sources and named locations remain private.</p>
        </div>
      </article>
      <article class="featured-item featured-item--ongoing">
        <div class="featured-item__index">03</div>
        <div>
          <span class="status-label">Ongoing research</span>
          <h3>Active evidence acquisition for UAV inspection</h3>
          <p><strong>Question.</strong> When evidence is incomplete, how should a UAV choose what to inspect next, where to move, and when enough visual evidence has been gathered?</p>
          <p><strong>Current direction.</strong> Jointly reason over viewpoint, sensing resolution, gimbal control, latency, bandwidth, and safety constraints. No completed benchmark or public system is claimed.</p>
        </div>
      </article>
    </div>
  </section>

  <section id="selected-publications" class="home-section" aria-labelledby="selected-publications-title">
    <div class="section-heading">
      <div>
        <p class="section-kicker">Selected publications</p>
        <h2 id="selected-publications-title">Foundations for partial observability</h2>
      </div>
      <a href="{{ '/publications/' | relative_url }}">View all publications →</a>
    </div>
    <div class="publication-grid">
      {% assign featured_pubs = site.publications | where_exp: "post", "post.featured_order" | sort: "featured_order" %}
      {% for post in featured_pubs %}
        {% include publication-card.html post=post %}
      {% endfor %}
    </div>
  </section>

  <section id="news" class="home-section" aria-labelledby="news-title">
    <p class="section-kicker">Selected news</p>
    <h2 id="news-title">Recent milestones</h2>
    <ol class="news-list">
      <li><time datetime="2026-05">May 2026</time><span>Paper accepted at IEEE T-PAMI.</span></li>
      <li><time datetime="2026-05">May 2026</time><span>Recognized as an ICML 2026 Gold Reviewer.</span></li>
      <li><time datetime="2026-05">May 2026</time><span>Paper accepted at ICML 2026.</span></li>
      <li><time datetime="2026-03">March 2026</time><span>Paper accepted to the CVPR 2026 Findings track.</span></li>
      <li><time datetime="2025-02">February 2025</time><span>Knowledge Bridger accepted at CVPR 2025.</span></li>
    </ol>
  </section>

  <section id="experience" class="home-section" aria-labelledby="experience-title">
    <p class="section-kicker">Experience and service</p>
    <h2 id="experience-title">Research across systems and learning</h2>
    <div class="experience-grid">
      <div>
        <h3>Experience</h3>
        <ul class="compact-list">
          <li><strong>Avant Robotics</strong>, Embodied AI Researcher, Shenzhen <span>· Dec. 2025–present</span><br /><span class="todo-note">Active embodied intelligence, world/action models, data engines, and UAV autonomy.</span></li>
          <li><strong>Microsoft Research Asia</strong>, Research Intern <span>· Feb.–Oct. 2024</span></li>
          <li><strong>Institute of Automation, CAS</strong>, Research Intern <span>· Jun.–Dec. 2023</span></li>
          <li><strong>Singapore Management University</strong>, CSC Visiting Ph.D. Researcher <span>· Oct. 2024–Oct. 2025</span></li>
        </ul>
      </div>
      <div>
        <h3>Service</h3>
        <p>Reviewer for journals including IEEE TMM, T-CSVT, and T-NNLS, and conferences including NeurIPS, CVPR, ICML, AAAI, and ACM MM.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="home-section contact-panel" aria-labelledby="contact-title">
    <div>
      <p class="section-kicker">Contact</p>
      <h2 id="contact-title">Let’s exchange ideas</h2>
      <p>I welcome conversations about UAV autonomy, active perception, simulation and data engines, and reliable multimodal learning.</p>
    </div>
    <div class="contact-links">
      <a href="mailto:{{ site.data.profile.author.email }}">Email</a>
      <a href="{{ site.data.profile.author.googlescholar }}" target="_blank" rel="noopener noreferrer">Google Scholar</a>
      <a href="{{ site.data.profile.author.orcid }}" target="_blank" rel="noopener noreferrer">ORCID</a>
      <a href="https://github.com/{{ site.data.profile.author.github }}" target="_blank" rel="noopener noreferrer">GitHub</a>
    </div>
  </section>
</div>
