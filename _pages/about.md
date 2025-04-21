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

Shujie Han is now a tenure-track Associate Professor of the [School of Computer Science](https://jsj.nwpu.edu.cn/enweb/HOME.htm) at [Northwestern Polytechnical University](https://www.nwpu.edu.cn/), Xi'an, Shaanxi province. She was a Boya postdoctoral fellow at [Peking University](https://www.pku.edu.cn/) advised by [Prof. Qun Huang](https://huangqundl.github.io/) in 2021-2024. Before that, she received her Ph.D.degree in July 2021 in the [Department of Computer Science and Engineering](https://www.cse.cuhk.edu.hk) at [the Chinese University of Hong Kong](https://www.cuhk.edu.hk/english/index.html) under the supervision of [Prof. Patrick P. C. Lee](http://www.cse.cuhk.edu.hk/~pclee), as a member of the [Applied Distributed System Lab (ADSLab)](http://adslab.cse.cuhk.edu.hk/). She received the B.Eng. degree in Information Security from [Northwestern Polytechnical University (NWPU)](https://www.nwpu.edu.cn/) in 2017. 

My research interests are in the intersection of systems and artificial intelligence (AI), such as AI for Systems and Systems for AI.
- **Applying AI for system dependability**: failure prediction for hard disk drives (HDDs), solid-state drives (SSDs), and memory errors.
- **System optimizations for AI applications**: scaling disk failure prediction via multi-source stream mining.

We are looking for the self-motivated students who are interested in the intersection of systems and AI to join our projects for research.
We also welcome senior undergraduate students (e.g., year-3 and year-4) to pursue their master degrees in our group.
Please feel free to contact me if you are interested in our research projects.

# 🔥 News
- *2025.01*: &nbsp;🎉🎉 One paper gets accepted in ICSE'25.
- *2024.10*: &nbsp;🎉🎉 One paper gets accepted in HPCC'24.
- *2024.09*: &nbsp;🎉🎉 One paper gets accepted in ICDM'24.

# 📝 Publications 
<!--div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div-->

Conferences
------
1. Tao Duan, Runqing Chen, Pinghui Wang, Junzhou Zhao, Jiongzhou Liu, **Shujie Han**, Yi Liu, and Fan Xu.  
**"BSODiag: A Global Diagnosis Framework for Batch Servers Outage in Large-scale Cloud Infrastructure Systems."**  
Proceedings of the 47th IEEE/ACM International Conference on Software Engineering (ICSE), Ottawa, Ontario, Canada, April 2025.  
[\[pdf\]](files/icse25.pdf)  

1. Cheng Li, Jiahe Wei, Huiru Xie, Jinjiang Wang, Xiaonan Zhao, **Shujie Han** and Xiao Zhang  
**"TraceGen: A Block-Level Storage System Performance Evaluation Tool for Analyzing and Generating I/O Traces."**  
Proceedings of the 26th IEEE International Conference on High Performance Computing and Communications (HPCC) (Short paper), Wuhan, China, December 2024.  
[\[pdf\]](files/hpcc24.pdf)  

1. **Shujie Han**, Zirui Ou, Qun Huang, and Patrick P. C. Lee.  
**"Scaling Disk Failure Prediction via Multi-Source Stream Mining."**  
Proceedings of the IEEE International Conference on Data Mining (ICDM) (Regular paper), Abu Dhabi, UAE, December 2024.  
(AR: 66/604 = 10.9%)  
[\[pdf\]](files/icdm24.pdf) [\[software\]](https://github.com/shujiehan/ScaleDFP)  

1. Zirui Ou, **Shujie Han**, Qihuan Zeng, and Qun Huang.  
**"FedSSA: Reducing Overhead of Additive Cryptographic Methods in Federated Learning with Sketch."**  
Proceedings of the 32nd IEEE International Conference on Network Protocols (ICNP), Charleroi, Belgium, October 2024.  
(AR: 50/205 = 24.4%)  
[\[pdf\]](files/icnp24.pdf)  

1. Xiao Zhang, Huiru Xie, Zhe Wang, **Shujie Han**, Leijie Zeng, and Wendi Cheng.  
**"FastStore: Optimization of Distributed Block Storage Services for Cloud Computing."**  
Proceedings of the 38th International Conference on Massive Storage Systems and Technology (MSST), Santa Clara, CA, USA, June 2024.  
(AR: 27/66 = 40.9%)  
[\[pdf\]](files/msst24.pdf)  

1. Jinhong Li, Yanjing Ren, **Shujie Han**, Patrick P. C. Lee.  
**"Enhancing LSM-tree Key-Value Stores for Read-Modify-Writes via Key-Delta Separation."**  
Proceedings of the 40th IEEE International Conference on Data Engineering (ICDE 2024), Utrecht, Netherlands, May 2024.  
[\[pdf\]](files/icde24kdsep.pdf)  

1. Qingxiu Liu, Qun Huang, Xiang Chen, Sa Wang, Wenhao Wang, **Shujie Han**, and Patrick P. C. Lee.  
**"PP-Stream: Toward High-Performance Privacy-Preserving Neural Network Inference via Distributed Stream Processing."**  
Proceedings of the 40th IEEE International Conference on Data Engineering (ICDE 2024), Utrecht, Netherlands, May 2024.  
[\[pdf\]](files/icde24ppstream.pdf)  

1. Zhinan Cheng, **Shujie Han** (corresponding), Patrick P. C. Lee, Xin Li, Jiongzhou Liu, and Zhan Li.  
**"An In-Depth Correlative Study Between DRAM Errors and Server Failures in Production Data Centers."**  
Proceedings of the 41st International Symposium on Reliable Distributed Systems (SRDS 2022), Vienna, Austria, September 2022.  
(AR: 24/105 = 22.9%)  
[\[pdf\]](files/srds22.pdf)  

1. Fan Xu, **Shujie Han** (corresponding), Patrick P. C. Lee, Yi Liu, Cheng He, and Jiongzhou Liu.  
**"General Feature Selection for Failure Prediction in Large-scale SSD Deployment."**  
Proceedings of the 51st IEEE/IFIP International Conference on Dependable Systems and Networks (DSN 2021), June 2021.  
(AR: 48/295 = 16.3%)  
[\[pdf\]](files/dsn21.pdf)  

1. **Shujie Han**, Patrick P. C. Lee, Fan Xu, Yi Liu, Cheng He, and Jiongzhou Liu.  
**"An In-Depth Study of Correlated Failures in Production SSD-Based Data Centers."**  
Proceedings of the 19th USENIX Conference on File and Storage Technologies (FAST 2021), February 2021.  
(AR: 28/130 = 21.5%)  
[\[pdf\]](files/fast21.pdf) [\[software\]](https://github.com/shujiehan/ssdanalysis) [\[corrections\]](files/fast21_corrections.txt)  

1. **Shujie Han**, Patrick P. C. Lee, Zhirong Shen, Cheng He, Yi Liu, and Tao Huang.  
**"Toward Adaptive Disk Failure Prediction via Stream Mining."**  
Proceedings of the 40th IEEE International Conference on Distributed Computing Systems (ICDCS 2020), Singapore, November 2020.  
(AR: 105/584 = 18.5%)  
(An extended version appeared in TC 2023)  
[\[pdf\]](files/icdcs20.pdf) [\[software\]](https://github.com/shujiehan/StreamDFP)  

1. Mi Zhang, **Shujie Han**, and Patrick P. C. Lee.  
**"A Simulation Analysis of Reliability in Erasure-Coded Data Centers."**  
Proceedings of the 36th IEEE International Symposium on Reliable Distributed Systems (SRDS 2017), Hong Kong, September 2017.  
(AR: 24/72 = 33.3%)  
[\[pdf\]](files/srds17.pdf) [\[software\]](http://adslab.cse.cuhk.edu.hk/software/simedc)  

Journals
------

1. **Shujie Han**, Patrick P. C. Lee, Zhirong Shen, Cheng He, Yi Liu, and Tao Huang.  
**"StreamDFP: A General Stream Mining Framework for Adaptive Disk Failure Prediction."**  
IEEE Transactions on Computers (TC), 72(2), pp.520-534, February 2023.  
(An earlier version appeared in ICDCS 2020)  
[\[main pdf\]](files/tc23.pdf) [\[supplementary pdf\]](files/tc23_supp.pdf) [\[software\]](https://github.com/shujiehan/StreamDFP)  

1. Mi Zhang, **Shujie Han**, and Patrick P. C. Lee.  
**"SimEDC: A Simulator for the Reliability Analysis of Erasure-Coded Data Centers."**  
IEEE Transactions on Parallel and Distributed Systems (TPDS), 30(12), pp. 2836-2848, December 2019.  
(An earlier version appeared in SRDS 2017)  
[\[main pdf\]](files/tpds19.pdf) [\[supplementary pdf\]](files/tpds19_supp.pdf) [\[software\]](http://adslab.cse.cuhk.edu.hk/software/simedc)  

1. Min Fu, **Shujie Han**, Patrick P. C. Lee, Dan Feng, Zuoning Chen, and Yu Xiao.  
**"A Simulation Analysis of Redundancy and Reliability in Primary Storage Deduplication."**  
IEEE Transactions on Computers (TC), 67(9), pp. 1259-1272, September 2018.  
(An earlier version appeared in IISWC 2016)  
[\[main pdf\]](files/tc18.pdf) [\[software\]](http://adslab.cse.cuhk.edu.hk/software/simdedup)  

Books
------

1. Cheng He, Mengling Feng, Patrick P. C. Lee, Pinghui Wang, **Shujie Han**, and Yi Liu (Eds.).  
**"Large-Scale Disk Failure Prediction."**  
Springer, June 2020 (ISBN: 978-981-15-7749-9).  
[\[doi\]](https://doi.org/10.1007/978-981-15-7749-9)

Preprints
------

1. **Shujie Han**, Jun Wu, Erci Xu, Cheng He, Patrick P. C. Lee, Yi Qiang, Qixing Zheng, Tao Huang, Zixi Huang, and Rui Li.  
**"Robust Data Preprocessing for Machine-Learning-Based Disk Failure Prediction in Cloud Production Environments."**  
arXiv:1912.09722, December 2019.  
[\[arXiv\]](https://arxiv.org/abs/1912.09722)

# 📖 Teaching

1. 信息存储与管理, Spring, 2024/2025.  
1. 数据库系统实验, Fall, 2024.  

# 💬 Activities

1. PC member in ICA3PP'24 and ICA3PP'23.  
1. Journal Reviewer in TON, TOS, and TCAD.  

# 🎖 Awards

1. Alibaba Group Outstanding Science Research Intern in the project "Research on online failure prediction for HDDs and field studies for SSDs in large-scale data centers" in 2022.  

