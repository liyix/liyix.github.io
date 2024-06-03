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

Hey there! I am Yixuan, a second-year graduate student at [Department of Computer Science and Engineering](https://cs.seu.edu.cn/main.htm), [Southeast University](https://www.seu.edu.cn/), advisored by Prof. [Wanyuan Wang](https://wanyuanwang.github.io/). My research interest lies in Artificial Intelligence, Reinforcement Learning, Operation Research and Multi-Agent Systems. My research outputs now include 5 publications accepted, 2 pending submissions, and one granted patent. Previously, I obtained my bachelor’s degrees in [Computer Science](https://cs.njupt.edu.cn/) from [Nanjing University of Posts and Telecommunications](https://www.njupt.edu.cn/) in 2022, fortunately working with Dr. [Kang Xu](https://xk57238890.github.io/). Here is my [CV](https://liyix.github.io/images/Yixuan_Li_CV.pdf) and the [chinese version](https://liyix.github.io/images/Chinese%20Version.pdf). Contact me through [yixuanli@seu.edu.cn](mailto:yixuanli@seu.edu.cn).


# 🔥 News
- *2023.11*: &nbsp;🎉🎉 One [paper](https://liyix.github.io/images/aamas24.pdf) accepted by [AAMAS'24](https://www.aamas2024-conference.auckland.ac.nz/accepted/papers/) as a full paper. 
- *2023.07*: &nbsp;🎉🎉 We win [Huawei Spark Award - Value Prize](https://www.chaspark.com/#/questions/sparks/900903102629404672) for [Challenging Problems](https://www.chaspark.com/#/questions/820504253384495104?sub=820506234689818624)! 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAMAS 2024</div><img src='images/aamas24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Factor Graph Neural Network Meets Max-Sum: A Real-Time Route Planning Algorithm for Massive-Scale Trips.](https://dl.acm.org/doi/10.5555/3635637.3662973)** [📄paper](https://liyix.github.io/images/aamas24.pdf) [📹slides](https://liyix.github.io/images/AAMAS_presentation.pdf) [📌poster](https://liyix.github.io/images/AAMAS_Poster.pdf)

**Yixuan Li**, Wanyuan Wang*, Weiyi Xu, Yanchen Deng, Weiwei Wu.

Proceedings of the 23rd International Conference on Autonomous Agents and Multiagent Systems ([AAMAS’24](https://www.aamas2024-conference.auckland.ac.nz/)).

- Designed a novel modeling approach: the Path-Query Factor Graph for the global path planning problem;
- Proposed a hybrid pruning technique to accelerate the Max-Sum algorithm in different traffic conditions;
- developed an end-to-end, real-time response framework based on the factor graph neural networks. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MSN 2023</div><img src='images/msn23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Decentralized Subgoal Tree Search for Multi-agent Planning without Priors or Communication.** [📄paper](https://liyix.github.io/images/msn23.pdf)

Qian Che, **Yixuan Li**, Ziyao Peng, Wanyuan Wang*, Yichuan Jiang.

Proceedings of the 19th International Conference on Mobility, Sensing and Networking ([MSN'23](https://ieee-msn.org/2023/)).

- Improved the distributed tree search algorithm by upstream planning to automatic extract sub-goals;
- Introduced an expectation alignment technique to extend the algorithm to non-communication scenarios.
</div>
</div>
  
- **A Multi-agent Based Method for Large-Scale Route Planning Using Distributed Constraint Optimization.**  
  **Yixuan Li**, Qian Che, Fengchen Wang, Yifeng Zhou, Chuanyou Li, Wanyuan Wang*  
  The 6th IEEE International Conference on Unmanned Systems (ICUS'23).  

- **Explicit Coordination Based Multi-Agent Reinforcement Learning for Intelligent Traffic Signal Control.**  
  **Yixuan Li**, Qian Che, Yifeng Zhou, Wanyuan Wang*, Yichuan Jiang.  
  The 18th CCF Conference on Computer Supported Cooperative Work and Social Computing (ChineseCSCW).  

- **A Multi-agent Based Method for Large-Scale Route Planning Using Distributed Constraint Optimization.**  
  **Yixuan Li**, Qian Che, Fengchen Wang, Huiying Zhang, Wanyuan Wang*, Yichuan Jiang.   
  The 18th CCF Conference on Computer Supported Cooperative Work and Social Computing (ChineseCSCW).  

- **A Method for Fault Root Cause Localization Based on Network Topology and Real-Time Alarms.**  
  Kang Xu, **Yixuan Li**, Haiqi Liu, Xiaowei Zhang, Ning Ye, Ruchuan Wang.  
  China Invention Patent No. CN112181758B, Granted on 2023.

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

# 💼 Projects
- *2023.01 - 2023.07*, **Accelerating Large-Scale Supply Chain Problem Solving**  
  *[Huawei](https://www.huawei.com/) Technologies Co., Ltd., Shenzhen, China*
  - Developed a solver acceleration method based on problem reduction for large-scale (integer) linear programming, predicted integers and identified active constraints to reduce the number of redundant constraints for a rapid solution.
  - Reduced solution time to milliseconds on Huawei's supply chain scheduling instances while ensuring 99% fidelity.
  - By integrating the solver's warm start technology, achieved over ten times speed improvement on average compared to CPLEX under the same solution gap, winning the Huawei Spark Award - Value Prize.
- *2022.09 - 2022.12*, **Optimization of Data Center Cooling System**  
  *[China Mobile](https://10086.cn/) Communications Group Co.,Ltd, Wuxi, China*
  - Trained a thermodynamic model of the cooling system using GNN and the relationship of the units.
  - Designed a DRL-based control algorithm for data center cooling systems by DDPG combined with imitation learning.
  - Test results showed a total power usage effectiveness (PUE) reduction of 35% compared to the original scheme, successfully deployed at the China Mobile Wuxi Data Center.
- *2020.06 - 2022.06*, **Anomaly Detection and Root Cause Localization in Intelligent Operations**  
  *State Key Laboratory of Smart Grid Protection and Operation Control, [NARI](http://www.sgepri.sgcc.com.cn/) Group, Nanjing, China*
  - Designed a suite of anomaly detection algorithms based on statistical modeling, machine learning, and deep learning for multivariate time series anomaly detection. Techniques applied include GNN, Transformer, GAN, Mask, etc.
  - Contributed to two papers and one patent, with both papers accepted by SCI-JCR Q2 journals.

# 💻 Internships
- *2024.07 (upcoming)*, [Noah’s Ark Lab](https://www.noahlab.com.hk/#/home), Huawei Technologies, Shenzhen, China.

# ⚽ Personality and Interests
- Enjoy teamwork!
- Love music and football, my favorite band is The Stone Roses.
