---
permalink: /
title: "About Me"
excerpt: "About Me"
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


Welcome to my personal page! I am currently a Ph.D. student in the [Department of Computing](https://www.polyu.edu.hk/comp/) (COMP), [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/) (PolyU), under the supervision of [Dr. Wenqi Fan (chief)](https://wenqifan03.github.io/) and [Prof. Qing Li (co)](https://www4.comp.polyu.edu.hk/~csqli/).

## Research Interest

+ Large Language Models (LLMs)
+ Graph Neural Networks (GNNs)
+ Recommender Systems (RecSys)
+ Intelligent Transportation Systems (ITS)

## Publications <a href='https://scholar.google.com/citations?user=XRAXqJgAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

+ [How Do Large Language Models Understand Graph Patterns? A Benchmark for Graph Pattern Comprehension](https://arxiv.org/pdf/2410.05298) Xinnan Dai, **Haohao Qu**, Yifei Shen, Bohang Zhang, Qihao Wen, Wenqi Fan, Dongsheng Li, Jiliang Tang, Caihua Shan. *ICLR 2025*.
+ [ChatEV: Predicting electric vehicle charging demand as natural language processing](https://www.sciencedirect.com/science/article/abs/pii/S1361920924004279?via%3Dihub) **Haohao Qu**, Han Li, 
Linlin You, Rui Zhu, Jinyue Yan, Paolo Santi, Carlo Ratti, Chau Yuen. *Transportation Research Part-D*.
+ [Unravelling the effect of electricity price on electric vehicle charging behavior: A case study in Shenzhen, China.](https://www.sciencedirect.com/science/article/abs/pii/S2210670724006607#:~:text=Impulse%20response%20analysis%20is%20conducted%20to%20unravel%20several%20noteworthy%20phenomena:) Kuang, Haoxuan, Xinyu Zhang, **Haohao Qu**, Linlin You, Rui Zhu, and Jun Li. *Sustainable Cities and Society* (2024): 105836.
+ [SSD4Rec: A Structured State Space Duality Model for Efficient Sequential Recommendation.](https://arxiv.org/pdf/2409.01192) **Haohao Qu**, Yifeng Zhang, Liangbo Ning, Wenqi Fan, Qing Li. *Preprint arXiv*.
+ [A Survey of Mamba.](https://arxiv.org/pdf/2408.01129) **Haohao Qu**, Liangbo Ning, An Rui, Wenqi Fan, Tyler Derr, Hui Liu, Xin Xu, Qing Li. *Preprint arXiv*.
+ [TokenRec: Learning to Tokenize ID for LLM-based Generative Recommendation.](https://arxiv.org/pdf/2406.10450) **Haohao Qu**, Wenqi Fan, Zihuai Zhao, Qing Li. *Preprint arXiv*.
+ [FMGCN: Federated Meta Learning-augmented Graph Convolutional Network for EV Charging Demand Forecasting.](https://ieeexplore.ieee.org/abstract/document/10472318) Linlin You, Qiyang Chen, **Haohao Qu**, Rui Zhu, Jinyue Yan, Paolo Santi, Carlo Ratti. *IEEE Internet of Things Journal* (2024), doi: 10.1109/JIOT.2024.3369655.
+ [A physics-informed and attention-based graph learning approach for regional electric vehicle charging demand prediction.](https://arxiv.org/abs/2309.05259) **Haohao Qu**, Haoxuan Kuang, Jun Li, Linlin You*. Preprint arXiv:2309.05259; *IEEE TITS*, doi: 10.1109/TITS.2024.3401850.
+ [Reinforcement Learning Based Incentive Mechanism for Federated Meta Learning: A Game-Theoretic Perspective.](https://ieeexplore.ieee.org/abstract/document/10098009) Shenglv Zhang, Yuren Zhou, **Haohao Qu**, Yiting Zhu, Linlin You*. *Proceedings of the IEEE 34th International Conference on Tools with Artificial Intelligence (ICTAI 2022)*.
+ [AFMeta: Asynchronous Federated Meta-learning with Temporally Weighted Aggregation.](https://ieeexplore.ieee.org/abstract/document/10189596) Sheng Liu, **Haohao Qu**, Qiyang Chen, Weitao Jian, Rui Liu, Linlin You*. *Proceedings of the 2022 IEEE Smartworld, Ubiquitous Intelligence & Computing, Scalable Computing & Communications, Digital Twin, Privacy Computing, Metaverse, Autonomous & Trusted Vehicles (UIC 2022)*.
+ [TWAFR-GRU: An Integrated Model for Real-time Charging Station Occupancy Prediction.](https://ieeexplore.ieee.org/abstract/document/10189531) Qiyang Chen, Sheng Liu, **Haohao Qu**, Rui Zhu, Linlin You*. *Proceedings of the 2022 IEEE Smartworld, Ubiquitous Intelligence & Computing, Scalable Computing & Communications, Digital Twin, Privacy Computing, Metaverse, Autonomous & Trusted Vehicles (UIC 2022)*.
+ [An Integrated Approach for the Near Real-Time Parking Occupancy Prediction.](https://ieeexplore.ieee.org/abstract/document/9997228) Jun Li, **Haohao Qu**, Linlin You*. *IEEE Transactions on Intelligent Transportation Systems*, 24(4), 3769-3778.
+ [Adaptation and Learning to Learn (ALL): An Integrated Approach for Small-Sample Parking Occupancy Prediction.](https://www.mdpi.com/2227-7390/10/12/2039) **Haohao Qu**, Sheng Liu, Jun Li*, Yuren Zhou, Rui Liu. *Mathematics* 10.12 (2022): 2039.
+ [Improving Parking Occupancy Prediction in Poor Data Conditions Through Customization and Learning to Learn.](https://link.springer.com/chapter/10.1007/978-3-031-10983-6_13) **Haohao Qu**, Sheng Liu, Zihan Guo, Linlin You, Jun Li*. *Proceedings of the 15th International Conference on Knowledge Science, Engineering and Management (KSEM 2022)*.
     

## Education

+ &nbsp;&nbsp;&nbsp;Ph.D student in Computing | <small>2023.01 - Now</small>
<br>&nbsp;&nbsp;&nbsp;Department of Computing (COMP), The Hong Kong Polytechnic University (PolyU)
<br>&nbsp;&nbsp;&nbsp;Advisor: [Dr. Wenqi Fan](https://wenqifan03.github.io/) and [Prof. Qing Li](https://www4.comp.polyu.edu.hk/~csqli/)

+ &nbsp;&nbsp;&nbsp;M.Eng. in Transportation Planning and Management | <small>2019.09 - 2022.06</small>
<br>&nbsp;&nbsp;&nbsp;School of Intelligent Systems Engineering (ISE), Sun Yat-sen University (SYSU, 中山大学)
<br>&nbsp;&nbsp;&nbsp;Advisor: [Associate Prof. Jun Li](https://ise.sysu.edu.cn/teacher/teacher02/106489.htm) and [Associate Prof. Linlin You](https://ise.sysu.edu.cn/teacher/teacher02/1371451.htm)

+ &nbsp;&nbsp;&nbsp;B.Eng. in Transportation Engineering | <small>2015.09 - 2019.06</small>
<br>&nbsp;&nbsp;&nbsp;School of Intelligent Systems Engineering (ISE), Sun Yat-sen University (SYSU, 中山大学)
<br>&nbsp;&nbsp;&nbsp;Advisor: [Associate Prof. Jun Li](https://ise.sysu.edu.cn/teacher/teacher02/106489.htm) and [Associate Prof. Linlin You](https://ise.sysu.edu.cn/teacher/teacher02/1371451.htm)

## Working Experience

+ Research Assistant | <small>2022.08 - 2023.08</small> | <small>China</small> 
 <br>School of Intelligent Systems Engineering (ISE), Sun Yat-sen University (SYSU, 中山大学)
 <br>Advisor: [Prof. Xiaojun Tan](https://ise.sysu.edu.cn/teacher/teacher01/1400778.htm) and [Associate Prof. Jun Li](https://ise.sysu.edu.cn/teacher/teacher02/106489.htm)
 
 


 
 



