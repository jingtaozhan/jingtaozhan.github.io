---
permalink: /
title: "Jingtao Zhan (詹靖涛)"
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

My name is Jingtao Zhan (詹靖涛, in Chinese). I am now a Tenure-track Assistant Professor at Shenzhen International Graduate School, Tsinghua University. I lead [**FAITH Lab**](https://www.faithlab.cn/) (**F**oundation of **AI** lab at **T**sing**H**ua). As the name suggests, our lab is dedicated to exploring the fundamental principles of artificial intelligence, aiming to uncover the underlying laws that govern intelligent systems.

Before that, I obtained my Ph.D. degree from the Department of Computer Science and Technology, Tsinghua University, under the supervision of Prof. Shaoping Ma and Prof. Yiqun Liu. I received my B.E. degree from the Department of Electronic Engineering, Tsinghua University, in 2020.

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 🔥 Research Statement

One of the key purposes of this personal website is to explain my research journey and interests. In the following paragraphs, I’ll begin by sharing the focus of my Ph.D. work, then describe how my understanding of AI research has evolved, and finally, outline my current research interests.

During my PhD, my research primarily focused on the field of information retrieval, a domain with both deep academic value and significant industrial relevance. Search engines and recommender systems are typical applications of this area. Research in this direction not only enhances user satisfaction but also drives tangible business value. I have worked on building more effective retrieval models, improving their efficiency, and expanding the capabilities of retrieval systems. Some of my work has received notable recognition, including Best Paper Awards at two of the top conferences in the field. These were the first such honors awarded to researchers from Chinese institutions, and the impact of these contributions continues to resonate in the industry.

**So, what am I currently interested in?**

Is it large models? Robotics? Multimodal learning?
(With all due respect, I mean no offense to any of these important domains.)

First of all, I believe the era of defining scientific research directions based on industrial application domains is over. Classifying research by domains such as "nlp" or "robots" was perhaps a necessity in the previous generation of AI, when our understanding of intelligence was still limited. But today, continuing to divide research along these lines only narrows our perspective. Imagine trying to study physics by dividing it into the study of tables, chairs, and sofas: one might never realize that they are all made of atoms. Or consider someone trying to separately study the motion of apples, moons, and stars: how could one ever discover the law of universal gravitation?

In the same way, I believe that AI research should no longer be confined by boundaries drawn around industrial domains. Doing so may actually hinder, rather than promote, scientific progress.

Secondly, many empirical phenomena suggest that a deeper unifying principle might lie beneath the surface differences of various AI domains. For instance, across different tasks, models are increasingly converging toward a common architecture, Transformer; the cross-entropy loss has become the default training objective; the Scaling Laws have been validated in multiple domains. Such convergence is very peculiar because different tasks have different data distributions and different objectives. Yet, their solutions all start to converge. There is one reasonable explanation: an underlying universal principle governs all these intelligence tasks. Just as gravitational theory links apples and planets, I believe that one day, we will uncover a unified theory of intelligence that can reveal the nature of intelligence.

**My Current Research Interests**

Finally, my current research is dedicated to developing a general Intelligence Theory. Starting from widely observed empirical patterns, I seek unified theoretical explanations that can deepen our understanding of the nature of intelligence itself. On top of this theoretical foundation, I aim to develop better AI technologies for practical applications.

Take Scaling Laws as an example. They've emerged as a cornerstone of the current era of large models, yet the reason behind them remains a mystery. Some even believe that [scaling laws are decided by god.](https://x.com/sama/status/1760473881884987606?) But as a scientist, I don’t accept “God” as an answer. I see this as a golden opportunity to explore the essence of intelligence: what intrinsic property of intelligence gives rise to the Scaling Laws? I believe that understanding this will not only deepen our grasp of intelligence, but also enable us to build better AI systems.

**Join My Research Team**

If you, too, believe in the possibility of a unified theory of AI, and are not content with just incremental improvements but instead seek deep and influential breakthroughs, I warmly welcome you to apply to work with me—as a research intern, a Master’s student, or a Ph.D. student. I recruit at least one Ph.D. student and several Master’s students every year.

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

- Evaluating Intelligence via Trial and Error. **Jingtao Zhan**, Jiahao Zhao, Jiayu Li, Yiqun Liu, Bo Zhang, Qingyao Ai, Jiaxin Mao, Hongning Wang, Min Zhang, Shaoping Ma. ArXiv Preprint.

- Capability-aware Prompt Reformulation Learning for Text-to-Image Generation. **Jingtao Zhan**, Qingyao Ai, Yiqun Liu, Jia Chen and Shaoping Ma. SIGIR 2024.

- Scaling Laws For Dense Retrieval. **Jingtao Zhan\***, Yan Fang\*, Qingyao Ai, Jiaxin Mao, Weihang Su, Jia Chen and Yiqun Liu.  SIGIR 2024. **Best Paper Award**.

- Combining Multiple Supervision for Robust Zero-shot Dense Retrieval. Yan Fang, Qingyao Ai, **Jingtao Zhan**, Yiqun Liu, Xiaolong Wu, Zhao Cao. AAAI 2024. 

- Constructing Tree-based Index for Efficient and Effective Dense Retrieval. Haitao Li, Qingyao Ai, **Jingtao Zhan**, Jiaxin Mao, Yiqun Liu, Zheng Liu, and Zhao Cao. SIGIR 2023.

- Disentangled Modeling of Domain and Relevance for Adaptable Dense Retrieval. **Jingtao Zhan**, Qingyao Ai, Yiqun Liu, Jiaxin Mao, Xiaohui Xie, Min Zhang, and Shaoping Ma. ArXiv Preprint.

- Evaluating Interpolation and Extrapolation Performance of Neural Retrieval Models. **Jingtao Zhan**, Xiaohui Xie, Jiaxin Mao, Yiqun Liu, Jiafeng Guo, Min Zhang and Shaoping Ma. CIKM 2022. 

- Learning Discrete Representations via Constrained Clustering for Effective and Efficient Dense Retrieval. **Jingtao Zhan**, Jiaxin Mao, Yiqun Liu, Jiafeng Guo, Min Zhang and Shaoping Ma. WSDM 2022. **Best Paper Award**.

- Jointly Optimizing Query Encoder and Product Quantization to Improve Retrieval Performance. **Jingtao Zhan**, Jiaxin Mao, Yiqun Liu, Jiafeng Guo, Min Zhang and Shaoping Ma. CIKM 2021.

- Optimizing Dense Retrieval Model Training with Hard Negatives. **Jingtao Zhan**, Jiaxin Mao, Yiqun Liu, Jiafeng Guo, Min Zhang and Shaoping Ma. SIGIR 2021.

- RepBERT: Contextualized Text Embeddings for First-Stage Retrieval. **Jingtao Zhan**, Jiaxin Mao, Yiqun Liu, Min Zhang, and Shaoping Ma. ArXiv Preprint.

- An Analysis of BERT in Document Ranking. **Jingtao Zhan**, Jiaxin Mao, Yiqun Liu, Min Zhang, and Shaoping Ma. SIGIR 2020.

- Leveraging Passage-level Cumulative Gain for Document Ranking. Zhijing Wu, Jiaxin Mao, Yiqun Liu, **Jingtao Zhan**, Yukun Zheng, Min Zhang and Shaoping Ma. WWW 2020.


# 🎖 Honors and Awards
- 2025, Outstanding Graduate of CS Deparment, Tsinghua University
- 2024, National Scholarship
- 2024, SIGIR'24 Best Paper Award
- 2022, Longfor Scholarship
- 2022, Overall Excellence Scholarship (First Prize), Tsinghua University. (Top 5%)
- 2022, WSDM'22 Best Paper Award
- 2021, Overall Excellence Scholarship (Second Prize), Tsinghua University. (Top 10%)
- 2020, Outstanding Graduate of Beijing
- 2020, Outstanding Graduate of Tsinghua University
- 2019, National Encouragement Scholarship
- 2017, National Encouragement Scholarship
 
# 📖 Educations
- *2025.08 - now*, Tenure-track Assistant Professor, Shenzhen International Graduate School, Tsinghua University.
- *2020.09 - 2025.06*, Ph.D. student, Department of Computer Science and Technology, Tsinghua University. 
- *2024.03 - 2024.08*, Visiting Research Scholar, University of Illinois Urbana-Champaign.
- *2016.09 - 2020.06*, B.S. student, Department of Electronic Engineering, Tsinghua University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->