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

I am a fifth-year (2020.09-) Ph.D. student at the State Key Lab of CAD&CG, Zhejiang University, advised by <a href="https://scholar.google.com/citations?user=vzxDyJoAAAAJ">Prof. Deng Cai</a> and <a href="https://scholar.google.com/citations?user=QLLFowsAAAAJ">Prof. Xiaofei He</a>. During my internship at Shanghai AI Laboratory, I closely collaborated with <a href="https://scholar.google.com.hk/citations?user=kWADCMUAAAAJ">Dr. Tong He</a>, <a href="https://scholar.google.com/citations?user=gFtI-8QAAAAJ">Prof. Yu Qiao</a>, and <a href="https://scholar.google.com/citations?user=pw_0Z_UAAAAJ">Prof. Wanli Ouyang</a>.

My research interests include 3D vision, robotics, and AIGC. Currently, I focus on advancing spatial intelligence through the development of a 3D foundation model. To achieve this goal, I explore four key directions: (1) Data, cheaply generating 4D data using **video generation models** and **virtual environments**; (2) Backbone, handling diverse input through **multi-modal learning**; (3) Pre-training, scaling up backbones with **representation learning**; and (4) Downstream, validating efficacy by **robot manipulation** and **3D scene understanding**.


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

## Video Generation

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICLR 2025</div>
      <img src='images/depth_any_video.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Depth Any Video with Scalable Synthetic Data**
  
  **Honghui Yang**<sup style="font-size: 1em; vertical-align: -0.4em;">*</sup>, Di Huang<sup style="font-size: 1em; vertical-align: -0.4em;">*</sup>, Wei Yin, Chunhua Shen, Haifeng Liu<sup>†</sup>, Xiaofei He, Binbin Lin, Wanli Ouyang, Tong He<sup>†</sup>
  
  ICLR, 2025

  [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2410.10815)
  [![](https://img.shields.io/github/stars/Nightmare-n/DepthAnyVideo?style=social&label=Code+Stars)](https://github.com/Nightmare-n/DepthAnyVideo)

  </div>
</div>

## Robotics

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICLR 2025</div>
      <img src='images/spa.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **SPA: 3D Spatial-Awareness Enables Effective Embodied Representation**

  Haoyi Zhu, **Honghui Yang**, Yating Wang, Jiange Yang, Limin Wang, Tong He<sup>†</sup>

  ICLR, 2025

  [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2410.08208)
  [![](https://img.shields.io/github/stars/HaoyiZhu/SPA?style=social&label=Code+Stars)](https://github.com/HaoyiZhu/SPA)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2024</div>
      <img src='images/emvp.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **EMVP: Embracing Visual Foundation Model for Visual Place Recognition with Centroid-Free Probing**

  Qibo Qiu, Shun Zhang, Haiming Gao, **Honghui Yang**, Haochao Ying, Wenxiao Wang, Xiaofei He<sup>†</sup>

  NeurIPS, 2024

  [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/placeholder)

  </div>
</div>

## Representation Learning

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2024</div>
      <img src='images/unipad.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **UniPAD: A Universal Pre-training Paradigm for Autonomous Driving**

  **Honghui Yang**, Sha Zhang, Di Huang, Xiaoyang Wu, Haoyi Zhu, Tong He<sup>†</sup>, Shixiang Tang, Hengshuang Zhao, Qibo Qiu, Binbin Lin<sup>†</sup>, Xiaofei He, Wanli Ouyang

  CVPR, 2024

  [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2310.08370)
  [![](https://img.shields.io/github/stars/Nightmare-n/UniPAD?style=social&label=Code+Stars)](https://github.com/Nightmare-n/UniPAD)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">TPAMI 2024</div>
      <img src='images/ponderv2.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **PonderV2: Improved 3D Representation with A Universal Pre-training Paradigm**

  Haoyi Zhu<sup style="font-size: 1em; vertical-align: -0.4em;">*</sup>, **Honghui Yang**<sup style="font-size: 1em; vertical-align: -0.4em;">*</sup>, Xiaoyang Wu<sup style="font-size: 1em; vertical-align: -0.4em;">*</sup>, Di Huang<sup style="font-size: 1em; vertical-align: -0.4em;">*</sup>, Sha Zhang, Xianglong He, Hengshuang Zhao, Chunhua Shen, Yu Qiao, Tong He<sup>†</sup>, Wanli Ouyang

  TPAMI, 2024

  [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2310.08586)
  [![](https://img.shields.io/github/stars/OpenGVLab/PonderV2?style=social&label=Code+Stars)](https://github.com/OpenGVLab/PonderV2)

  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICCV 2023</div>
      <img src='images/ponder.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Ponder: Point Cloud Pre-training via Neural Rendering**

  Di Huang, Sida Peng, Tong He<sup>†</sup>, **Honghui Yang**, Xiaowei Zhou, Wanli Ouyang

  ICCV, 2023

  [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2301.00157)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2023</div>
      <img src='images/gd_mae.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **GD-MAE: Generative Decoder for MAE Pre-training on LiDAR Point Clouds**

  **Honghui Yang**<sup style="font-size: 1em; vertical-align: -0.4em;">*</sup>, Tong He<sup style="font-size: 1em; vertical-align: -0.4em;">*</sup>, Jiaheng Liu, Hua Chen, Boxi Wu, Binbin Lin<sup>†</sup>, Xiaofei He, Wanli Ouyang

  CVPR, 2023

  [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2212.03010)
  [![](https://img.shields.io/github/stars/Nightmare-n/GD-MAE?style=social&label=Code+Stars)](https://github.com/Nightmare-n/GD-MAE)

  </div>
</div>

## Multi-modal Learning

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2023</div>
      <img src='images/pvt_ssd.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **PVT-SSD: Single-Stage 3D Object Detector with Point-Voxel Transformer**

  **Honghui Yang**, Wenxiao Wang, Minghao Chen, Binbin Lin<sup>†</sup>, Tong He<sup>†</sup>, Hua Chen, Xiaofei He, Wanli Ouyang

  CVPR, 2023

  [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2305.06621)
  [![](https://img.shields.io/github/stars/Nightmare-n/PVT-SSD?style=social&label=Code+Stars)](https://github.com/Nightmare-n/PVT-SSD)

  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ECCV 2022</div>
      <img src='images/graph_rcnn.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Graph R-CNN: Towards Accurate 3D Object Detection with Semantic-Decorated Local Graph**

  **Honghui Yang**, Zili Liu, Xiaopei Wu, Wenxiao Wang<sup>†</sup>, Wei Qian, Xiaofei He, Deng Cai

  ECCV, 2022 (<span style="color: red;">Oral</span>)

  [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2208.03624)
  [![](https://img.shields.io/github/stars/Nightmare-n/GraphRCNN?style=social&label=Code+Stars)](https://github.com/Nightmare-n/GraphRCNN)

  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2022</div>
      <img src='images/sfd.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Sparse Fuse Dense: Towards High Quality 3D Detection with Depth Completion**

  Xiaopei Wu, Liang Peng, **Honghui Yang**, Liang Xie, Chenxi Huang, Chengqi Deng, Haifeng Liu, Deng Cai<sup>†</sup>

  CVPR, 2022 (<span style="color: red;">Oral</span>)
  
  [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2203.09780)
  [![](https://img.shields.io/github/stars/LittlePey/SFD?style=social&label=Code+Stars)](https://github.com/LittlePey/SFD)

  </div>
</div>



# 💻 Internships
<!--
- *2024.10 - Present*, <a href="https://www.xiaohongshu.com/">RedNote</a>, China.
-->
- *2022.06 - 2024.10*, <a href="https://www.shlab.org.cn/">Shanghai AI Laboratory</a>, China.
- *2019.10 - 2022.06*, <a href="https://www.fabu.ai/">Fabu Inc.</a>, China.

# 🎖 Honors and Awards
- Transfar Scholarship, *2023*
- Lu Zengyong Scholarship, *2022* 
- Outstanding Postgraduate Student Award, *2021* - *2025* 
- Zhejiang Provincial Collegiate Programming Contest, Gold Medal, *2019*
- The ICPC Asia-East Continent Final, Bronze Medal, *2018*
- National Scholarship, *2017* 

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->


