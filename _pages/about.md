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

I am a second-year Ph.D. student in [Prof. Mohit Bansal](https://www.cs.unc.edu/~mbansal/)’s group ([MURGe Lab](https://murgelab.cs.unc.edu/)) at UNC Chapel Hill. Previously, I was a Research Resident under the supervision of [Prof. Viet Anh Nguyen](https://vietanhnguyen.net) at [VinAI Research](https://www.vinai.io), Vietnam. I received a bachelor's degree in Computer Science from Hanoi University of Science and Technology in 2022.

My research focuses on mechanistic interpretability and inference-time interventions for LLM safety alignment. Additionally, I'm interested in post-training methods for (multimodal) LLMs, including Reinforcement Learning from Human Feedback (RLHF) and Reinforcement Learning with Verifiable Rewards (RLVR).

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News

- *July 2025*: New preprint [GrAInS: Gradient-based Attribution for Inference-Time Steering of LLMs and VLMs](https://arxiv.org/abs/2507.18043) on using gradient attribution for steering LLMs and VLMs.
- *May 2025*: [MAT-Steer](https://www.arxiv.org/abs/2502.12446) is accepted to ACL 2025!
- *February 2025*: New preprint [Multi-Attribute Steering of Language Models via Targeted Intervention](https://www.arxiv.org/abs/2502.12446) on steering multiple attributes of LLMs via targeted inference-time intervention.
- *October 2024*: New preprint [LASeR: Learning to Adaptively Select Reward Models with Multi-Armed Bandits](https://arxiv.org/abs/2410.01735) on selecting the best-suited reward model for fine-tuning LLMs on a per-task or per-instance basis.
- *March 2024*: I will be joining [Prof. Mohit Bansal](https://www.cs.unc.edu/~mbansal/)'s group as a Ph.D. student at UNC Chapel Hill this Fall!

<details>
  <summary>Old news</summary>

  <div markdown="1">
  - *May 2024*: Our paper [Cold-start Recommendation by Personalized Embedding Region Elicitation](https://arxiv.org/abs/2406.00973) is accepted to UAI 2024!
  - *February 2024*: New preprint [Cost-Adaptive Recourse Recommendation by Adaptive Preference Elicitation](http://arxiv.org/abs/2402.15073) on personalized algorithmic recourse with preference elicitation.
  - *November 2023*: New preprint [Coverage-Validity-Aware Algorithmic Recourse](https://arxiv.org/abs/2311.11349) on algorithmic recourse under distribution shift.
  - *January 2023*: Our paper [Distributionally Robust Recourse Action](https://arxiv.org/abs/2302.11211) is accepted to ICLR 2023!
  - *January 2023*: Our paper [Feasible Recourse Plan via Diverse Interpolation](https://arxiv.org/abs/2302.11213) is accepted to AISTATS 2023!
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
1. Multi-Attribute Steering of Language Models via Targeted Intervention<br>
   **Duy Nguyen**, Archiki Prasad, Elias Stengel-Eskin, and Mohit Bansal.<br>
   <em>The 63rd Annual Meeting of the Association for Computational Linguistics (ACL), 2025.</em> [Paper](https://aclanthology.org/2025.acl-long.1007/) [Code](https://github.com/duykhuongnguyen/MAT-Steer)

1. Cold-start Recommendation by Personalized Embedding Region Elicitation<br>
   Hieu Nguyen, **Duy Nguyen**, Khoa Doan, and Viet Anh Nguyen.<br>
   <em>The 40th Conference on Uncertainty in Artificial Intelligence (UAI), 2024.</em> [Paper](https://openreview.net/forum?id=ciOkU5YpvU) [Code](https://github.com/HieuNT91/recsys)

1. Coverage-Validity-Aware Algorithmic Recourse<br>
   Ngoc Bui, **Duy Nguyen**, Man-Chung Yue, and Viet Anh Nguyen.<br>
   <em>Operations Research (OPRE), 2024.</em> [Paper](https://arxiv.org/abs/2311.11349) [Code](https://github.com/ngocbh/cvas)

1. Distributionally Robust Recourse Action<br>
   **Duy Nguyen**, Ngoc Bui, and Viet Anh Nguyen.<br>
   <em>The Eleventh International Conference on Learning Representations (ICLR), 2023.</em> [Paper](https://openreview.net/forum?id=E3ip6qBLF7) [Code](https://github.com/duykhuongnguyen/DiRRAc)

1. Feasible Recourse Plan via Diverse Interpolation<br>
   **Duy Nguyen**, Ngoc Bui, and Viet Anh Nguyen.<br>
   <em>The 26th International Conference on Artificial Intelligence and Statistics (AISTATS), 2023.</em> [Paper](https://arxiv.org/abs/2302.11213) [Code](https://github.com/duykhuongnguyen/recourse-plan-diverse-interpolation)

1. Robust Bayesian Recourse<br>
   Tuan-Duy H. Nguyen, Ngoc Bui, **Duy Nguyen**, Man-Chung Yue, and Viet Anh Nguyen.<br>
   <em>The 38th Conference on Uncertainty in Artificial Intelligence (UAI), 2022.</em> [Paper](https://openreview.net/forum?id=BqIM6SIoqgq) [Code](https://github.com/VinAIResearch/robust-bayesian-recourse)

1. Counterfactual Plans under Distributional Ambiguity<br>
   Ngoc Bui, **Duy Nguyen**, and Viet Anh Nguyen.<br>
   <em>The Tenth International Conference on Learning Representations (ICLR), 2022.</em> [Paper](https://openreview.net/forum?id=noaG7SrPVK0) [Code](https://github.com/ngocbh/COPA)

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
- *May 2025 - August 2025*: Applied Scientist Intern at Amazon Science, USA
- *August 2022 - August 2024*: Research Resident at VinAI Research, Vietnam
