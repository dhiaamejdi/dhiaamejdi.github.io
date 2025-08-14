---
permalink: /
title: "Dhiaa Mejdi – Researcher in Data Engineering, MLOps, and LLM Applications"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a researcher and engineer passionate about advancing the automation, interpretability, and scalability of data engineering pipelines using large language models (LLMs). My work bridges **state-of-the-art natural language processing** with **robust, production-scale data engineering** to create trustworthy, adaptive ETL workflows and improve MLOps processes in distributed systems.

My current research explores:
- Accuracy and executability of LLM-generated ETL scripts.
- Interpretability of intelligent automation in complex data engineering contexts.
- Architectures for modernizing cloud-based data pipelines in real-world environments.

I hold a **Master’s equivalent in Computer Science and Applied Mathematics Engineering** from the National Engineering School of Sfax (ENIS), Tunisia, and I have studied as an **exchange scholar** at Hochschule Offenburg, Germany, through the competitive DAAD KOSPIE program (top 10% acceptance rate).  

Professionally, I have worked in **data engineering, MLOps, and applied machine learning** across industry and research labs:
- **Data Engineer** at ERGO GROUP AG (Germany) designing scalable AWS-based big data pipelines.
- **Deep Learning Research Intern** at Hahn-Schickard (Germany), integrating neural networks into Industry 4.0 manufacturing systems.
- Roles in **DevOps, research assistance, and applied AI** in France, Hong Kong, and Tunisia.

My research and professional experience have resulted in **peer-reviewed publications**, manuscripts under preparation for venues such as **VLDB** and **NeurIPS**, and contributions to industry-grade AI systems.  

Beyond research and engineering, I am deeply engaged in teaching, mentorship, and STEM outreach. I have served as **Chair of IEEE ENIS Student Branch**, led technical workshops in MLOps and competitive programming, and developed STEM programs for high-school students.

**Keywords:** Data Engineering, MLOps, LLMs, Generative AI, Big Data Systems, Cloud Computing, NLP for ETL Automation.


<!-- Regcent Publications -->
<h3>📚 Recent Publications</h3>
<ul>
  {% for pub in site.publications limit:3 %}
    <li>
      <a href="{{ pub.url | relative_url }}">{{ pub.title }}</a>
      <span style="color:gray;"> – {{ pub.date | date: "%B %Y" }}</span>
    </li>
  {% endfor %}
</ul>
<p><a href="{{ '/publications/' | relative_url }}">See all publications →</a></p>

<!-- Recent Awards -->
<h3>🏆 Recent Awards</h3>
<p><a href="{{ '/portfolio/' | relative_url }}">See all awards →</a></p>
