---
permalink: /
title: "Duy Nguyen"
excerpt: "Ph.D. student at UNC Chapel Hill researching mechanistic interpretability, inference-time steering, and alignment for multimodal LLMs."
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

I am a second-year Ph.D. Student in [Prof. Mohit Bansal](https://www.cs.unc.edu/~mbansal/)’s group ([MURGe Lab](https://murgelab.cs.unc.edu/)) at UNC Chapel Hill. Previously, I was a Research Resident under the supervision of [Prof. Viet Anh Nguyen](https://vietanhnguyen.net) at [VinAI Research](https://www.vinai.io), Vietnam. I received a bachelor's degree in Computer Science from Hanoi University of Science and Technology in 2022.

My research focuses on mechanistic interpretability and inference-time interventions for interpreting and monitoring the behaviors of (multimodal) LLMs. Additionally, I am interested in post-training methods for LLMs, including Reinforcement Learning from Human Feedback (RLHF) and Reinforcement Learning with Verifiable Rewards (RLVR).

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News

<ul class="news-timeline">
  <li>
      <span class="news-timeline__date">September 2025</span>
      <span class="news-timeline__content">Our paper <a href="https://arxiv.org/abs/2410.01735" target="_blank" rel="noopener">LASeR: Learning to Adaptively Select Reward Models with Multi-Armed Bandits</a> is accepted to NeurIPS 2025!</span>
  </li>
  <li>
      <span class="news-timeline__date">August 2025</span>
      <span class="news-timeline__content">Our paper <a href="https://arxiv.org/abs/2501.15758" target="_blank" rel="noopener">Distributional Surgery for Language Model Activations</a> is accepted to EMNLP 2025 Findings!</span>
  </li>
  <li>
    <span class="news-timeline__date">July 2025</span>
    <span class="news-timeline__content">New preprint <a href="https://arxiv.org/abs/2507.18043" target="_blank" rel="noopener">GrAInS: Gradient-based Attribution for Inference-Time Steering of LLMs and VLMs</a> on using gradient attribution for steering LLMs and VLMs.</span>
  </li>
  <li>
    <span class="news-timeline__date">May 2025</span>
    <span class="news-timeline__content">Our paper <a href="https://www.arxiv.org/abs/2502.12446" target="_blank" rel="noopener">MAT-Steer: Multi-Attribute Steering of Language Models via Targeted Intervention</a> is accepted to ACL 2025! Thanks Elias for helping present the paper!</span>
  </li>
</ul>

<details class="news-archive">
  <summary>Old news</summary>

  <div markdown="1">
  <ul class="news-timeline news-timeline--compact">
    <li>
      <span class="news-timeline__date">October 2024</span>
      <span class="news-timeline__content">Our paper <a href="https://arxiv.org/abs/2311.11349" target="_blank" rel="noopener">Coverage-Validity-Aware Algorithmic Recourse</a> is accepted to Operations Research!</span>
    </li>
    <li>
      <span class="news-timeline__date">March 2024</span>
      <span class="news-timeline__content">I will be joining <a href="https://www.cs.unc.edu/~mbansal/" target="_blank" rel="noopener">Prof. Mohit Bansal</a>'s group as a Ph.D. student at UNC Chapel Hill this Fall!</span>
    </li>
    <li>
      <span class="news-timeline__date">May 2024</span>
      <span class="news-timeline__content">Our paper <a href="https://arxiv.org/abs/2406.00973" target="_blank" rel="noopener">Cold-start Recommendation by Personalized Embedding Region Elicitation</a> is accepted to UAI 2024!</span>
    </li>
    <li>
      <span class="news-timeline__date">February 2024</span>
      <span class="news-timeline__content">New preprint <a href="http://arxiv.org/abs/2402.15073" target="_blank" rel="noopener">Cost-Adaptive Recourse Recommendation by Adaptive Preference Elicitation</a> on personalized algorithmic recourse with preference elicitation.</span>
    </li>
    <li>
      <span class="news-timeline__date">January 2023</span>
      <span class="news-timeline__content">Our paper <a href="https://arxiv.org/abs/2302.11211" target="_blank" rel="noopener">Distributionally Robust Recourse Action</a> is accepted to ICLR 2023!</span>
    </li>
    <li>
      <span class="news-timeline__date">January 2023</span>
      <span class="news-timeline__content">Our paper <a href="https://arxiv.org/abs/2302.11213" target="_blank" rel="noopener">Feasible Recourse Plan via Diverse Interpolation</a> is accepted to AISTATS 2023!</span>
    </li>
    <li>
      <span class="news-timeline__date">October 2022</span>
      <span class="news-timeline__content">We are awarded an honorable mention at 2022 INFORMS Undergraduate Operations Research Prize!</span>
    </li>
    <li>
      <span class="news-timeline__date">May 2022</span>
      <span class="news-timeline__content">One paper accepted to UAI 2022!</span>
    </li>
    <li>
      <span class="news-timeline__date">January 2022</span>
      <span class="news-timeline__content">One paper accepted to ICLR 2022!</span>
    </li>
  </ul>
  </div>

</details>





# 📝 Publications

<p class="pub-note"><em>* denotes equal contribution</em></p>

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
<div class="pub-list">

<div class="pub-card">
  <div class="pub-card-title">LASeR: Learning to Adaptively Select Reward Models with Multi-Armed Bandits</div>
  <div class="pub-card-authors">
    <strong>Duy Nguyen</strong>*, Archiki Prasad*, Elias Stengel-Eskin, Mohit Bansal
  </div>
  <div class="pub-card-meta">
    <a href="https://neurips.cc/">NeurIPS 2025</a> | Conference on Neural Information Processing Systems
  </div>
  <div class="pub-card-links">
    <button class="pub-card-btn" type="button" data-toggle="abstract" data-target="abstract-laser">Abstract</button>
    <a class="pub-card-btn" href="https://arxiv.org/abs/2410.01735" target="_blank" rel="noopener">Paper</a>
    <a class="pub-card-btn" href="https://github.com/duykhuongnguyen/LASeR-MAB" target="_blank" rel="noopener">Code</a>
  </div>
  <div class="pub-card-abstract" id="abstract-laser" hidden>
    <p>Reward Models (RMs) are crucial to aligning large language models (LLMs), but the degree to which an RM specialized to one task (e.g. writing) generalizes to new tasks (e.g. math) is often not known a priori, often making using only one fixed RM to train LLMs suboptimal. However, optimizing LLMs with multiple RMs simultaneously can incur a prohibitively high computational cost and lead to conflicting signals from different RMs that may degrade performance. To address these challenges, we introduce LASeR (Learning to Adaptively Select Rewards), which frames reward model selection as a multi-armed bandit problem, efficiently and iteratively training LLMs using multiple RMs by selecting the most well-suited RM for each instance. On commonsense and math reasoning tasks, we show that LASeR boosts iterative LLM training, improving the absolute average accuracy of Llama-3-8B over three datasets by 2.67% over an ensemble of RM scores while also showing superior efficiency (e.g., a 2x speedup). Moreover, on WildChat (open-ended instruction-following tasks), LASeR leads to a 72.69% AlpacaEval win rate over the RM score ensemble baseline. Extending to long-context generation, LASeR improves by 2.96 F1 points (avg.) on single-document QA tasks and 2.97 F1 points on few-shot learning over the RM score ensemble baseline with best-of-n sampling.</p>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-title">Multi-Attribute Steering of Language Models via Targeted Intervention</div>
  <div class="pub-card-authors">
    <strong>Duy Nguyen</strong>, Archiki Prasad, Elias Stengel-Eskin, Mohit Bansal
  </div>
  <div class="pub-card-meta">
    <a href="https://2025.aclweb.org/">ACL 2025</a> | Association for Computational Linguistics
  </div>
  <div class="pub-card-links">
    <button class="pub-card-btn" type="button" data-toggle="abstract" data-target="abstract-mat-steer">Abstract</button>
    <a class="pub-card-btn" href="https://aclanthology.org/2025.acl-long.1007/" target="_blank" rel="noopener">Paper</a>
    <a class="pub-card-btn" href="https://github.com/duykhuongnguyen/MAT-Steer" target="_blank" rel="noopener">Code</a>
  </div>
  <div class="pub-card-abstract" id="abstract-mat-steer" hidden>
    <p>Inference-time intervention (ITI) has emerged as a promising method for steering large language model (LLM) behavior in a particular direction (e.g., improving helpfulness) by intervening on token representations without costly updates to the LLM’s parameters. However, existing ITI approaches fail to scale to multi-attribute settings with conflicts, such as enhancing helpfulness while also reducing toxicity. To address this, we introduce Multi-Attribute Targeted Steering (MAT-Steer), a novel steering framework designed for selective token-level intervention across multiple attributes. We achieve this by learning steering vectors using an alignment objective that shifts the model’s internal representations of undesirable outputs closer to those of desirable ones while enforcing sparsity and orthogonality among vectors for different attributes, thereby reducing inter-attribute conflicts. We evaluate MAT-Steer in two distinct settings: (i) on question answering (QA) tasks where we balance attributes like truthfulness, bias, and toxicity; (ii) on generative tasks where we simultaneously improve attributes like helpfulness, correctness, and coherence. MAT-Steer outperforms existing ITI and parameter-efficient fine-tuning approaches across both task types (e.g., average 3% accuracy gain across QA tasks and 55.82% win rate against the best ITI baseline).</p>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-title">Distributional Surgery for Language Model Activations</div>
  <div class="pub-card-authors">
    Bao Nguyen, Binh Nguyen, <strong>Duy Nguyen</strong>, Viet Anh Nguyen
  </div>
  <div class="pub-card-meta">
    <a href="https://2025.emnlp.org/">EMNLP 2025 Findings</a> | Conference on Empirical Methods in Natural Language Processing
  </div>
  <div class="pub-card-links">
    <button class="pub-card-btn" type="button" data-toggle="abstract" data-target="abstract-radiant">Abstract</button>
    <a class="pub-card-btn" href="https://arxiv.org/abs/2501.15758" target="_blank" rel="noopener">Paper</a>
    <a class="pub-card-btn" href="https://github.com/nguyenngocbaocmt02/OT-Intervention" target="_blank" rel="noopener">Code</a>
  </div>
  <div class="pub-card-abstract" id="abstract-radiant" hidden>
    <p>Language models are prone to occasionally undesirable generations, such as harmful or toxic content, despite their impressive capability to produce texts that appear accurate and coherent. This paper presents a new two-stage approach to detect and mitigate undesirable content generations by rectifying activations. First, we train an ensemble of layerwise classifiers to detect undesirable content using activations by minimizing a smooth surrogate of the risk-aware score. Then, for contents that are detected as undesirable, we propose layerwise distributional intervention policies that perturb the attention heads minimally while guaranteeing probabilistically the effectiveness of the intervention. Benchmarks on several language models and datasets show that our method outperforms baselines in reducing the generation of undesirable output.</p>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-title">Cold-start Recommendation by Personalized Embedding Region Elicitation</div>
  <div class="pub-card-authors">
    Hieu Nguyen, <strong>Duy Nguyen</strong>, Khoa Doan, Viet Anh Nguyen
  </div>
  <div class="pub-card-meta">
    <a href="https://www.auai.org/">UAI 2024</a> | Conference on Uncertainty in Artificial Intelligence
  </div>
  <div class="pub-card-links">
    <button class="pub-card-btn" type="button" data-toggle="abstract" data-target="abstract-cold-start">Abstract</button>
    <a class="pub-card-btn" href="https://openreview.net/forum?id=ciOkU5YpvU" target="_blank" rel="noopener">Paper</a>
    <a class="pub-card-btn" href="https://github.com/HieuNT91/recsys" target="_blank" rel="noopener">Code</a>
  </div>
  <div class="pub-card-abstract" id="abstract-cold-start" hidden>
    <p>Rating elicitation is a success element for recommender systems to perform well at cold-starting, in which the systems need to recommend items to a newly arrived user with no prior knowledge about the user's preference. Existing elicitation methods employ a fixed set of items to learn the user's preference and then infer the users' preferences on the remaining items. Using a fixed seed set can limit the performance of the recommendation system since the seed set is unlikely optimal for all new users with potentially diverse preferences. This paper addresses this challenge using a 2-phase, personalized elicitation scheme. First, the elicitation scheme asks users to rate a small set of popular items in a ``burn-in'' phase. Second, it sequentially asks the user to rate adaptive items to refine the preference and the user's representation. Throughout the process, the system represents the user's embedding value not by a point estimate but by a region estimate. The value of information obtained by asking the user's rating on an item is quantified by the distance from the region center embedding space that contains with high confidence the true embedding value of the user. Finally, the recommendations are successively generated by considering the preference region of the user. We show that each subproblem in the elicitation scheme can be efficiently implemented. Further, we empirically demonstrate the effectiveness of the proposed method against existing rating-elicitation methods on several prominent datasets.</p>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-title">Coverage-Validity-Aware Algorithmic Recourse</div>
  <div class="pub-card-authors">
    Ngoc Bui, <strong>Duy Nguyen</strong>, Man-Chung Yue, Viet Anh Nguyen
  </div>
  <div class="pub-card-meta">
    <a href="https://pubsonline.informs.org/journal/opre">Operations Research 2024</a> | INFORMS
  </div>
  <div class="pub-card-links">
    <button class="pub-card-btn" type="button" data-toggle="abstract" data-target="abstract-cvar">Abstract</button>
    <a class="pub-card-btn" href="https://arxiv.org/abs/2311.11349" target="_blank" rel="noopener">Paper</a>
    <a class="pub-card-btn" href="https://github.com/ngocbh/cvas" target="_blank" rel="noopener">Code</a>
  </div>
  <div class="pub-card-abstract" id="abstract-cvar" hidden>
    <p>Algorithmic recourse emerges as a prominent technique to promote the explainability, transparency, and ethics of machine learning models. Existing algorithmic recourse approaches often assume an invariant predictive model; however, the predictive model is usually updated upon the arrival of new data. Thus, a recourse that is valid respective to the present model may become invalid for the future model. To resolve this issue, we propose a novel framework to generate a model-agnostic recourse that exhibits robustness to model shifts. Our framework first builds a coverage-validity-aware linear surrogate of the nonlinear (black-box) model; then, the recourse is generated with respect to the linear surrogate. We establish a theoretical connection between our coverage-validity-aware linear surrogate and the minimax probability machines (MPM). We then prove that by prescribing different covariance robustness, the proposed framework recovers popular regularizations for MPM, including the l2-regularization and class-reweighting. Furthermore, we show that our surrogate pushes the approximate hyperplane intuitively, facilitating not only robust but also interpretable recourses. The numerical results demonstrate the usefulness and robustness of our framework.</p>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-title">Distributionally Robust Recourse Action</div>
  <div class="pub-card-authors">
    <strong>Duy Nguyen</strong>, Ngoc Bui, Viet Anh Nguyen
  </div>
  <div class="pub-card-meta">
    <a href="https://iclr.cc/">ICLR 2023</a> | International Conference on Learning Representations
  </div>
  <div class="pub-card-links">
    <button class="pub-card-btn" type="button" data-toggle="abstract" data-target="abstract-dirrac">Abstract</button>
    <a class="pub-card-btn" href="https://openreview.net/forum?id=E3ip6qBLF7" target="_blank" rel="noopener">Paper</a>
    <a class="pub-card-btn" href="https://github.com/duykhuongnguyen/DiRRAc" target="_blank" rel="noopener">Code</a>
  </div>
  <div class="pub-card-abstract" id="abstract-dirrac" hidden>
    <p>A recourse action aims to explain a particular algorithmic decision by showing one specific way in which the instance could be modified to receive an alternate outcome. Existing recourse generation methods often assume that the machine learning model does not change over time. However, this assumption does not always hold in practice because of data distribution shifts, and in this case, the recourse action may become invalid. To redress this shortcoming, we propose the Distributionally Robust Recourse Action (DiRRAc) framework, which generates a recourse action that has high probability of being valid under a mixture of model shifts. We first formulate the robustified recourse setup as a min-max optimization problem, where the max problem is specified by Gelbrich distance over an ambiguity set around the distribution of model parameters. Then we suggest a projected gradient descent algorithm to find a robust recourse according to the min-max objective. We also show that our DiRRAc framework can be extended to hedge against the misspecification of the mixture weights. Numerical experiments with both synthetic and three real-world datasets demonstrate the benefits of our proposed framework over the state-of-the-art recourse methods, which generate robust recourses.</p>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-title">Feasible Recourse Plan via Diverse Interpolation</div>
  <div class="pub-card-authors">
    <strong>Duy Nguyen</strong>, Ngoc Bui, Viet Anh Nguyen
  </div>
  <div class="pub-card-meta">
    <a href="https://aistats.org/">AISTATS 2023</a> | International Conference on Artificial Intelligence and Statistics
  </div>
  <div class="pub-card-links">
    <button class="pub-card-btn" type="button" data-toggle="abstract" data-target="abstract-rec-plan">Abstract</button>
    <a class="pub-card-btn" href="https://arxiv.org/abs/2302.11213" target="_blank" rel="noopener">Paper</a>
    <a class="pub-card-btn" href="https://github.com/duykhuongnguyen/recourse-plan-diverse-interpolation" target="_blank" rel="noopener">Code</a>
  </div>
  <div class="pub-card-abstract" id="abstract-rec-plan" hidden>
    <p>Explaining algorithmic decisions and recommending actionable feedback is increasingly important for machine learning applications. Recently, significant efforts have been invested in finding a diverse set of recourses to cover the wide spectrum of users' preferences. However, existing works often neglect the requirement that the recourses should be close to the data manifold; hence, the constructed recourses might be implausible and unsatisfying to users. To address these issues, we propose a novel approach that explicitly directs the diverse set of actionable recourses towards the data manifold. We first find a diverse set of prototypes in the favorable class that balances the trade-off between diversity and proximity. We demonstrate two specific methods to find these prototypes: either by finding the maximum a posteriori estimate of a determinantal point process or by solving a quadratic binary program. To ensure the actionability constraints, we construct an actionability graph in which the nodes represent the training samples and the edges indicate the feasible action between two instances. We then find a feasible path to each prototype, and this path demonstrates the feasible actions for each recourse in the plan. The experimental results show that our method produces a set of recourses that are close to the data manifold while delivering a better cost-diversity trade-off than existing approaches.</p>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-title">Robust Bayesian Recourse</div>
  <div class="pub-card-authors">
    Tuan-Duy H. Nguyen, Ngoc Bui, <strong>Duy Nguyen</strong>, Man-Chung Yue, Viet Anh Nguyen
  </div>
  <div class="pub-card-meta">
    <a href="https://www.auai.org/">UAI 2022</a> |  Conference on Uncertainty in Artificial Intelligence
  </div>
  <div class="pub-card-links">
    <button class="pub-card-btn" type="button" data-toggle="abstract" data-target="abstract-bayes">Abstract</button>
    <a class="pub-card-btn" href="https://openreview.net/forum?id=BqIM6SIoqgq" target="_blank" rel="noopener">Paper</a>
    <a class="pub-card-btn" href="https://github.com/VinAIResearch/robust-bayesian-recourse" target="_blank" rel="noopener">Code</a>
  </div>
  <div class="pub-card-abstract" id="abstract-bayes" hidden>
    <p>Algorithmic recourse aims to recommend an informative feedback to overturn an unfavorable machine learning decision. We introduce in this paper the Bayesian recourse, a model-agnostic recourse that minimizes the posterior probability odds ratio. Further, we present its min-max robust counterpart with the goal of hedging against future changes in the machine learning model parameters. The robust counterpart explicitly takes into account possible perturbations of the data in a Gaussian mixture ambiguity set prescribed using the optimal transport (Wasserstein) distance. We show that the resulting worst-case objective function can be decomposed into solving a series of two-dimensional optimization subproblems, and the min-max recourse finding problem is thus amenable to a gradient descent algorithm. Contrary to existing methods for generating robust recourses, the robust Bayesian recourse does not require a linear approximation step. The numerical experiment demonstrates the effectiveness of our proposed robust Bayesian recourse facing model shifts.</p>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-title">Counterfactual Plans under Distributional Ambiguity</div>
  <div class="pub-card-authors">
    Ngoc Bui, <strong>Duy Nguyen</strong>, Viet Anh Nguyen
  </div>
  <div class="pub-card-meta">
    <a href="https://iclr.cc/">ICLR 2022</a> | International Conference on Learning Representations
  </div>
  <div class="pub-card-links">
    <button class="pub-card-btn" type="button" data-toggle="abstract" data-target="abstract-copa">Abstract</button>
    <a class="pub-card-btn" href="https://openreview.net/forum?id=noaG7SrPVK0" target="_blank" rel="noopener">Paper</a>
    <a class="pub-card-btn" href="https://github.com/ngocbh/COPA" target="_blank" rel="noopener">Code</a>
  </div>
  <div class="pub-card-abstract" id="abstract-copa" hidden>
    <p>Counterfactual explanations are attracting significant attention due to the flourishing applications of machine learning models in consequential domains. A counterfactual plan consists of multiple possibilities to modify a given instance so that the model's prediction will be altered. As the predictive model can be updated subject to the future arrival of new data, a counterfactual plan may become ineffective or infeasible, with respect to the future values of the model parameters. In this work, we study the counterfactual plans under model uncertainty, in which the distribution of the model parameters is partially prescribed using only the first- and second-moment information. First, we propose an uncertainty quantification tool to compute the lower and upper bounds of the probability of feasibility for any given counterfactual plan. We then provide corrective methods to adjust the counterfactual plan to improve the feasibility measure. The numerical experiments validate our bounds and demonstrate that our correction increases the robustness of the counterfactual plans in different real-world datasets.</p>
  </div>
</div>

</div>

<script>
document.addEventListener('DOMContentLoaded', function () {
  document.querySelectorAll('.pub-card-btn[data-toggle="abstract"]').forEach(function (button) {
    button.addEventListener('click', function () {
      var targetId = button.getAttribute('data-target');
      var abstractBlock = document.getElementById(targetId);
      if (!abstractBlock) {
        return;
      }

      var isHidden = abstractBlock.hasAttribute('hidden');
      if (isHidden) {
        abstractBlock.removeAttribute('hidden');
        button.classList.add('is-active');
      } else {
        abstractBlock.setAttribute('hidden', '');
        button.classList.remove('is-active');
      }
    });
  });
});
</script>

# 🎖 Honors and Awards

<div class="award-stack">
  <div class="award-card">
    <div class="award-card__icon" aria-hidden="true">🏅</div>
    <div class="award-card__body">
      <span class="award-card__date">October 2022</span>
      <div class="award-card__title">Honorable Mention</div>
      <div class="award-card__meta">INFORMS Undergraduate Operations Research Prize</div>
    </div>
  </div>
  <div class="award-card">
    <div class="award-card__icon" aria-hidden="true">🏆</div>
    <div class="award-card__body">
      <span class="award-card__date">October 2022</span>
      <div class="award-card__title">Best Thesis Presentation Award</div>
      <div class="award-card__meta">Hanoi University of Science and Technology</div>
    </div>
  </div>
  <div class="award-card">
    <div class="award-card__icon" aria-hidden="true">🎓</div>
    <div class="award-card__body">
      <span class="award-card__date">September 2019</span>
      <div class="award-card__title">Excellence Scholarship</div>
      <div class="award-card__meta">Hanoi University of Science and Technology</div>
    </div>
  </div>
</div>

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

<ul class="news-timeline news-timeline--compact experience-timeline">
  <li>
    <span class="experience-date">May 2025 – August 2025</span>
    <div class="experience-body">
      <div class="experience-role">Applied Scientist Intern</div>
      <div class="experience-org">Amazon Science · USA</div>
    </div>
  </li>
  <li>
    <span class="experience-date">August 2022 – August 2024</span>
    <div class="experience-body">
      <div class="experience-role">Research Resident</div>
      <div class="experience-org">VinAI Research · Vietnam</div>
    </div>
  </li>
</ul>
