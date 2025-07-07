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

I am currently a Recommendation Algorithm Engineer at Kuaishou Technology. Previously, I obtained my Master's degree in Artificial Intelligence from [Tsinghua University](https://www.tsinghua.edu.cn/), under the supervision of [Prof. Xiu Li](https://scholar.google.com/citations?user=Xrh1OIUAAAAJ) and [Huifeng Guo](https://scholar.google.com/citations?user=jlBcPn8AAAAJ). My research interests lie in the areas of Graph Neural Network, Recommender System, Machine Learning, and Multi-task Learning. Currently, I am mainly working on data mining, information retrieval and recommender systems.

My recent work topics include but are not limited to:
<ul>
    <li>LLM/RL/Uplift4Rec</li>
    <li>Multi-behavior/Multi-scenario/Multi-task/Multi-modal recommendation algorithm</li>
</ul>

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Selected Publications 

$*$ -- -- Co-first author, $\dagger$ -- -- Corresponding author

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2025</div><img src='images/kuaimod.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## VLM as Policy: Common-Law Content Moderation Framework for Short Video Platform.
Xingyu Lu<sup>*</sup>, Tianke Zhang<sup>*</sup>, **<u>Chang Meng</u>**, Xiaobei Wang, Jinpeng Wang, Yifan Zhang, Shisong Tang, Changyi Liu, Haojie Ding, Kaiyu Jiang, Kaiyu Tang, Bin Wen, Haitao Zheng, Fan Yang<sup>$\dagger$</sup>, Tingting Gao, Di Zhang, Kun Gai

<i>Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining</i>, KDD'25, Long Paper, <span style="color:red">Oral</span>, **CCF-A**

