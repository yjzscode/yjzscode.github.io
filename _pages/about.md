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

🙋 I am Yijin Zhou (周艺晋), currently a second-year Ph.D. student at [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/) and [Shanghao Innovation Institute](https://www.sii.edu.cn/), supervised by Research Scientist [Jing Shao](https://amandajshao.github.io/). I received my bachelor's degree from [Zhiyuan College](https://zhiyuan.sjtu.edu.cn/html/zhiyuan/), Shanghai Jiao Tong University, in 2024.

📓 My research interests lie in AI agents, post-training, and trustworthiness. Outside of research, I enjoy 🏸badminton and 🏋️fitness.


# 🔥 News
- *2026.06*: &nbsp;🎉🎉 One paper is accepted by ECCV 2026!
- *2026.05*: &nbsp;🎉🎉 One paper is accepted by ICML 2026!
- *2026.04*: &nbsp;🎉🎉 One paper is accepted by RSS 2026!
- *2026.03*: &nbsp;🎉🎉 One paper is accepted by CVPR 2026 Findings🏸!
- *2026.03*: &nbsp;🎉🎉 One paper is accepted by CVPR 2026!
- *2025.11*: &nbsp;🎉🎉 One paper is accepted by AAAI 2026!
- *2025.09*: &nbsp;🎉🎉 Start my journal at Shanghao Innovation Institute!
- *2025.07*: &nbsp;🎉🎉 Start a period of algorithm internship at Shanghai AI Lab!
- *2024.12*: &nbsp;🎉🎉 One paper is accepted by Medical Image Analysis (IF 10.9)!
- *2024.07*: &nbsp;🎉🎉 Start a period of algorithm internship at Alibaba!
- *2024.06*: &nbsp;🎉🎉 Graduated and won Outstanding Undergraduate Thesis (Top 1%) and Outstanding Students of SJTU!
- *2024.02*: &nbsp;🎉🎉 One paper is accepted by ICML 2024 FM-Wild Workshop!
- *2023.10*: &nbsp;🎉🎉 One paper is accepted by Medical Image Analysis (IF 10.9)!

# 📝 Publications 
## (M)LLM Agent
- `Arxiv` [Exploring Agentic Tool-Calling Decisions via Uncertainty-Aligned Reinforcement Learning](https://arxiv.org/pdf/2606.06976), **Yijin Zhou**, Linqian Zeng, Xiaoya Lu, Wenyuan Xie, Dongrui Liu, Junchi Yan, Jing Shao. [Github](https://github.com/yjzscode/TRUST)
- `ECCV 2026` [HomeGuard: VLM-based Embodied Safeguard for Identifying Contextual Risk in Household Task](https://arxiv.org/pdf/2603.14367), Xiaoya Lu\*, **Yijin Zhou\***, Zeren Chen, Ruocheng Wang, Bingrui Sima, Enshen Zhou, Lu Sheng, Dongrui Liu, Jing Shao. [Github](https://github.com/AI45Lab/HomeGuard)
- `Arxiv` [INFA-Guard: Mitigating Malicious Propagation via Infection-Aware Safeguarding in LLM-Based Multi-Agent Systems](https://arxiv.org/pdf/2601.14667), **Yijin Zhou\***, Xiaoya Lu\*, Dongrui Liu, Junchi Yan, Jing Shao. [Github](https://github.com/yjzscode/INFA-Guard)
- `CVPR 2026` [Geometrically-Constrained Agent for Spatial Reasoning](https://arxiv.org/pdf/2511.22659), Zeren Chen\*, Xiaoya Lu\*, Zhijie Zheng, Pengrui Li, Lehan He, Yijin Zhou, Jing Shao, Bohan Zhuang, Lu Sheng. [Github](https://github.com/gca-spatial-reasoning/gca) [Page](https://gca-spatial-reasoning.github.io/)
- `AAAI 2026` [IS-Bench: Evaluating Interactive Safety of VLM-Driven Embodied Agents in Daily Household Tasks](https://arxiv.org/pdf/2506.16402), Xiaoya Lu\*, Zeren Chen\*, Xuhao Hu\*, **Yijin Zhou**, Weichen Zhang, Dongrui Liu, Lu Sheng, Jing Shao. [Github](https://github.com/AI45Lab/IS-Bench) [Dataset](https://huggingface.co/datasets/Ursulalala/IS_Bench_dataset)

## (M)LLM Post-Training
- `ICML 2026` [How Out-of-Distribution Detection Learning Theory Enhances Transformer: Learnability and Reliability](https://arxiv.org/pdf/2406.12915), **Yijin Zhou**, Yutang Ge, Wenyuan Xie, Linqian Zeng, Xiaowen Dong, Yuguang Wang. [Github](https://github.com/yjzscode/GROD-OOD-Detection-with-Transformers)
- `ICML 2024 Workshop` [GROD: Enhancing Generalization of Transformer with Out-of-Distribution Detection](https://openreview.net/pdf?id=rh7qlZdUt5), **Yijin Zhou**, Yuguang Wang.


## Others
- `CVPR 2026 Findings` [Jano: Adaptive Diffusion Generation with Early-stage Convergence Awareness](https://arxiv.org/pdf/2603.00519), Yuyang Chen\*, Linqian Zeng\*, **Yijin Zhou**, Hengjie Li, Jidong Zhai. [Github](https://github.com/chen-yy20/Jano)
- `Arxiv` [DeepSight: An All-in-One LM Safety Toolkit](https://arxiv.org/pdf/2602.12092), Bo Zhang, Jiaxuan Guo, Lijun Li, Dongrui Liu, Sujin Chen, Guanxu Chen, Zhijie Zheng, Qihao Lin, Lewen Yan, Chen Qian, **Yijin Zhou**, Yuyao Wu, Shaoxiong Guo, Tianyi Du, Jingyi Yang, Xuhao Hu, Ziqi Miao, Xiaoya Lu, Jing Shao, Xia Hu. [DeepSafe](https://github.com/AI45Lab/DeepSafe) [DeepScan](https://github.com/AI45Lab/DeepScan)
- `Arxiv` [Frontier AI Risk Management Framework in Practice: A Risk Analysis Technical Report v1. 5](https://arxiv.org/pdf/2602.14457), Dongrui Liu, Yi Yu, Jie Zhang, Guanxu Chen, Qihao Lin, Hanxi Zhu, Lige Huang, **Yijin Zhou**, Peng Wang, Shuai Shao, Boxuan Zhang, Zicheng Liu, Jingwei Sun, Yu Li, Yuejin Xie, Jiaxuan Guo, Jia Xu, Chaochao Lu, Bowen Zhou, Xia Hu, Jing Shao.
- `Chapter in Book "Deep Learning in Drug Design"` [Generative models for drug design](https://www.sciencedirect.com/science/chapter/edited-volume/pii/B9780443329081000155), **Yijin Zhou**, Yuguang Wang.
- `Medical Image Analysis` [Learnable color space conversion and fusion for stain normalization in pathology images](https://www.sciencedirect.com/science/article/pii/S1361841524003499), Jing Ke, **Yijin Zhou**（学生一作）, Yiqing Shen, Yi Guo, Ning Liu, Xiaodan Han, Dinggang Shen. [Github](https://github.com/yjzscode/Optimal-Normalisation-in-Color-Spaces)
- `Medical Image Analysis` [Clusterseg: A crowd cluster pinpointed nucleus segmentation framework with cross-modality datasets](https://www.sciencedirect.com/science/article/pii/S1361841523000191), Jing Ke, Yizhou Lu, Yiqing Shen, Junchao Zhu, **Yijin Zhou**, Jinghan Huang, Jieteng Yao, Xiaoyao Liang, Yi Guo, Zhonghua Wei, Sheng Liu, Qin Huang, Fusong Jiang, Dinggang Shen. [Github](https://github.com/lu-yizhou/ClusterSeg)

# 🎖 Honors and Awards
- Excellent Bachelor’s Thesis (Top 1%), Shanghai Jiao Tong University
- “Chun-Tsung Scholar” Honorary Title, conferred by Nobel Laureate Tsung-Dao Lee
- Outstanding Graduate, Shanghai Jiao Tong University
- Meritorious Student, Shanghai Jiao Tong University
- Zhiyuan Honor Scholarship (3 times)
- Undergraduate Excellence Scholarship (3 times)

# 📖 Educations
- *2025.09 - Now*, Phd Student, Shanghai Innovation Institute, Shanghai.
- *2024.09 - Now*, Phd Student, Shanghai Jiao Tong University, Shanghai.
- *2020.09 - 2024.06*, Undergraduate, Shanghai Jiao Tong University, Shanghai.


# 💻 Internships
- *2025.07 - 2026.07*, AI Algorithm Intern, Shanghai Artificial Intelligence Laboratory
- *2024.06 - 2024.08*, AI Algorithm Intern, Alibaba Cloud Computing Co., Ltd.

