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

<p class="about-greeting">👋 I'm Linli Shi <span class="zh-name">「史林立」</span></p>

I am a master's student at Johns Hopkins University, working with Prof. [Ziyun (Claude) Wang](https://ziyunclaudewang.github.io) in the [SPIKE Lab](https://github.com/spikelab-jhu). My current research interests include event-based vision, 3D vision, and robotics. To enable robots to reliably perceive and act in the fast-paced, dynamic real world is one of my research goals.

Before joining JHU, I received a dual degree in Computer Science: a BSc from the University of Birmingham and a BEng from Central South University. At the University of Birmingham, I worked with Prof. [Hyung Jin Chang](https://cvlab-uob.github.io/) and Dr. [Yihua Cheng](https://www.yihua.zone) on gaze estimation.

Outside research, I'm an SCA-certified barista and specialty coffee nerd ☕️. Happy to chat over a pour-over!


# 🔥 News
- *2026.07*: &nbsp;We’re open-sourcing an [Isaac Sim Event Camera Plugin](https://github.com/spikelab-jhu/isaac-sim-event-camera-plugin): plug-and-play, real-time, and highly configurable.


# 📝 Publications
Very soon. Really, very soon.

# 🧩 Projects

<div class='paper-box'><div class='paper-box-image'><div><img src='images/simulator-small.gif' alt="Isaac Sim Event Camera Plugin" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Isaac Sim Event Camera Plugin**

**Linli Shi**, Ruijun Zhang, [Ziyun Wang](https://ziyunclaudewang.github.io)

<a href="https://github.com/spikelab-jhu/isaac-sim-event-camera-plugin">[<i class="fab fa-github"></i> <b>Code</b>]</a>
- A high-rate event camera simulation plugin in [Isaac Sim](https://developer.nvidia.com/isaac/sim?size=n_6_n&sort-field=featured&sort-direction=desc), generating fully-labeled event streams directly inside the physics simulator.

- Use motion vectors to interpolate frames, achieving real-time event generation.
- Support sensor noise and motion blur models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/rtdnet.png' alt="RTDNet" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RTDNet: A Recurrent Network using Temporal Difference for Video Gaze Estimation**

**Linli Shi**, [Hyung Jin Chang](https://cvlab-uob.github.io/), [Yihua Cheng](https://www.yihua.zone)

*Undergraduate capstone project — awarded Outstanding Final Year Project, UoB*

<a href="https://github.com/indexss/RTDNet">[<i class="fab fa-github"></i> <b>Code</b>]</a>
- A recurrent network that alternates between spatial and temporal feature processing for high-precision video gaze estimation.
- PDA Loss aligns predicted gaze trajectories with ground truth, moving beyond per-frame point consistency.
</div>
</div>

<div class='paper-box project-box--text-only'>
<div class='paper-box-text' markdown="1">

**Backseat**

**Linli Shi**, Abigail Pain, Hao Li, Yunfan Song, Ella Gardner, Xuanwei Shi, Joe Penny

<a href="https://github.com/indexss/Backseat">[<i class="fab fa-github"></i> <b>Code</b>]</a>
- A Spring Boot + Angular web application that augments Spotify with user-driven ratings, reviews, leaderboards, and social music discovery.
</div>
</div>

# 🎖 Honors
- *2023-2024* Dean's List, University of Birmingham
- *2023, 2024* University of Birmingham Entrance Scholarship
- ☕️ *2025.09* [SCA Brewing Intermediate](https://www.reyachcoffee.com/en/), Specialty Coffee Association

# 📖 Educations
- *2025.01 - Now*, Johns Hopkins University, MSE Electrical and Computer Engineering
- *2023.09 - 2025.06*, University of Birmingham, BSc Computer Science
- *2021.09 - 2025.06*, Central South University, BEng Computer Science

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 💻 Experience
- *2025.01 - 2025.05*, Teaching Assistant of 30205 Team Project AI @ [UoB](https://github.com/uob-dbwp)
- *2023.12 - 2024.01*, Software Engineer Intern @ [hibretOne-CIC](https://platform.hibretone.org)
- *2022.09 - 2025.06*, Technical Consultant @ [Apple Lab (iOS Club), CSU](https://www.csuios.club)
- *2022.09 - 2025.06*, Member @ Open Source Association, CSU
- ☕️ *2025.10 - 2025.12*, Barista @ [Seesaw Coffee](http://www.seesaw-coffee.cn), Taiyuan
