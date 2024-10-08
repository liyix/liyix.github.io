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

Hey there! I am Yixuan, a second-year graduate student at [Department of Computer Science and Engineering](https://cs.seu.edu.cn/main.htm), [Southeast University](https://www.seu.edu.cn/), advisored by Prof. [Wanyuan Wang](https://wanyuanwang.github.io/). My research interest lies in Reinforcement Learning, Operation Research and Multi-Agent Systems. Previously, I obtained my bachelor’s degrees in [Computer Science](https://cs.njupt.edu.cn/) from [Nanjing University of Posts and Telecommunications](https://www.njupt.edu.cn/) in 2022, fortunately working with Dr. [Kang Xu](https://xk57238890.github.io/). Contact me through [yixuanli@seu.edu.cn](mailto:yixuanli@seu.edu.cn).



# 🔥 News
- *2023.11*: &nbsp;🎉🎉 One [paper](https://liyix.github.io/images/aamas24.pdf) accepted by [AAMAS'24](https://www.aamas2024-conference.auckland.ac.nz/accepted/papers/) as a full paper. 
- *2023.07*: &nbsp;🎉🎉 We win [Huawei Spark Award - Value Prize](https://www.chaspark.com/#/questions/sparks/900903102629404672) for [Challenging Problems](https://www.chaspark.com/#/questions/820504253384495104?sub=820506234689818624)! 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAMAS 2024</div><img src='images/aamas24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Factor Graph Neural Network Meets Max-Sum: A Real-Time Route Planning Algorithm for Massive-Scale Trips.](https://dl.acm.org/doi/10.5555/3635637.3662973)** [📄paper](https://liyix.github.io/images/aamas24.pdf) [📹slides](https://liyix.github.io/images/AAMAS_presentation.pdf) [📌poster](https://liyix.github.io/images/AAMAS_Poster.pdf)

**Yixuan Li**, Wanyuan Wang*, Weiyi Xu, Yanchen Deng, Weiwei Wu.

Proceedings of the 23rd International Conference on Autonomous Agents and Multiagent Systems ([AAMAS’24](https://www.aamas2024-conference.auckland.ac.nz/),CORE Rank A*/CCF B).

- Designed a novel modeling approach: the Path-Query Factor Graph for the global path planning problem;
- Proposed a hybrid pruning technique to accelerate the Max-Sum algorithm in different traffic conditions;
- developed an end-to-end, real-time response framework based on the factor graph neural networks. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TST</div><img src='images/TST.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Multiagent Reinforcement Learning-Based Flow Splitting for Network Packet Routing.** [📄paper](https://liyix.github.io/images/TST.pdf)

Qian Che†, **Yixuan Li†**, Yijing Wang*, Haoran Chen, Wanyuan Wang, Weiwei Wu*.

Tsinghua Science and Technology ([TST](https://www.sciopen.com/journal/1007-0214?stage=1),SCI-Q1, Impact Factor:5.2).

- Developed a novel multiagent modeling approach by representing traffic demand as agents;
- Designed an attention-based pointer network to enhance feature extraction. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MSN 2023</div><img src='images/msn23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Decentralized Subgoal Tree Search for Multi-agent Planning without Priors or Communication](https://ieeexplore.ieee.org/abstract/document/10566902).** [📄paper](https://liyix.github.io/images/msn23.pdf)

Qian Che, **Yixuan Li**, Ziyao Peng, Wanyuan Wang*, Yichuan Jiang.

Proceedings of the 19th International Conference on Mobility, Sensing and Networking ([MSN'23](https://ieee-msn.org/2023/),CCF C).

- Improved the distributed tree search algorithm by upstream planning to automatic extract sub-goals;
- Introduced an expectation alignment technique to extend the algorithm to non-communication scenarios.
</div>
</div>
  
- **A Method for Fault Root Cause Localization Based on Network Topology and Real-Time Alarms.**  
  Kang Xu, **Yixuan Li**, Haiqi Liu, Xiaowei Zhang, Ning Ye, Ruchuan Wang.  
  China Invention Patent No. CN112181758B, Granted on 2023.

# 📝 Preprint 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/MILP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Fast and Interpretable Mixed-Integer Linear Program Solving by Learning Model Reduction.** [📄paper](https://liyix.github.io/images/MILP.pdf) [📹slides](https://liyix.github.io/images/MILP_share.pdf) [📌poster](https://liyix.github.io/images/MILP_poster.pdf)

**Yixuan Li**, Can Chen, Jiajun Li, Jiahui Duan, Xiongwei Han, Tao zhong, Vincent Chau, Weiwei Wu, Wanyuan Wang*. 

- Designed an interpretable model parsimonious strategy and a strategy pruning method for MIP;
- Designed an efficient solving method through preference-based reinforcement learning. 
</div>
</div>

- **Shapley Value-based Congestion Attribution: A Practical Multiagent Reinforcement Learning for Traffic Signal Control.** [📄paper](https://liyix.github.io/images/Shapley.pdf) 

  **Yixuan Li†**, Jiajun Li†, Xiao Liu, Weiwei Wu, Wanyuan Wang*.
  
  *Under Review.*

- **Multiagent Reinforcement Learning Method based on Structural Coordination.**  

  **Yixuan Li**, Yi Huang, Junlan Feng, Chao Deng, Chunyu Liu, Vincent Chau, Wanyuan Wang*.
  
  *Under Review.*

- **MicLog: Log Parsing with Meta In-Context Learning.**  

  Jianbo Yu, **Yixuan Li**, Hai Xu, zhijing Li, Kang Xu, Wanyuan Wang*.
  
  *Under Review.*
  

# 🎖 Honors and Awards
- *2023.11* Southeast University, Scholarship. 
- *2023.07* Huawei Spark Award - Value Prize, Major Contributor.
- *2023.01* China Graduate Mathematical Contest in Modeling, National Third Prize
- *2022.11* Southeast University, Scholarship
- *2022.04* Alibaba Cloud Panjiu Intelligent Algorithm Competition, Global Top 3%
- *2021.11* "Challenge Cup" Academic Science and Technology Competition, National First Prize
- *2020.12* Nanjing University of Posts and Telecommunications, Scholarship
- *2020.10* "Yuezuan Cup" Software Design Competition, Third Prize

# 📖 Educations
- *2022.06 - now*, [Department of Computer Science and Engineering](https://cs.seu.edu.cn/main.htm), [Southeast University](https://www.seu.edu.cn/). 
- *2018.09 - 2022.06*, [Department of Computer Science](https://cs.njupt.edu.cn/), [Nanjing University of Posts and Telecommunications](https://www.njupt.edu.cn/). 

# 💻 Internships
- *2024.08 -2025.01*, [Noah’s Ark Lab](https://www.noahlab.com.hk/#/home), Huawei Technologies, Shenzhen, China.
  Advisored by Jiahui Duan and Xiongwei Han, I am deeply grateful to collaborate with them and receive their guidance.

# 💼 Projects
- *2023.01 - 2025.06*, **Data and Knowledge-Driven Optimization Problem Strategies**  
  *[Huawei](https://www.huawei.com/) Technologies Co., Ltd., Shenzhen, China*

- *2022.09 - 2023.12*, **DRL Based Data Center Cooling System Optimization**  
  *[China Mobile](https://10086.cn/) Communications Group Co.,Ltd, Wuxi, China*

- *2020.03 - 2020.09*, **Multi-Agent Coordinated RL Based Traffic Signal Control**  
  *China Computer Federation (CCF)-Tencent Fund, Nanjing, China*

- *2020.01 - 2022.06*, **Anomaly Detection and Root Cause Localization in Intelligent Operations**  
  *State Key Laboratory of Smart Grid Protection and Operation Control, [NARI](http://www.sgepri.sgcc.com.cn/) Group, Nanjing, China*



# ⚽ Personality and Interests
- Enjoy teamwork!
- Love music and football.
