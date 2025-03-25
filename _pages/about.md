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

I am **Tao Zhang (张韬)**, currently a PhD student at Wuhan University, under the guidance of Prof. [Shunping Ji](https://scholar.google.com/citations?user=FjoRmF4AAAAJ&hl=zh-CN). Additionally, I am currently interning at Seed, ByteDance, where I am advised by Dr. [Xiangtai Li](https://scholar.google.com/citations?user=FL3ReD0AAAAJ&hl=zh-CN) and Dr. [Jiashi Feng](https://scholar.google.com.sg/citations?user=Q8iay0gAAAAJ&hl=en). Prior to this, I completed internships at the Y-Tech Lab of Kuaishou Technology (advised by Xingye Tian) and Skywork AI (advised by Dr. [Xiangtai Li](https://scholar.google.com/citations?user=FL3ReD0AAAAJ&hl=zh-CN) and Prof. [ShuiCheng YAN](https://scholar.google.com.hk/citations?user=DNuiPHwAAAAJ&hl=en)). I obtained my master's degree from Wuhan University under the supervision of Prof. [Shunping Ji](https://scholar.google.com/citations?user=FjoRmF4AAAAJ&hl=zh-CN).

My research interests encompass:

1. Image and video understanding tasks.
2. Multi-modal learning with Large Language Models (LLMs).
3. Remote Sensing.

# 🔥 News
- *2025.03*: &nbsp;🎉🎉 DVIS++ is accepted by TPAMI 2025. 
- *2024.12*: &nbsp;🎉🎉 PCM is accepted by AAAI 2025. 
- *2024.06*: &nbsp;🎉🎉 OMG-LLaVA is accepted by NeurIPS 2024. 
- *2024.04*: &nbsp;🎉🎉 DVIS-DAQ is accepted by ECCV 2024. 
- *2023.08*: &nbsp;🎉🎉 We achieve 1st place in the VIS Track of the 5th LSVOS challenge at ICCV 2023. 
- *2023.07*: &nbsp;🎉🎉 DVIS is accepted by ICCV 2023. 
- *2023.05*: &nbsp;🎉🎉 We achieve 1st place in the VPS Track of the PVUW challenge at CVPR 2023.

# 📝 Publications 

Full Publications can be found in [Google Scholar](https://scholar.google.com/citations?user=3xu4a5oAAAAJ&hl=zh-CN).

Code can be found in [github](https://github.com/zhang-tao-whu).

## Main Publications:

<li><a href="https://arxiv.org/abs/2501.04001">Sa2VA: Marrying SAM2 with LLaVA for Dense Grounded Understanding of Images and Videos</a>,  
     Haobo Yuan*, Xiangtai Li*, <strong>Tao Zhang*</strong>, Zilong Huang, Shilin Xu, Shunping Ji, Yunhai Tong, Lu Qi, Jiashi Feng, Ming-Hsuan Yang,
      <strong>Arxiv </strong> | <a href="https://lxtgh.github.io/project/sa2va/">Code</a> </li>

<li><a href="https://arxiv.org/abs/2501.04670">Are They the Same? Exploring Visual Correspondence Shortcomings of Multimodal LLMs</a>,  
     Yikang Zhou*, <strong>Tao Zhang*</strong>, Shilin Xu, Shihao Chen, Qianyu Zhou, Yunhai Tong, Shunping Ji, Jiangning Zhang, Xiangtai Li, Lu Qi,
      <strong>Arxiv </strong> | <a href="https://zhouyiks.github.io/projects/CoLVA/">Code</a> </li>

<li><a href="https://arxiv.org/abs/2406.19389">OMG-LLaVA: Bridging Image-level, Object-level, Pixel-level Reasoning and Understanding</a>,  
     <strong>Tao Zhang</strong>, Xiangtai Li, Hao Fei, Haobo Yuan, Shengqiong Wu, Shunping Ji, Chen Change Loy, Shuicheng Yan,
      <strong>NeurIPS 2024 </strong> | <a href="https://github.com/lxtGH/OMG-Seg/tree/main/omg_llava">Code</a> </li>

<li><a href="https://arxiv.org/abs/2403.00762">Point Could Mamba: Point Cloud Learning via State Space Model</a>,  
     <strong>Tao Zhang</strong>, Haobo Yuan, Lu Qi, Jiangning Zhang, Qianyu Zhou, Shunping Ji, Shuicheng Yan, Xiangtai Li,
      <strong>AAAI 2025 </strong> | <a href="https://github.com/zhang-tao-whu/PCM">Code</a> </li>

<li><a href="https://arxiv.org/pdf/2404.00086">Improving Video Segmentation via Dynamic Anchor Queries</a>,  
     Yikang Zhou*, <strong>Tao Zhang*</strong>, Shunping Ji, Shuicheng Yan, Xiangtai Li,
      <strong>ECCV 2024 </strong> | <a href="https://github.com/zhang-tao-whu/DVIS_Plus/tree/main/DVIS_DAQ">Code</a> </li>

<li><a href="https://arxiv.org/abs/2312.13305">DVIS++: Improved Decoupled Framework for Universal Video Segmentation</a>,  
     <strong>Tao Zhang</strong>, Xingye Tian, Yikang Zhou, Shunping Ji, Xuebo Wang, Yuan Zhang, Pengfei Wan, Zhongyuan Wang, Yu Wu,
      <strong>TPAMI 2025 </strong> | <a href="https://github.com/zhang-tao-whu/DVIS_Plus">Code</a> </li>

<li><a href="https://arxiv.org/abs/2306.03413">DVIS: Decoupled Video Instance Segmentation Framework</a>,  
     <strong>Tao Zhang</strong>, Xingye Tian, Yu Wu, Shunping Ji, Xuebo Wang, Yuan Zhang, Pengfei Wan,
      <strong>ICCV 2023 </strong> | <a href="https://github.com/zhang-tao-whu/DVIS">Code</a> </li>

<li><a href="https://arxiv.org/abs/2203.04074">E2EC: An End-to-End Contour-based Method for High-Quality High-Speed Instance Segmentation</a>,  
     <strong>Tao Zhang</strong>, Shiqing Wei, Shunping Ji,
      <strong>CVPR 2022 </strong> | <a href="https://github.com/zhang-tao-whu/e2ec">Code</a> </li>

# 🎖 Honors and Awards
- *2023.08* Winner of the VIS Track of the 5th LSVOS challenge at ICCV 2023. 
- *2023.05* Winner of the VPS Track of the PVUW challenge at CVPR 2023.
- Conference Reviewer for CVPR, ICCV, ECCV, NeurIPS, ICML, ICLR, AAAI, and Journal Reviewer For IEEE-TCSVT and IEEE-TGRS.

# 📖 Educations
- *2023.09 - now*, PhD in Wuhan University. 
- *2020.09 - 2023.06*, Master in Wuhan University. 
- *2016.09 - 2020.06*, Bachelor in Northeastern University. 


# 💻 Internships
- *2022.01 - 2024.02*, Y-Tech Lab of Kuaishou technology, China.
- *2024.02 - 2024.06*, Skywork AI, Singapore.
- *2024.09 - now*, Seed, ByteDance, China.