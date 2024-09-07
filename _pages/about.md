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

Hi there, I am Shengxin Hong. I am a senior undergraduate student majoring in Software Engineering at Detroit Mercy University and Hubei University of Technology (joint degree). Currently, I am a research assistant with Prof. [Xiuyi Fan](https://dr.ntu.edu.sg/cris/rp/rp01665) at Nanyang Technological University (NTU).

My research interests lie at the intersection of Explainable AI (XAI) and multi-agent systems. In the past, I've been focused on the goal of designing contestable AI systems that are open to human intervention and responsive to disputes (human-machine and machine-machine). Specifically, I explored the following domains:

- AI for Education: Designing interactive human-AI systems for application in educational environments, in order to provide effective, safe and explainable automated assessment scoring and feedback to students.
- Autonomous Agent: Integrating symbolic logic techniques (formal reasoning, argumentation, and KR) to develop robust AI agents (especially Large Language Models as Agent) that can engage and cooperate with humans in a manner that is as intuitive and natural as human-to-human interaction.
- LLMs for Reasoning: Generalizing LLMs to complex reasoning scenarios based on neural-symbolic approaches.


# 📝 Academic Papers

<div class='paper-box'><div class='paper-box-image'><div><img src='images/EAAI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[``My Grade is Wrong!'': A Contestable AI Framework for Providing Interactive Feedback to Students](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Shengxin Hong**, Chang Cai, Sixuan Du, Haiyue Feng, Francesca Toni, Xiuyi Fan
**Submitted to [EAAI-25-AAAI](https://eaai-conf.github.io/year/eaai-25.html)**
- Interactive feedback, where feedback flows in both directions between teacher and student, is more effective than traditional one-way feedback. However, it is often too time-consuming for widespread use in educational practice. While Large Language Models (LLMs) have potential for automating feedback, they struggle with reasoning and interaction in an interactive setting. This paper introduces CAELF, a Contestable AI Empowered LLM Framework for automating interactive feedback. CAELF allows students to query, challenge, and clarify their feedback by integrating a multi-agent system with computational argumentation. Essays are first assessed by multiple Teaching-Assistant Agents (TA Agents), and then a Teacher Agent aggregates the evaluations through formal reasoning to generate feedback and grades. Students can further engage with the feedback to refine their understanding. A case study on 500 critical thinking essays with user studies demonstrates that CAELF significantly improves interactive feedback, enhancing the reasoning and interaction capabilities of LLMs. This approach offers a promising solution to overcoming the time and resource barriers that have limited the adoption of interactive feedback in educational settings.
</div>
</div>

- [Reconciling Explanations in Multi-Model Systems through Probabilistic Argumentation](https://arxiv.org/abs/2404.13419), **Shengxin Hong**, Xiuyi Fan, **axXiv Preprint**

- [ArgMed-Agents: Explainable Clinical Decision Reasoning with LLM Disscusion via Argumentation Schemes](https://arxiv.org/abs/2403.06294), **Shengxin Hong**, Liang Xiao, Xin Zhang, Jianxia Chen, **Accepted in BIBM 2024**

# 📖 Experiences
- *2023.11 - Present*, Research Assistant (Remote), Nanyang Technological University (NTU), Singapore.
Advisor: Prof. [Xiuyi Fan](https://dr.ntu.edu.sg/cris/rp/rp01665)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.