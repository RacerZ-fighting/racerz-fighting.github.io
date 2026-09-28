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

Hello! I'm **Qiyi Zhang**, a third-year Ph.D. student in the [System and Software Security Laboratory](https://secsys.fudan.edu.cn/) at Fudan University, advised by Prof. [Yuan Zhang](https://yuanxzhang.github.io/).

My research focuses on **web security, Java security, and agentic systems for security**, with an emphasis on **automated vulnerability discovery and security testing**. In particular, I study **inconsistencies in URL parsing and interpretation across web components** and the security vulnerabilities that arise from them. More recently, I have been exploring **agentic systems for automated security analysis and vulnerability discovery**, with the goal of making security testing more autonomous, scalable, and practical.

My work has been accepted to leading security conferences, including **ACM CCS** and **IEEE S&P**. My research has also led to the discovery of **hundreds of high-impact real-world vulnerabilities**, earning acknowledgments and bug bounty rewards from major technology companies and open-source projects, including **Microsoft, vLLM, Oracle, Spring, and Tencent**.

Beyond identifying security problems, I am particularly interested in turning research ideas into **practical security solutions for real-world systems**. Some of my ongoing research has already been **adopted by Alibaba in practice**, and I hope to continue working on security problems that combine strong technical depth with direct real-world impact.

# 🔥 News
- [*2026.09*] &nbsp;🎉 One paper accepted by **IEEE S&P 2027**!
- [*2026.05*] &nbsp;🎉 One paper accepted by **Journal of Software 2026**!
- [*2025.08*] &nbsp;🎉 One paper accepted by **ACM CCS 2025**!

# 📝 Publications 

- `IEEE S&P'27` **Babel of Voices: Demystifying Security Threats Arising from Cross-Specification URL Parsing Inconsistencies in Web Applications** [To be appeared]  
  <u>Qiyi Zhang</u>, Anmao Gou, Youkun Shi, Fengyu Liu, Yuan Zhang.  
  In *Proceedings of 48th IEEE Symposium on Security and Privacy (S&P)*, May 2027. (<span style="color:#B00C00">CCF-A</span>) 

- `JOS'26` **Black-box Detection Method for Broken-access-control Vulnerabilities via LLM-based Semantic Understanding** [<span class="pdf">Paper</span>](https://www.jos.org.cn/jos/article/abstract/7715)
  Fengyu Liu, Yuan Zhang, <u>Qiyi Zhang</u>, Tian Chen, Youkun Shi, Min Yang.  
  *In Journal of Software*, China, 2026. (<span style="color:#B00C00">CCF-A</span>) 

- `ACM CCS'25` **Be Aware of What You Let Pass: Demystifying URL-based Authentication Bypass Vulnerability in Java Web Applications** [<span class="pdf">Full Version</span>](/paper/uabscan-ccs25-long.pdf) [<span class="pdf">Paper</span>](/paper/uabscan-ccs25.pdf) [<span class="repo">Code</span>](https://zenodo.org/records/16990216)  
  <u>Qiyi Zhang</u><sup>\*</sup>, Fengyu Liu<sup>\*</sup>, Zihan Lin, Yuan Zhang (* co-first authors).  
  In *Proceedings of the 32nd ACM Conference on Computer and Communications Security (CCS)*, October 2025. (<span style="color:#B00C00">CCF-A</span>) 

# 📖 Educations
- *2024.09 - now*, Ph.D, Fudan University, Shanghai, China.
- *2020.09 - 2024.06*, B.Eng., Xidian University, Xi’an, China.

# 💬 Service
- Teaching Assistant of System Security: Attacks & Defenses (in School of Software), Fall 2026
- Teaching Assistant of System Security: Attacks & Defenses (in School of Software), Fall 2025
- Teaching Assistant of System Security: Attacks & Defenses (in School of Software), Fall 2024
- External Reviewer
	- 2027: Usenix Security
  - 2026: Usenix Security, WWW, AsiaCCS, CODASPY
	- 2025: Usenix Security, CCS, Esoorics
	- 2024: CCS

# 🏆 Honors & Awards

* 2025 - Fudan University Open Source Pioneer Award [[Reference]](https://mp.weixin.qq.com/s/moCMrL3J0BorroiFH-s-Pw)
* 2025 - Datagrand Scholarship [[Reference]](https://cs.fudan.edu.cn/72/0c/c24257a750092/page.htm)