---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---

<img align="top" width="600" src="/images/github-nips.jpg" />

[**Learning Energy-based Model via Dual-MCMC Teaching**](https://jcui1224.github.io/dual-MCMC-proj/)
<br>
**Jiali Cui**, Tian Han <br> 
*In Advances in Neural Information Processing Systems* ***(NeurIPS)***, 2023

---

[**Learning Hierarchical Features with Joint Latent Space Energy-Based Prior**](https://jcui1224.github.io/hierarchical-representation-ebm-proj/)
<br>
**Jiali Cui**, Ying Nian Wu, Tian Han <br> 
*IEEE/CVF International Conference on Computer Vision (ICCV)*, 2023

[**Learning Joint Latent Space EBM Prior Model for Multi-layer Generator**](https://jcui1224.github.io/hierarchical-joint-ebm-proj/)
<br>
**Jiali Cui**, Ying Nian Wu, Tian Han <br> 
*IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2023

[**Semi-supervised Learning by Latent Space Energy-Based Model of Symbol-Vector Coupling**](https://arxiv.org/pdf/2010.09359.pdf)
<br>
Bo Pang, Erik Nijkamp, **Jiali Cui**, Tian Han, Ying Nian Wu <br> 
*Workshop on I Can’t Believe It’s Not Better (ICBINB) @ NeurIPS*, 2020
