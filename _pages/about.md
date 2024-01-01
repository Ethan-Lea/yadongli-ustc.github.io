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

I am a third-year MSc student at the University of Science and Technology of China (USTC). I am also a group member of USTC [Intelligent Perception Lab](https://ustc-ip-lab.github.io/), advised by [Prof. Qibin Sun](https://ieeexplore.ieee.org/author/37088704418) and [Prof. Yan Chen](https://scholar.google.com/citations?hl=en-EN&user=MVOCn1AAAAAJ).
My research interests include wireless sensing and ubiquitous computing, focusing on developing human-centric sensing systems with cost-effective and privacy-preserving mobile devices.  

The goal of my research is to **enhance the sensing robustness** (cross-domain gesture and position sensing, sensing under human and device interference) and **augment the sensing resolution** (near-field SAR imaging, radar point cloud generation), which is crucial for achieving a comprehensive perception of the physical and digital world with millions of wireless devices. 

# 📢 News
- *2023.12*: &nbsp;🎉🎉 One paper is accepted by IEEE TMC and four papers are accepted by IEEE ICASSP. 
- *2023.11*: &nbsp;🎉🎉 One paper is accepted by [Communications Engineering](https://www.nature.com/commseng/). 
- *2023.10*: &nbsp;🎉🎉 One paper is accepted by ACM UbiComp. 
- *2023.10*: &nbsp;🎉🎉 We have released the largest [indoor mmWave radar point cloud dataset](https://github.com/ruixv/RadarEyes) and the corresponding code.
- *2023.09*: &nbsp;🎉🎉 MCD-Gesture dataset has been downloaded by researchers from over 50 universities worldwide.
- *2022.09*: &nbsp;🎉🎉 One paper is accepted by IEEE TMC. 
- *2021.11*: &nbsp;🎉🎉 We have released a [mmWave gesture dataset](https://github.com/DI-HGR/cross_domain_gesture_dataset) consisting of 24050 samples and 750 domains. 

# 🔥 Released Datasets
- [MCD-Gesture](https://github.com/yadong-lee/cross_domain_gesture_dataset): mmWave Gesture Dataset (IEEE TMC, 2022).  
  - A cross-domain gesture dataset consisting of 24050 instances from 25 users, 6 environments, and 5 locations.  
  - The dataset has been used by researchers from over 50 institutions worldwide.  
- [RadarEyes](https://github.com/ruixv/RadarEyes): mmWave Pointcloud Dataset (IEEE TIP, Under review).  
  - The largest indoor mmWave radar dataset for high-quality point cloud reconstruction.   
  - The dataset contains 1,000,000 frames of mmWave radar, LiDAR, and camera data from 300 indoor scenarios.
- [H-WILD](https://github.com/H-WILD/human_held_device_wifi_indoor_localization_dataset): WiFi Localization Dataset (ACM UbiComp, 2023).  
  - A human-held device WiFi localization dataset consisting of 120,000 frames from 10 volunteers across 4 rooms.
    
# 📝 Publications 
## Augmenting the sensing resolution
-  [A High-resolution Handheld Millimeter-wave Imaging System with Phase Error Estimation and Compensation]()  
  **Yadong Li**, Dongheng Zhang, Ruixu Geng, Zhi Lu, Zhi Wu, Yang Hu, Qibin Sun, Yan Chen  
  *to appear in Communications Engineering (**Comms. Eng.**)*
- [IFNet: Imaging and Focusing Network for Handheld mmWave Devices]()  
  **Yadong Li**, Dongheng Zhang, Ruixu Geng, Jincheng Wu, Yang Hu, Qibin Sun, Yan Chen  
  *IEEE International Conference on Acoustics, Speech, and Signal Processing (**ICASSP**), 2024*
-  [DiffRadar: High-quality mmWave Radar Perception with Diffusion Probabilistic Model]()  
  Jincheng Wu, Ruixu Geng, **Yadong Li**, Dongheng Zhang, Zhi Lu, Yang Hu, Yan Chen  
 *IEEE International Conference on Acoustics, Speech, and Signal Processing (**ICASSP**), 2024*
-  [DREAM-PCD: Deep Reconstruction and Enhancement of mmWave Radar Pointcloud]()  
   Ruixu Geng, **Yadong Li**, Dongheng Zhang, Jincheng Wu, Yating Gao, Yang Hu, Yan Chen  
 *arXiv, 2023 (submitted to IEEE Transactions on Imaging Processing)*

## Enhancing the sensing robustness
- [Towards Domain-Independent and Real-Time Gesture Recognition Using mmWave Signal](https://ieeexplore.ieee.org/abstract/document/9894724)  
  **Yadong Li**, Dongheng Zhang, Jinbo Chen, Jinwei Wan, Dong Zhang, Yang Hu, Qibin Sun, Yan Chen  
  *IEEE Transactions on Mobile Computing (**TMC**), 2022*
- [DI-Gesture: Domain-Independent and Real-Time Gesture Recognition with Millimeter-Wave Signals](https://ieeexplore.ieee.org/document/10001175)  
  **Yadong Li**, Dongheng Zhang, Jinbo Chen, Jinwei Wan, Dong Zhang, Yang Hu, Qibin Sun, Yan Chen  
  *IEEE Global Communications Conference (**GLOBECOM**), 2022*
-  [Robust WiFi Respiration Sensing in the Presence of Interfering Individual]()  
  Xuecheng Xie, Dongheng Zhang, **Yadong Li**, Jinbo Chen, Yang Hu, Qibin Sun, Yan Chen  
  *to appear in IEEE Transactions on Mobile Computing (**TMC**)*
 - [RLoc: Towards Robust Indoor Localization by Quantifying Uncertainty]()  
  Tianyu Zhang, Dongheng Zhang, Guanzhong Wang, **Yadong Li**, Yang Hu, Qibin Sun, Yan Chen  
  *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (**IMWUT/UbiComp**), 2023* 
- [SimFall: A Data Generator For RF-based Fall Detection]()  
  Jiamu Li, Dongheng Zhang, Qi Chen, **Yadong Li**, Jianyang Wang, Wenxuan Li, Yang Hu, Qibin Sun, Yan Chen  
  *IEEE International Conference on Acoustics, Speech, and Signal Processing (**ICASSP**), 2024*
- [Enabling Orientation-Free mmWave-based Vital Sign Sensing with Multi-domain Signal Analysis]()  
  Hanqin Gong, Dongheng Zhang, Jinbo Chen, **Yadong Li**, Guixin Xu, Yuqin Yuan, Yang Hu, Yan Chen  
  *IEEE International Conference on Acoustics, Speech, and Signal Processing (**ICASSP**), 2024*
- [Unsupervised Domain Adaptation for RF-based Gesture Recognition](https://ieeexplore.ieee.org/document/10147269)  
  Bin-Bin Zhang, Dongheng Zhang, **Yadong Li**, Yang Hu, Yan Chen   
  *IEEE Internet of Things Journal (**IoTJ**), 2023*
- [Real-Time Fall Detection Using mmWave Radar](https://ieeexplore.ieee.org/document/9747153)  
  Wenxuan Li, Dongheng Zhang,**Yadong Li**, Zhi Wu, Jinbo Chen, Dong Zhang, Yang Hu, Qibin Sun, Yan Chen  
  *IEEE International Conference on Acoustics, Speech, and Signal Processing (**ICASSP**), 2022*


# ✨ Honors and Awards
- *2022.10* National Scholarship for Postgraduates (Top 2%)
- *2021.08* Adolescents Science and Technology Innovation Prize in Henan (10 students in Henan province each year) 
- *2021.06* Outstanding Undergraduate in Henan (Top 2%)
- *2021.04* The Academic Star of Zhengzhou University (1 student in Zhengzhou University each year)
- *2020.11* 1st Place, RoboCup@Home China Open
- *2019.08* Excellent Design Work, Design Challenge, The IJCAI-2019 Eldercare Robot Challenge
- *2019.05* 1st Place, RoboCup@Home Asia-Pacific Invitational Tournament
- *2019.04* 1st Place, RoboCup@Home China Open 


# 📖 Education
- *2021.09 - Now*, Master, Cyberspace Security, University of Science and Technology of China. 
- *2017.09 - 2021.06*, Bachelor, Computer Science, Zhengzhou University. 



