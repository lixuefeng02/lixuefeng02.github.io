---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<link href='https://fonts.googleapis.com/css?family=Titillium+Web:400,600,400italic,600italic,300,300italic'
    rel='stylesheet' type='text/css'>
<style>

</style>
# About Me
I am Xuefeng Li(李学峰), currently a first-year PhD student at [GAIR Lab](https://plms.ai/), Shanghai Jiao Tong University,advised by Prof. [Pengfei Liu](http://pfliu.com/).

Previously, I obtained my Bachelor Degree at [Beihang University](https://www.buaa.edu.cn/) (BUAA), major in computer science.

## Research Interests
I an general interested in the field of **Large Language Models (LLMs)**. Currently, I am particularly interested in the Large Language Model Reasoning and Planning.

# 🔥 News

<style>  
    .scrollable-area {  
        max-height: 190px;  
        overflow-y: auto;  
        box-shadow: 0 2px 12px rgba(0, 0, 0, 0.08);  /* 更柔和的阴影 */
        padding: 10px 15px;  /* 增加内边距让内容不贴边 */
        color: #333;
        border: 1px solid #e0e0e0;  /* 浅灰色边框 */
        border-radius: 8px;  /* 圆角边框 */
        background-color: #ffffff;  /* 确保背景是白色 */
    }
    /* 设置滚动条的宽度和轨道背景 */
    .scrollable-area::-webkit-scrollbar {
        width: 8px;
    }
    /* 设置滚动条轨道 */
    .scrollable-area::-webkit-scrollbar-track {
        background: #f1f1f1;
        border-radius: 4px;
    }
    /* 设置滚动条滑块 */
    .scrollable-area::-webkit-scrollbar-thumb {
        background: #888;
        border-radius: 4px;
    }

    /* 鼠标悬停在滑块上时的样式 */
    .scrollable-area::-webkit-scrollbar-thumb:hover {
        background: #555;
    }
    .pdf {
        text-decoration: none;
        color: #122c8b;
    }
    .code {
        text-decoration: none;
        color: #122c8b;
    }
    .title{
        color: #374798;
    }
</style>

<div class="scrollable-area" style="width:100%;">
    <ul>
        <li><em>2025.04</em>: 🔥 Say hi to <strong>OctoThinker</strong>, a mid-training ablation study in the era of RL scaling.</li>
        <li><em>2025.03</em>: 🔥 Checkout <strong>ToRL</strong>, tool-integrated RL scaling.</li>
        <li><em>2025.02</em>: 🔥 Checkout <strong>LIMR</strong>, Less is more for RL scaling.</li>
    </ul>  
</div>

<!-- import publications markdown -->
{% include publications.md %}


<!-- # Projects
<div class='paper-box'>
    <div class='paper-box-image'>
        <div><img src='images/openagents_overview.png' alt="sym" width="100%"></div>
    </div>
    <div class='paper-box-text' markdown="1">

[**OpenAgents**](https://github.com/xlang-ai/OpenAgents) (2023) [![](https://img.shields.io/github/stars/xlang-ai/OpenAgents?style=social)](https://github.com/xlang-ai/OpenAgents)

Host your own ChatGPT Plus locally!

- **Data Agent**: code interpreter augmented with data tools
- **Plugins Agent**: 200+ plugins for daily life
- **Web Agent**: autonomous web browsing
</div>
</div> -->

# Exeperiences

- <img src="images/education.png" width=18em style="vertical-align: middle;"> _2020.09 - 2024.06_, B.S.@BUAA, CS.
- <img src="images/education.png" width=18em style="vertical-align: middle;"> _2024.09 - 2029.06_(expected), Ph.D.@SJTU, CS.
<!-- - <img src="images/intern.png" width=18em style="vertical-align: middle;"> _2021.10 - 2022.08_, Intern@MSRA. -->
<!-- - <img src="images/intern.png" width=18em style="vertical-align: middle;"> _2023.09 - 2023.09_, Intern@XLang-HKU. -->
<!-- - <img src="images/intern.png" width=18em style="vertical-align: middle;"> _2024.02 -_, Research Collaborator@Sea AI Lab, Singapore. -->
<!-- - <img src="images/intern.png" width=18em style="vertical-align: middle;"> _2024.01 - 2024.06_, Research Assistant@Shanghai AI Lab, Shanghai. -->
<!-- - <img src="images/intern.png" width=18em style="vertical-align: middle;"> _2024.06 - 2025.04_, Intern@LLM360. -->