[**Paper**](https://arxiv.org/pdf/2504.14904) [**Code**](https://github.com/KuaiMod/KuaiMod.github.io) [**Page Site**](https://kuaimod.github.io.)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/cdum.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Coarse-to-fine Dynamic Uplift Modeling for Real-time Video Recommendation.

**<u>Chang Meng<sup>*</sup></u>**, Chenhao Zhai<sup>*</sup>, Xueliang Wang, Shuchang Liu, Xiaoqiang Feng, Lantao Hu<sup>$\dagger$</sup>, Xiu Li<sup>$\dagger$</sup>, Han Li<sup>$\dagger$</sup>, Kun Gai

<i>Proceedings of the 19th ACM Conference on Recommender Systems</i>, RecSys'25, Full Paper, <span style="color:red">Oral</span>, **CCF-B**

[**Paper**](https://arxiv.org/pdf/2410.16755) [**Code**](https://github.com/UpliftVideo/CDUM)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2025</div><img src='images/KDD2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Combinatorial Optimization Perspective based Framework for Multi-behavior Recommendation.

Chenhao Zhai<sup>*</sup>, **<u>Chang Meng<sup>*</sup></u>**, Yu Yang, Kexin Zhang, Xuhao Zhao, Xiu Li<sup>$\dagger$</sup>

<i>Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining</i>, KDD'25, Long Paper, <span style="color:red">Oral</span>, **CCF-A**

[**Paper**](https://arxiv.org/pdf/2502.02232) [**Code**](https://github.com/MC-CV/COPF)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2023</div><img src='images/CIKM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Parallel Knowledge Enhancement based Framework for Multi-behavior Recommendation.

**<u>Chang Meng<sup>*</sup></u>**, Chenhao Zhai<sup>*</sup>, Yu Yang, Hengyu Zhang, Xiu Li<sup>$\dagger$</sup>

<i>Proceedings of the 32nd ACM International Conference on Information & Knowledge Management</i>, CIKM'23, Long Paper, <span style="color:red">Oral</span>, **CCF-B**

[**Paper**](https://doi.org/10.1145/3583780.3615004) [**Code**](https://github.com/MC-CV/PKEF) [**Video**](https://www.bilibili.com/video/BV1o34y1G73a)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOIS 2023</div><img src='images/TOIS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Coarse-to-Fine Knowledge-Enhanced Multi-Interest Learning Framework for Multi-Behavior Recommendation.

<!-- **[Chang Meng](https://scholar.google.com/citations?user=0yh3nS8AAAAJ)<sup>*</sup>**, Ziqi Zhao<sup>*</sup>, [Wei Guo](https://scholar.google.com/citations?user=9NGhGNgAAAAJ), [Yingxue Zhang](https://scholar.google.com/citations?user=4bsYpogAAAAJ), [Haolun Wu](https://scholar.google.com/citations?user=-KcBDLcAAAAJ), [Chen Gao](https://scholar.google.com/citations?user=Af60_cEAAAAJ), [Dong Li](https://dblp.org/pid/47/4826-16.html), [Xiu Li](https://scholar.google.com/citations?user=Xrh1OIUAAAAJ)<sup>$\dagger$</sup>, [Ruiming Tang](https://scholar.google.com/citations?user=fUtHww0AAAAJ)<sup>$\dagger$</sup> -->

**<u>Chang Meng<sup>*</sup></u>**, Ziqi Zhao<sup>*</sup>, Wei Guo, Yingxue Zhang, Haolun Wu, Chen Gao, Dong Li, Xiu Li<sup>$\dagger$</sup>, Ruiming Tang<sup>$\dagger$</sup>

<i>ACM Transactions on Information Systems</i>, TOIS'23, Research-Article, **CCF-A**       

[**Paper**](https://doi.org/10.1145/3606369) [**Code**](https://github.com/MC-CV/CKML)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2023</div><img src='images/KDD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Hierarchical Projection Enhanced Multi-behavior Recommendation.

**<u>Chang Meng<sup>*</sup></u>**, Hengyu Zhang<sup>*</sup>, Wei Guo, Huifeng Guo, Haotian Liu, Yingxue Zhang, Hongkun Zheng, Ruiming Tang<sup>$\dagger$</sup>, Xiu Li<sup>$\dagger$</sup>, Rui Zhang

<i>Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining</i>, KDD'23, Long Paper, <span style="color:red">Oral</span>, **CCF-A**

[**Paper**](https://doi.org/10.1145/3580305.3599838) [**Code**](https://github.com/MC-CV/HPMR) [**Video**](https://www.bilibili.com/video/BV1wj411r74B)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2023</div><img src='images/WWW.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Compressed Interaction Graph based Framework for Multi-behavior Recommendation.
**(first student author, supervised by Wei Guo)**

Wei Guo<sup>*</sup>, **<u>Chang Meng<sup>*</sup></u>**, Enming Yuan, Zhicheng He, Huifeng Guo, Yingxue Zhang, Bo Chen, Yaochen Hu, Ruiming Tang<sup>$\dagger$</sup>, Xiu Li<sup>$\dagger$</sup>, Rui Zhang

<i>Proceedings of the ACM Web Conference 2023</i>, WWW'23, Long Paper, <span style="color:red">Oral</span>, **CCF-A**

[**Paper**](https://doi.org/10.1145/3543507.3583312) [**Code**](https://github.com/MC-CV/CIGF) [**Video**](https://www.bilibili.com/video/BV1Pv4y1W7Zx)
</div>
</div>

**Patent**: [CN116881578A](https://patents.google.com/patent/CN116881578A), [CN116523587A](https://patents.google.com/patent/CN116523587A), [CN116186382A](https://patents.google.com/patent/CN116186382A)


# 🎖 Honors and Awards
  - *2023*  National Scholarship of Tsinghua University
  - *2022*  Second-class Scholarship of Tsinghua University
  - *2021*  Graduation Gold List - Personality Development Star (the only one in the university)
  - *2021*  Outstanding graduates
  - *2019*  National Scholarship
  - *2018*  National Scholarship
  - *2018*  Provincial merit students

# 🏆 Competition Prizes
  - *2021*  <i> Rank 10/177</i>  of Megvii AI intelligent transportation open source track
  - *2019*  <i> National Finals Special Prize</i>  of “Siemens Cup” China Intelligent Manufacturing Contest
  - *2019*  <i> Provincial Special Prize</i> of “Siemens Cup” China Intelligent Manufacturing Contest
  - *2019*  <i> Second Prize</i>  of National College Students Mathematical Contest in Modeling (CUMCM)
  - *2018*  <i> First Prize</i>  of National Mathematics Competition for College students
  - *2015*  <i> Gold Medal</i>  of China Southeast Mathematics Olympiad (CSMO)

# 📖 Educations

- *2021.09 -- 2024.06*, Master, Artificial Intelligence, **Tsinghua University**, GPA 3.92/4.00, ranking 10/96.
- *2017.09 -- 2021.06*, Bachelor, Automation, **Harbin Engineering University**, GPA 93.46/100, ranking 1/356.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Working Experience
<div class='image-with-text'><div class='image'><div><img src='images/kuaishou.png' width="100%"></div></div>
<div class='text' markdown="1">
- *2024.01 -- Present*, <i>Recommendation Algorithm Engineer</i>, **Kuaishou**, Community Science, Beijing, China

    Topic: Development of Recommendation algorithm for Kuaishou
    
    Projects: Uplift Modeling
</div>
</div>

<div class='image-with-text'><div class='image'><div><img src='images/WeChat-Logo.png' width="100%"></div></div>
<div class='text' markdown="1">
- *2023.06 -- 2023.08*, <i>Recommendation Algorithm Intern (Summer Intern)</i>, **Tencent**, WeiXin Group, Guangzhou, China

    Topic: Development of CTR algorithm for WeChat
    
    Projects: Search & Recommendation
</div>
</div>

<div class='image-with-text'><div class='image'><div><img src='images/bytedance.png' width="100%"></div></div>
<div class='text' markdown="1">
- *2023.04 -- 2023.06*, <i>Search Algorithm Intern (Byteintern)</i>, **ByteDance**, TikTok, Shanghai, China

    Topic: Development of e-commerce CTR/CVR algorithm for Tiktok

    Projects: Search & Recommendation
</div>
</div>

<div class='image-with-text'><div class='image'><div><img src='images/alibaba-cloud.png' width="100%"></div></div>
<div class='text' markdown="1">
- *2022.12 -- 2023.03*, <i>Research Intern</i>, **Alibaba Group**, Aliyun, Hangzhou, China

    Topic: Research on cloud platform recommendation algorithm

    Projects: Graph Neural Network & Recommendation
</div>
</div>

<div class='image-with-text'><div class='image'><div><img src='images/huawei.png'  width="100%"></div></div>
<div class='text' markdown="1">
- *2021.12 -- 2022.12*, <i>Research Intern</i>, **Huawei**, Noah’s Ark Lab, Shenzhen, China

    Topic: Research on recommendation algorithm based on user multi-behavior modeling

    Projects: Graph Neural Network & Multi-behavior Recommendation
</div>
</div>


# 🎈 Professional Activities
- **Reviewer** 
  - Journal: TOIS, TKDE
  - Conference: KDD, SIGIR, CIKM, WSDM, ICONIP




  




