---
permalink: /
title: "About"
layout: home
redirect_from:
  - /about/
  - /about.html
---

Hi, I'm **Min Cai (蔡旻)**. I'm an incoming PhD student at the University of Alberta, supervised by <a href="https://xiye17.github.io">Dr. Xi Ye</a>. Previously, I was an M.S. student graduated from Shenzhen University, where I was supervised by <a href="https://hdzhangust.github.io">Prof. Haodi Zhang</a>. Before that, I obtained my B.A. in Translation from Beijing Language and Culture University. Currently, I'm interning at Zhipu AI, mentored by <a href="https://zhangdan0602.github.io">Dr. Dan Zhang</a>. I also work closely with <a href="https://acbull.github.io">Dr. Ziniu Hu</a>, <a href="https://shichangzh.github.io">Dr. Shichang Zhang</a>, and <a href="https://difanzou.github.io">Dr. Difan Zou</a>.

I have broad interests in ML and NLP, particularly in understanding the mechanisms behind neural language models, developing LLM agents capable of solving complex problems, and enhancing LLM reasoning. **My primary focus is on inference-time algorithms for alignment and reasoning in LLMs.**

**Research areas:**
- **Interpreting and controlling LLM behaviors** — mechanistic understanding for better alignment with human values (e.g., <a href="https://llm-self-control.github.io">SelfControl</a>)
- **LLM Agents** — solving complex tasks via multi-agent games and strategic planning (e.g., <a href="https://avalonbench.github.io">AvalonBench</a>)
- **LLM Reasoning** — inference-time algorithms such as Monte Carlo tree search and representation engineering (e.g., <a href="https://llm-strategist.github.io">Strategist</a>)

# Selected Publications

<div class="pub-list">

<div class="pub-card">
  <div class="pub-thumb">
    <img src="/images/how_post_train_reshapes.png" alt="Paper figure">
  </div>
  <div class="pub-body">
    <div class="pub-venue-badge">
      <span class="pub-venue">Preprint</span>
      <span class="pub-award">★ Outstanding Paper — New England NLP Workshop</span>
    </div>
    <p class="pub-title">How Post-Training Reshapes LLMs: A Mechanistic View on Knowledge, Truthfulness, Refusal, and Confidence</p>
    <p class="pub-authors">Hongzhe Du*, Weikai Li*, <strong>Min Cai</strong>, Karim Saraipour, Zimin Zhang, Himabindu Lakkaraju, Yizhou Sun, Shichang Zhang <em>(*equal contribution)</em></p>
    <p class="pub-desc">Studied how post-training reshapes LLMs on knowledge storage, truthfulness, refusal and confidence, using causal tracing, linear probing and entropy neurons.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2504.02904" class="pub-btn primary" target="_blank" rel="noopener">Preprint</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-thumb">
    <img src="/images/strategist-fig.png" alt="Strategist figure">
  </div>
  <div class="pub-body">
    <div class="pub-venue-badge">
      <span class="pub-venue">ICLR 2025</span>
    </div>
    <p class="pub-title">Strategist: Learning Strategic Skills by LLMs via Bi-Level Tree Search</p>
    <p class="pub-authors">Jonathan Light, <strong>Min Cai</strong>, Weiqin Chen, Guanzhi Wang, Xiusi Chen, Wei Cheng, Yisong Yue, Ziniu Hu</p>
    <p class="pub-venue-text">International Conference on Learning Representations (ICLR 2025) · Covered by <em>State of AI Report 2024</em></p>
    <p class="pub-desc">Strategist uses LLMs to acquire new strategic skills for multi-agent games through a bi-level tree search self-improvement process.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2408.10635" class="pub-btn primary" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/jonathanmli/Avalon-LLM/" class="pub-btn" target="_blank" rel="noopener">Code</a>
      <a href="https://llm-strategist.github.io" class="pub-btn" target="_blank" rel="noopener">Website</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-thumb">
    <img src="/images/selfcontrol-fig.png" alt="SelfControl figure">
  </div>
  <div class="pub-body">
    <div class="pub-venue-badge">
      <span class="pub-venue">ICML 2024 Workshop</span>
    </div>
    <p class="pub-title">Self-Control of LLM Behaviors by Compressing Suffix Gradient into Prefix Controller</p>
    <p class="pub-authors"><strong>Min Cai</strong>, Yuchen Zhang, Shichang Zhang, Fan Yin, Dan Zhang, Difan Zou, Yisong Yue, Ziniu Hu</p>
    <p class="pub-venue-text">Foundation Models in the Wild &amp; Mechanistic Interpretability Workshop, ICML 2024</p>
    <p class="pub-desc">An inference-time LLM control method that leverages self-evaluation to steer model behaviors through representation engineering.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2406.02721" class="pub-btn primary" target="_blank" rel="noopener">Preprint</a>
      <a href="https://github.com/HenryCai11/LLM-Self-Control" class="pub-btn" target="_blank" rel="noopener">Code</a>
      <a href="https://llm-self-control.github.io" class="pub-btn" target="_blank" rel="noopener">Website</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-thumb">
    <img src="/images/avalonbench-fig.png" alt="AvalonBench figure">
  </div>
  <div class="pub-body">
    <div class="pub-venue-badge">
      <span class="pub-venue">NeurIPS 2023 Workshop</span>
    </div>
    <p class="pub-title">AvalonBench: Evaluating LLMs Playing the Game of Avalon</p>
    <p class="pub-authors">Jonathan Light*, <strong>Min Cai*</strong>, Sheng Shen, Ziniu Hu <em>(*equal contribution)</em></p>
    <p class="pub-venue-text">Foundation Models for Decision Making Workshop, NeurIPS 2023</p>
    <p class="pub-desc">A benchmark exploring the potential of LLM agents in Resistance Avalon, a strategic social deduction game requiring reasoning and coalition building.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2310.05036" class="pub-btn primary" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/jonathanmli/Avalon-LLM/" class="pub-btn" target="_blank" rel="noopener">Code</a>
      <a href="https://avalonbench.github.io" class="pub-btn" target="_blank" rel="noopener">Website</a>
    </div>
  </div>
</div>

</div>

# Beyond Academics

In my spare time, I enjoy playing and listening to music — jazz, classical, R&B, and more. I also play the Pokémon Trading Card Game (PTCG) and love exploring new foods.
