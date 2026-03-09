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

I am currently a Ph.D. student at the School of Computer Science, Northwestern Polytechnical University, supervised by [Prof. Zhu Wang(王柱)](https://jszy.nwpu.edu.cn/wangzhu.html). My research interests include mmWave sensing and wireless sensing foundation model.

*☀️☀️☀️ Special thanks to Prof. Zhiwen Yu(於志文), Prof. Bin Guo(郭斌), and Prof. Zhuo Sun(孙卓) for their guidance. I also appreciate the collaboration and support from my co-authors: Wenchao Song(宋文超), Qian Qin(秦谦), Yangqian Lei(雷杨倩), Dongliang Ma(马栋梁), and Qiwen Gan(甘琪文).*

# 🔥 News
<div class="news-scroll-box" markdown="1">

- *2025.12*: Invited to serve as a reviewer for IEEE Transactions on Mobile Computing.
- *2025.11*: Invited to serve as a reviewer for IEEE Transactions on Human-Machine Systems.
- *2025.11*: Invited to serve as a reviewer for ACM UbiComp/IMWUT.
- *2025.07*: 🎉🎉 2 papers accepted to ACM UbiComp/IMWUT 2025!
- *2025.07*: 🎉🎉 1 paper accepted to IEEE Transactions on Mobile Computing!
- *2025.04*: Join the Program Committee for MobiCom 2025 Artifact Evaluation. 
- *2025.02*: 🔥🔥 We have released a [mmWave radar dataset for 3D in-air handwritten words](https://www.kaggle.com/datasets/mmpencil/mmpencil-dataset/data).
- *2024.10*: Invited to serve as a reviewer for IEEE Internet of Things Journal.
- *2024.06*: Invited to serve as a reviewer for ACM UbiComp/ISWC 2024, Posters and Demos track.
- *2023.10*: 🎉🎉 1 paper accepted to ACM UbiComp/IMWUT 2024!

</div>

# 📝 Publications 


## 📡 mmWave Sensing 

<div class="pub-item" onclick="window.open('https://dl.acm.org/doi/10.1145/3749504', '_blank');" style="cursor: pointer;">
<span class="badge">UbiComp/IMWUT 2025</span> 
<span style="color: red; font-style: italic; font-weight: bold; font-size: 0.90em; vertical-align: middle;">(CCF-A)</span> <br>
<em>mmPencil: Toward Writing-Style-Independent In-Air Handwriting Recognition via mmWave Radar and Large Vision-Language Model.</em> <br>
<span class="highlight-author">Yifan Guo</span>, Zhu Wang, Qian Qin, Yangqian Lei, Qiwen Gan, Zhuo Sun, Chao Chen, Bin Guo, Zhiwen Yu. <br>
<a href="https://github.com/1YifanGuo/mmPencil" onclick="event.stopPropagation();" style="font-size: 1.3em;">💻</a>  
<a href="https://www.kaggle.com/datasets/mmpencil/mmpencil-dataset/data" onclick="event.stopPropagation();" style="font-size: 1.3em;">💾</a>
</div>

<div class="pub-item" onclick="window.open('https://ieeexplore.ieee.org/abstract/document/11072920', '_blank');" style="cursor: pointer;">
<span class="badge">IEEE TMC</span> 
<span style="color: red; font-style: italic; font-weight: bold; font-size: 0.90em; vertical-align: middle;">(CCF-A)</span> <br>
<em>MultiScanner: Enabling Simultaneous Detection of Multiple Liquids with mmWave Radar Based on a Composite Reflection Model.</em> <br>
<span class="highlight-author">Yifan Guo</span>, Zhu Wang, Zhihui Ren, Wei Xu, Yangqian Lei, Qian Qin, Zhuo Sun, Chao Chen, Bin Guo, Zhiwen Yu, Daqing Zhang.
</div>

<div class="pub-item" onclick="window.open('https://dl.acm.org/doi/pdf/10.1145/3631443', '_blank');" style="cursor: pointer;">
<span class="badge">UbiComp/IMWUT 2024</span>
<span style="color: red; font-style: italic; font-weight: bold; font-size: 0.90em; vertical-align: middle;">(CCF-A)</span> <br>
<em>Liqdetector: enabling container-independent liquid detection with mmwave signals based on a dual-reflection model.</em> <br>
Zhu Wang, <span class="highlight-author">Yifan Guo</span>, Zhihui Ren, Wenchao Song, Zhuo Sun, Chao Chen, Bin Guo, Zhiwen Yu.
</div>

## 🛜 Wi-Fi Sensing

<div class="pub-item" onclick="window.open('https://dl.acm.org/doi/10.1145/3749506', '_blank');" style="cursor: pointer;">
<span class="badge">UbiComp/IMWUT 2025</span>
<span style="color: red; font-style: italic; font-weight: bold; font-size: 0.90em; vertical-align: middle;">(CCF-A)</span> <br>
<em>AdaptTrack: A Robust Tracking System for Complex Environments Based on Wi-Fi Device Selection Strategy.</em> <br>
Dongliang Ma, Zhuo Sun, Zhiqiang Wei, <span class="highlight-author">Yifan Guo</span>, Yangqian Lei, Zhu Wang, Zhiwen Yu, Bin Guo.
</div>

<div class="pub-item" onclick="window.open('https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10787125', '_blank');" style="cursor: pointer;">
<span class="badge">IEEE TMC</span>
<span style="color: red; font-style: italic; font-weight: bold; font-size: 0.90em; vertical-align: middle;">(CCF-A)</span> <br>
<em>FinerSense: a Fine-grained Respiration Sensing System Based on Precise Separation of Wi-Fi Signals.</em> <br>
Wenchao Song, Zhu Wang, <span class="highlight-author">Yifan Guo</span>, Zhuo Sun, Zhihui Ren, Chao Chen, Bin Guo, Zhiwen Yu, Xingshe Zhou, Daqing Zhang.
</div>

<div class="pub-item" onclick="window.open('https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10592811', '_blank');" style="cursor: pointer;">
<span class="badge">IEEE TMC</span>
<span style="color: red; font-style: italic; font-weight: bold; font-size: 0.90em; vertical-align: middle;">(CCF-A)</span> <br>
<em>Characterizing the through-wall sensing mechanism of wi-fi signals with a refraction-aware fresnel zone model.</em> <br>
Zhihui Ren, Zhu Wang, Zhuo Sun, <span class="highlight-author">Yifan Guo</span>, Wenchao Song, Hualei Zhang, Chao Chen, Bin Guo, Zhiwen Yu, Xingshe Zhou, Daqing Zhang.
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2024.04 - (now)*, Ph.D. Student, Computer Science and Technology,<br> School of Computer Science, Northwestern Polytechnical University, Xi'an, China. 
- *2021.09 - 2024.04*, M.Eng., Computer Technology,<br> School of Computer Science, Northwestern Polytechnical University, Xi'an, China.
- *2016.09 - 2020.06*, B.Eng., Internet of Things Engineering,<br> School of International Education, Hebei University of Technology, Tianjin, China.

# 💬 Invited Talks
- *2025.10.16*, Paper Session H1: Interaction Techniques II, UbiComp/ISWC 2025, Espoo, Finland.
- *2025.08.24*, PCC Top-Tier Conference and Journal Exchange Papers, HMCC 2025, Dalian, China.
- *2024.10.08*, Paper Session 4B: mmWave, UbiComp/ISWC 2024, Melbourne, Australia.
- *2024.08.20*, PCC Top-Tier Conference and Journal Exchange Papers, HHME 2024, Taiyuan, China.

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->