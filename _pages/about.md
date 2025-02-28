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

# About Me

I am a Ph.D. student in [Prof. Mohit Bansal](https://www.cs.unc.edu/~mbansal/)’s group ([MURGe Lab](https://murgelab.cs.unc.edu/)) at UNC Chapel Hill. Previously, I was a Research Resident under the supervision of [Prof. Viet Anh Nguyen](https://vietanhnguyen.net) at [VinAI Research](https://www.vinai.io), Vietnam. I received a bachelor's degree in Computer Science from Hanoi University of Science and Technology in 2022.

My research focuses on post-training methods for (multimodal) LLMs, including RLHF and Reward Modeling. Additionally, I'm very interested in mechanistic interpretability and inference-time interventions for LLM safety alignment.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News

- *February 2025*: New preprint [Multi-Attribute Steering of Language Models via Targeted Intervention](https://www.arxiv.org/abs/2502.12446) on steering multiple attributes of LLMs via targeted inference-time intervention.
- *October 2024*: New preprint [LASeR: Learning to Adaptively Select Reward Models with Multi-Armed Bandits](https://arxiv.org/abs/2410.01735) on selecting the best-suited reward model for fine-tuning LLMs on a per-task or per-instance basis.
- *May 2024*: Our paper [Cold-start Recommendation by Personalized Embedding Region Elicitation](https://arxiv.org/abs/2406.00973) is accepted to UAI 2024!
- *March 2024*: I will be joining [Prof. Mohit Bansal](https://www.cs.unc.edu/~mbansal/)'s group as a Ph.D. student at UNC Chapel Hill this Fall!
- *February 2024*: New preprint [Cost-Adaptive Recourse Recommendation by Adaptive Preference Elicitation](http://arxiv.org/abs/2402.15073) on personalized algorithmic recourse with preference elicitation.
- *November 2023*: New preprint [Coverage-Validity-Aware Algorithmic Recourse](https://arxiv.org/abs/2311.11349) on algorithmic recourse under distribution shift.
- *January 2023*: Our paper [Distributionally Robust Recourse Action](https://arxiv.org/abs/2302.11211) is accepted to ICLR 2023!
- *January 2023*: Our paper [Feasible Recourse Plan via Diverse Interpolation](https://arxiv.org/abs/2302.11213) is accepted to AISTATS 2023!

<details>
  <summary>Old news</summary>

  <div markdown="1">
  - *October 2022*: We are awarded an honorable mention at 2022 INFORMS Undergraduate Operations Research Prize!
  - *May 2022*: One paper accepted to UAI 2022!
  - *January 2022*: One paper accepted to ICLR 2022!
  </div>

</details>





# 📝 Publications

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
</div>
</div> -->



<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2022</div><img src='images/GSAT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Interpretable and Generalizable Graph Learning via Stochastic Attention Mechanism](https://arxiv.org/abs/2201.12987) \\
**Siqi Miao**, Miaoyuan Liu, Pan Li, **ICML 2022**

<a href="https://github.com/Graph-COM/GSAT"><img src="https://img.shields.io/github/stars/Graph-COM/GSAT?style=social&label=Code+Stars" alt=""></a>
</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">UAI 2024</div><img src='images/pere.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cold-start Recommendation by Personalized Embedding Region Elicitation](https://openreview.net/forum?id=ciOkU5YpvU) \\
Hieu Nguyen, **Duy Nguyen**, Khoa Doan, and Viet Anh Nguyen. \\
The 40th Conference on Uncertainty in Artificial Intelligence (UAI), 2024. \\
<a href="https://openreview.net/forum?id=ciOkU5YpvU"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=UAI 2024&color=red"></a>
<a href="https://arxiv.org/abs/2406.00973"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/HieuNT91/recsys"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
<!-- <a href="https://colab.research.google.com/drive/1t0_4BxEJ0XncyYvn_VyEQhxwNMvtSUNx?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Colab"></a> -->
<!-- <a href="https://proceedings.mlr.press/v162/miao22a.html"> <img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICML%2722&color=blue"> </a> -->

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='images/dirrac.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Distributionally Robust Recourse Action](https://openreview.net/forum?id=E3ip6qBLF7) \\
**Duy Nguyen**, Ngoc Bui, and Viet Anh Nguyen. \\
The Eleventh International Conference on Learning Representations (ICLR), 2023. \\
<a href="https://openreview.net/forum?id=E3ip6qBLF7"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICLR 2023&color=blue"></a>
<a href="https://arxiv.org/abs/2302.11211"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/duykhuongnguyen/DiRRAc"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
<!-- <a href="https://colab.research.google.com/drive/1t0_4BxEJ0XncyYvn_VyEQhxwNMvtSUNx?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Colab"></a> -->
<!-- <a href="https://proceedings.mlr.press/v162/miao22a.html"> <img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICML%2722&color=blue"> </a> -->

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AISTATS 2023</div><img src='images/frpd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Feasible Recourse Plan via Diverse Interpolation](https://arxiv.org/abs/2302.11213) \\
**Duy Nguyen**, Ngoc Bui, and Viet Anh Nguyen. \\
The 26th International Conference on Artificial Intelligence and Statistics (AISTATS), 2023. \\
<a href="https://arxiv.org/abs/2302.11213"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=AISTATS 2023&color=green"></a> 
<a href="https://arxiv.org/abs/2302.11213"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/duykhuongnguyen/recourse-plan-diverse-interpolation"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">UAI 2022</div><img src='images/rbr.png' alt="sym" width="100%"></div></div>    
<div class='paper-box-text' markdown="1">

[Robust Bayesian Recourse](https://openreview.net/forum?id=BqIM6SIoqgq) \\
Tuan-Duy H. Nguyen, Ngoc Bui, **Duy Nguyen**, Man-Chung Yue, and Viet Anh Nguyen. \\
The 38th Conference on Uncertainty in Artificial Intelligence (UAI), 2022. \\
<a href="https://openreview.net/forum?id=BqIM6SIoqgq"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=UAI 2022&color=red"></a>
<a href="https://arxiv.org/abs/2206.10833"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/VinAIResearch/robust-bayesian-recourse"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2022</div><img src='images/copa.png' alt="sym" width="100%"></div></div>     
<div class='paper-box-text' markdown="1">

[Counterfactual Plans under Distributional Ambiguity](https://openreview.net/forum?id=noaG7SrPVK0) \\
Ngoc Bui, **Duy Nguyen**, and Viet Anh Nguyen. \\
The Tenth International Conference on Learning Representations (ICLR), 2022. \\
<a href="https://openreview.net/forum?id=noaG7SrPVK0"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICLR 2022&color=blue"></a>
<a href="https://arxiv.org/abs/2201.12487"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/ngocbh/COPA"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a> 
</div>
</div> 

# 🎖 Honors and Awards
- *October 2022*: Honorable Mention - INFORMS Undergraduate Operations Research Prize
- *October 2022*: Best Thesis Presentation Award - Hanoi University of Science and Technology
- *September 2019*: Excellence Scholarship for the academic year - Hanoi University of Science and Technology

<!-- # 💬 Invited Talks
- *2022.11*, Inter-Experimental LHC Machine Learning Working Group, CERN
- *2022.10*, Department of Physics, Purdue University
- *2022.08*, AI Time
- *2022.07*, Fast Machine Learning Lab
-->

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Experience
- *August 2022 - August 2024*: Research Resident at VinAI Research, Vietnam
