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
- **[2026-07]** ✨ [EVIS v1.0](https://github.com/spikelab-jhu/isaac-sim-event-camera-plugin) is now available, bringing HDR support, configurable sensor noise, motion blur, anti-aliasing controls, and a PyTorch dataloader for streamlined downstream training. See our [technical report](https://arxiv.org/abs/2607.08098) for details.


# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><img src='images/simulator-small.gif' alt="Isaac Sim Event Camera Plugin" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**EVIS: A Physics-Grounded Event Camera Plugin for NVIDIA Isaac Sim**

**Linli Shi**, Ruijun Zhang, [Ziyun Wang](https://ziyunclaudewang.github.io)

*arXiv preprint, 2026*

<a href="https://github.com/spikelab-jhu/isaac-sim-event-camera-plugin">[<img class="brand-icon" src="images/github.svg" alt=""> <b>Code</b>]</a>
<a href="https://arxiv.org/abs/2607.08098">[<span class="paper-emoji">📄</span> <b>Paper</b>]</a>
- A physics-grounded event camera simulation platform for [NVIDIA Isaac Sim](https://developer.nvidia.com/isaac/sim?size=n_6_n&sort-field=featured&sort-direction=desc), bridging realistic event generation, controlled benchmarking, and downstream learning.
- Supports event generation from linear intensity before gamma correction, realistic sensor noise, motion-blurred rendering, and anti-aliased rendering and warping.
- Provides a PyTorch-native dataloader for multiple event representations, with evaluations on frame reconstruction, optical flow, and pose estimation.
</div>
</div>

# 🧩 Projects

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
