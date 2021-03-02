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


## [Structure-aware Pre-training for Table Understanding with Tree-based Transformers](https://arxiv.org/pdf/2010.12537)

Zhiruo Wang, Haoyu Dong, Ran Jia, Jia Li, Zhiyi Fu, Shi Han, Dongmei Zhang.

under review with the [2021 ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2021)](https://www.kdd.org/kdd2021/).


## [Intrinsic Knowledge Evaluation on Chinese Language Models](https://arxiv.org/abs/2011.14277)

Zhiruo Wang, Refen Hu.

under review with [the Joint Conference of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (ACL-IJCNLP 2021)](https://2021.aclweb.org/).


## [FastBERT: a Self-distilling BERT with Adaptive Inference Time](https://arxiv.org/pdf/2004.02178)

Weijie Liu, Peng Zhou, Zhe Zhao, Zhiruo Wang, Haotang Deng, Qi Ju.

published in [the 58th Annual Meeting of the Association for Computational Linguistics (ACL 2020)](https://acl2020.org/).


## [K-BERT: Enabling Language Representation with Knowledge Graph](https://arxiv.org/pdf/1909.07606)

Weijie Liu, Peng Zhou, Zhe Zhao, Zhiruo Wang, Qi Ju, Haotang Deng, Ping Wang

published in [the Thirth-Fourth AAAI Conference on Artificial Intelligence (AAAI 2020)](https://aaai.org/Conferences/AAAI-20/).
