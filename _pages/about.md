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


# 👋 Hi ! 

I am a second-year Master candidate at Shanghai University of Finance and Economics (SUFE), under the supervision of Prof. [Yun Chen](https://yunc.me/). 

My research interest includes **Large Language Models**, **Model Merge**, **Model Compression**, and **LLM Safety**. Feel free to contact me to discuss or collaborate!

<span style="background-color: #fff3cd; padding:0.2em 0.4em; border-radius:4px;">
  ✨ <strong>Currently seeking Ph.D. opportunities.</strong>
</span>


# 🔥 News
- *2025.05*: &nbsp;🎉🎉 One paper is accepted by ACL 2025 Main Conference. 
- *2025.01*: &nbsp;🎉🎉 One paper is accepted by NAACL 2025 Main Conference.  
- *2024.09*: &nbsp;🎉🎉 One paper is accepted by EMNLP 2024 Main Conference. 

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/ImPart.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## **ImPart: Importance-Aware Delta-Sparsification for Improved Model Compression and Merging in LLMs**

**<span style="color: #0055aa;">Yan Yang</span>**, Yixia Li, Hongru Wang, Xuetao Wei, Jianqiao Yu, Yun Chen, Guanhua Chen

📑 [**Paper**](https://arxiv.org/pdf/2504.13237) | ⚙️ [**Code**](https://github.com/yanyang19/ImPart) | 🌟 **ACL 2025 Main**
- **TL;DR**: Motivated by the observation that singular vectors with larger singular values encode more important task-specific information, ImPart assigns variable sparsity ratios to singular vectors based on corresponding singular values. ImPart achieves 2× higher compression efficiency than baselines and further improve model quantization and model merge.

</div>
</div>
<!-- ============================================================================= -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2025</div><img src='images/SeqAR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## **SeqAR: Jailbreak LLMs with Sequential Auto-Generated Characters**

**<span style="color: #0055aa;">Yan Yang</span>**, Zeguan Xiao, Xin Lu, Hongru Wang, Xuetao Wei, Hailiang Huang, Guanhua Chen, Yun Chen

📑 [**Paper**](https://arxiv.org/pdf/2407.01902) | ⚙️ [**Code**](https://github.com/sufenlp/SeqAR) | 🌟 **NAACL 2025 Main**
- **TL;DR**: Building on established character simulation methods for jailbreaks, SeqAR optimizes multiple characters and prompt LLMs to sequentially respond as them, thereby further distracting LLMs and expanding the applicable jailbreak area. SeqAR achieved state-of-the-art jailbreak performances and exhibits strong transferability.
</div>
</div>
<!-- ============================================================================= -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/DAP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## **Distract Large Language Models for Automatic Jailbreak Attack**

Zeguan Xiao, **<span style="color: #0055aa;">Yan Yang</span>**, Guanhua Chen, Yun Chen

📑 [**Paper**](https://arxiv.org/pdf/2403.08424) | ⚙️ [**Code**](https://github.com/sufenlp/AttanttionShiftJailbreak) | 🌟 **EMNLP 2024 Main** 
- **TL;DR**: Leveraging the observation that irrelevant context can distract large language models and diminish their performance, we proposed DAP, which employs specially designed jailbreak templates embedded
with refined irrelevant context to conceal malicious content. DAP demonstrated robust jailbreak performance.
</div>
</div>
<!-- ============================================================================= -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/FigirPro.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## **FigirPro: Enhancing Text-to-SQL with Fine-Grained Guidance from Pivot Programming Languages**

Yongdong Chi, Hanqing Wang, Yun Chen, **<span style="color: #0055aa;">Yan Yang</span>**, Zonghan Yang, Xiao Yan, Guanhua Chen

- **TL;DR**: FigirPro incorporates the high-resource Python program as a pivot to bridge between the natural language query and SQL program. FigirPro consistently outperforms existing text-to-SQL approaches, particularly on challenging queries.

</div>
</div>


# 🎖 Honors and Awards
- *2023.07* Outstanding Graduate of Shanghai University of Finance and Economics.
- *2023.01* Tailong Commercial Bank Scholarship (top 15%).
- *2020.09 - 2023.07* Renming Scholarship, 3rd Prize (top 15%).

# 📖 Educations
- *2023.09 - 2026.06 (now)*, Master candidate, School of Computer & Artificial Intelligence, Shanghai University of Finance and Economics, Shanghai.  
- *2019.09 - 2023.06*, Undergraduate, School of Information Management & Engineering, Shanghai University of Finance and Economics, Shanghai. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2019.05 - 2020.02*, [Toursun Synbio](https://github.com/tsynbio/), China.

# 🔆 Others
- *2022.09 - 2024.09*, Core Technical Team Member of the N.O.P.E. Robotics Club at Shanghai University of Finance and Economics. 
- *2020.09 - 2021.06*, Leader of the Academic Department of the College Student Union 