---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from:

- /about/
- /about.html

---

  I’m a Ph.D. student at McGill University under the supervision of Prof. [Lijun Sun](https://lijunsun.github.io/).
  I received my Master's degree in Applied Statistics from Central South University in 2024, under the supervision
  of Prof. [Muzhou Hou](https://faculty.csu.edu.cn/houmuzhou/en/index.htm). In 2021, I earned my Bachelor's degree
  in Economic Statistics from Hainan University. 

  My research interests include recommender systems, time series modeling, probabilistic machine learning, and Gaussian
  processes. During my master's studies, my research focused on understanding the negative transfer issue in cross-domain
  recommender systems from a statistical perspective and designing robust cross-domain recommender system models. Recently,
  my research has shifted toward combining deep learning and statistical models to achieve efficient covariance learning
  in spatiotemporal and multivariate process modeling.


News
=====
* <span style="color:darkred"> New! </span> I received the **MEITA Scholarship** and started my Ph.D. studies in the Department of Civil Engineering at McGill University.
* <span style="color:darkred"> New! </span> I was awarded the **Outstanding Graduate Student Award** from Central South University and the **Outstanding Graduate Award** of Hunan Province.  
* <span style="color:darkred"> New! </span> I successfully defended my thesis and received a Master's degree in Applied Statistics from the School of Mathematics and Statistics, Central South University.
<button onclick="window.location.href='https://chengyuan-zhang.github.io/news/';">Read more</button>

<p>&nbsp;</p>

Featured Research
======

## DADIN: Domain Adversarial Deep Interest Network for cross-domain recommender systems

Menglin Kong, Muzhou Hou, Shaojie Zhao, Feng Liu, Ri Su, Yinghao Chen. *Expert Systems with Applications.*

### Images
<div style="display: flex; flex-direction: row; gap: 20px; justify-content: center;">
<img src="images/dadin1.jpg" alt="Figure 1: dadin" style="max-width: 100%; height: auto; border: 1px solid #ddd; padding: 5px;">
</div>

<details>
<summary><b>Abstract</b></summary>
The cross-domain recommendation (CDR) model addresses challenges such as data sparsity, the long tail distribution of user–item interactions, and the cold start of items or users. However, solely transferring domain-shared knowledge based on the co-occurrence patterns, without considering user preferences, leads to negative transfer in CDR. To overcome these limitations, we propose an advanced deep learning CDR model called the Domain Adversarial Deep Interest Network (DADIN) aims to facilitate smooth knowledge transfer from the source domain to the target domain and effectively alleviate negative transfer. Firstly, the joint distribution alignment of user preference in DADIN is realized by introducing a skip-connection-based domain agnostic layer, and then the domain classifier is artificially designed to distinguish between the information coming from the source domain or the target domain. Additionally, DADIN combines prediction loss, global domain confusion loss, and intra-class domain confusion losses through the Min-Max game and gradient reverse layer to achieve collaborative optimization. Two real-world experiments show the area under curve (AUC) of DADIN is 0.78 on the Huawei dataset, and it outperforms its competitors by 0.71% on the Amazon dataset, showcasing its state-of-the-art performance. Moreover, our ablation studies further demonstrate that domain adversarial technique increases the AUC by 2.34% on the Huawei dataset and 16.67% on the Amazon dataset, respectively.
</details>

- Access our preprint via:
  [[arXiv](https://arxiv.org/abs/2305.12058)]
  and [[Elesvier](https://www.sciencedirect.com/science/article/pii/S0957417423033821)].

- Codes are available: [GitHub repo](https://github.com/KongMLin/C2DR).



<br/>  

## C²DR: Robust Cross-Domain Recommendation based on Causal Disentanglement

Menglin Kong, Jia Wang, Yushan Pan, Haiyang Zhang, Muzhou Hou. *WSDM'24.*

### Images
<div style="display: flex; flex-direction: row; gap: 20px; justify-content: center;">
<img src="images/c2dr.pdf" alt="Figure 1: c2dr" style="max-width: 100%; height: auto; border: 1px solid #ddd; padding: 5px;">
</div>

<details>
  <summary><b>[Abstract]</b></summary>

Cross-domain recommendation aims to leverage heterogeneous information to transfers knowledge from a data-sufficient domain (source domain) to a data-scarce domain (target domain). Existing approaches mainly ignore the modeling of  users' domain specific preferences on items. We argue that incorporating domain-specific preferences from the source domain will introduce irrelevant information that fails to the target domain. Additionally, directly combining domain-shared and domain-specific information may hinder the target domain's performance. To this end, we propose $C^2DR$, a novel approach that disentangles domain-shared and domain-specific preferences from a causal perspective. Specifically, we formulate a causal graph to capture the critical causal relationships based on the underlying recommendation process, explicitly identifying domain-shared and domain-specific information as causal irrelevant variables. Then, we introduce disentanglement regularization terms to learn distinct representations of the causal variables that obey the independence constraints in the causal graph. Remarkably, our proposed method enables effective intervention and transfer of domain-shared information, thereby improving the robustness of the recommendation model. We evaluate the efficacy of $C^2DR$ through extensive experiments on three real-world datasets, demonstrating significant improvements over state-of-the-art baselines.
</details>

- Access our paper via: [[ACM](https://dl.acm.org/doi/abs/10.1145/3616855.3635809)].
- 
- Codes are available: [GitHub repo](https://github.com/KongMLin/C2DR).

<br/>


