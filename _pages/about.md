---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Min Cai (蔡旻). I'm an M.S. student graduated from Shenzhen University, where I was supervised by <a href="https://hdzhangust.github.io" style="text-decoration: none; color: #0366d6; transition: color 0.3s;">Prof. Haodi Zhang</a>. Before that, I obtained my B.A. in Translation from Beijing Language and Culture University. Currently, I'm interning at Zhipu AI, mentored by <a href="https://zhangdan0602.github.io" style="text-decoration: none; color: #0366d6; transition: color 0.3s;">Dr. Dan Zhang</a>. Meanwhile, I also work closely with <a href="https://acbull.github.io" style="text-decoration: none; color: #0366d6; transition: color 0.3s;">Dr. Ziniu Hu</a>, <a href="https://shichangzh.github.io" style="text-decoration: none; color: #0366d6; transition: color 0.3s;">Dr. Shichang Zhang</a>, and <a href="https://difanzou.github.io" style="text-decoration: none; color: #0366d6; transition: color 0.3s;">Dr. Difan Zou</a>.

I have broad interests in NLP, particularly in understanding the mechanisms of neural language models (LMs) and, in turn, contributing to a better understanding of human nature and benefiting societal good.

Specifically, my current research focuses on:
- **LLM understanding** (mechanistic interpretability, e.g., <a href="https://llm-self-control.github.io" style="text-decoration: none; color: #0366d6; transition: color 0.3s;">SelfControl</a>) and **evaluation** (e.g., <a href="https://avalonbench.github.io" style="text-decoration: none; color: #0366d6; transition: color 0.3s;">AvalonBench</a> and DataSciBench).
- **LLM control/alignment** using representation engineering (e.g., <a href="https://llm-self-control.github.io" style="text-decoration: none; color: #0366d6; transition: color 0.3s;">SelfControl</a>).
- **LLM game agents** that are capable of solving complex tasks (e.g., <a href="https://llm-strategist.github.io" style="text-decoration: none; color: #0366d6; transition: color 0.3s;">Strategist</a>).


## Selected Publications

<!-- Text and Buttons Section -->
<div>
  <h3>AvalonBench: Evaluating LLMs Playing the Game of Avalon</h3>
  <p>
    Jonathan Light*, <b>Min Cai*</b>, Sheng Shen, Ziniu Hu (*equal contribution)
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/jonathanmli/Avalon-LLM?logo=github&style=flat-square">
  </p>
  <p>
    <a href="https://github.com/jonathanmli/Avalon-LLM/" target="_blank" style="text-decoration:none;">
      <button style="padding:6px 6px; background-color:#0366d6; color:white; border:none; border-radius:3px; font-size:13px; font-weight:bold; cursor:pointer; transition: background-color 0.3s;">
        Code
      </button>
    </a>
    <a href="https://arxiv.org/abs/2310.05036" target="_blank" style="text-decoration:none;">
      <button style="padding:6px 6px; background-color:#0366d6; color:white; border:none; border-radius:3px; font-size:13px; font-weight:bold; cursor:pointer; transition: background-color 0.3s;">
        Paper
      </button>
    </a>
    <a href="https://avalonbench.github.io" target="_blank" style="text-decoration:none;">
      <button style="padding:6px 6px; background-color:#0366d6; color:white; border:none; border-radius:3px; font-size:13px; font-weight:bold; cursor:pointer; transition: background-color 0.3s;">
        Website
      </button>
    </a>
  </p>
  <div style="display: flex; align-items: center;">
    <!-- Figure Section -->
    <div style="flex-shrink: 0; margin-right: 15px;">
      <img src="../images/avalonbench-fig.png" alt="AvalonBench Figure" style="max-width: 350px; border-radius: 8px;">
    </div>
    <div>
      <p>AvalonBench is a benchmark that explores the potential of Large Language Models (LLMs) Agents in playing the strategic social deduction game, Resistance Avalon.
      </p>
    </div>
  </div>
