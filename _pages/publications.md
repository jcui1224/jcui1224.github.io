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

[**Learning Joint Latent Space EBM Prior Model for Multi-layer Generator**](https://jcui1224.github.io/hierarchical-joint-ebm-proj/)
<br>
**Jiali Cui**, Ying Nian Wu, Tian Han <br> 
*IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2023

[**Learning Hierarchical Features with Joint Latent Space Energy-Based Prior**](https://jcui1224.github.io/hierarchical-representation-ebm-proj/)
<br>
**Jiali Cui**, Ying Nian Wu, Tian Han <br> 
*IEEE/CVF International Conference on Computer Vision (ICCV)*, 2023