</div>

----

<!-- Figure Section -->
<div>
  <h3>Self-Control of LLM Behaviors by Compressing Suffix Gradient into Prefix Controller</h3>
  <p>
    <b>Min Cai</b>, Yuchen Zhang, Shichang Zhang, Fan Yin, Dan Zhang, Difan Zou, Yisong Yue, Ziniu Hu
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/HenryCai11/LLM-Self-Control?logo=github&style=flat-square">
  </p>
  <p>
    <a href="https://github.com/HenryCai11/LLM-Self-Control" target="_blank" style="text-decoration:none;">
      <button style="padding:6px 6px; background-color:#0366d6; color:white; border:none; border-radius:3px; font-size:13px; font-weight:bold; cursor:pointer; transition: background-color 0.3s;">
        Code
      </button>
    </a>
    <a href="https://arxiv.org/abs/2406.02721" target="_blank" style="text-decoration:none;">
      <button style="padding:6px 6px; background-color:#0366d6; color:white; border:none; border-radius:3px; font-size:13px; font-weight:bold; cursor:pointer; transition: background-color 0.3s;">
        Preprint
      </button>
    </a>
    <a href="https://llm-self-control.github.io" target="_blank" style="text-decoration:none;">
      <button style="padding:6px 6px; background-color:#0366d6; color:white; border:none; border-radius:3px; font-size:13px; font-weight:bold; cursor:pointer; transition: background-color 0.3s;">
        Website
      </button>
    </a>
  </p>
  <div style="display: flex; align-items: center;">
    <!-- Image Section -->
    <div style="flex-shrink: 0; margin-right: 15px;">
      <img src="../images/selfcontrol-fig.png" alt="SelfControl Figure" style="max-width: 350px; border-radius: 8px;">
    </div>
    <!-- Text Section -->
    <div>
      <p>
        SelfControl is an inference time LLM control method that leverages LLM self-evaluation to control model behaviors through representation engineering.
      </p>
    </div>
  </div>
</div>

----
<!-- Text and Buttons Section -->
<div>
  <h3>Strategist: Learning Strategic Skills by LLMs via Bi-Level Tree Search</h3>
  <p>
    Jonathan Light, <b>Min Cai</b>, Weiqin Chen, Guanzhi Wang, Xiusi Chen, Wei Cheng, Yisong Yue, Ziniu Hu
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/jonathanmli/Avalon-LLM?logo=github&style=flat-square">
  </p>
  <p>
    <a href="https://github.com/jonathanmli/Avalon-LLM/" target="_blank" style="text-decoration:none;">
      <button style="padding:6px 6px; background-color:#0366d6; color:white; border:none; border-radius:3px; font-size:13px; font-weight:bold; cursor:pointer; transition: background-color 0.3s;">
        Code
      </button>
    </a>
    <a href="https://arxiv.org/abs/2408.10635" target="_blank" style="text-decoration:none;">
      <button style="padding:6px 6px; background-color:#0366d6; color:white; border:none; border-radius:3px; font-size:13px; font-weight:bold; cursor:pointer; transition: background-color 0.3s;">
        Preprint
      </button>
    </a>
    <a href="https://llm-strategist.github.io" target="_blank" style="text-decoration:none;">
      <button style="padding:6px 6px; background-color:#0366d6; color:white; border:none; border-radius:3px; font-size:13px; font-weight:bold; cursor:pointer; transition: background-color 0.3s;">
        Website
      </button>
    </a>
  </p>
  <div style="display: flex; align-items: center;">
    <!-- Figure Section -->
    <div style="flex-shrink: 0; margin-right: 15px;">
      <img src="../images/strategist-fig.png" alt="Strategist Figure" style="max-width: 200px; border-radius: 8px;">
    </div>
    <div>
      <p>Strategist is an advanced game agent that utilizes LLMs to acquire new skills for playing multi-agent games through a self-improvement process.</p>
    </div>
  </div>
</div>