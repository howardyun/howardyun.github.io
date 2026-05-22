---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. candidate at [Beijing University of Posts and Telecommunications (BUPT)](https://www.bupt.edu.cn/), Beijing, China, advised by Prof. [Yuchao Zhang](https://yuchaozhang.weebly.com) and Prof. Wendong Wang. I am a member of the [DANCE Group](https://yuchaozhang.weebly.com), where I serve as the Principal Investigator (**PI**) of the security research direction, leading the **DANCE SEC** team. My research focuses on **Network Security** and **Software/Large Language Model (LLM) Supply Chain Security**.

Outside of research, you can find me on the basketball court (always down for a pickup game), trying to nail a new song on guitar, or losing table tennis rallies to people who claim they "don't play that much." I'm an INTJ — which means I'll analyze your network traffic for vulnerabilities but won't judge your code (much).

Please feel free to reach out; I promise I'm friendlier than my threat models suggest.

## Education

- **Ph.D. in Software Engineering** (2023 -- Present), Beijing University of Posts and Telecommunications (BUPT), Beijing, China
  - Research: Network Security, Software & Large Model Supply Chain Security
- **M.E. in Software Engineering** (2022 -- 2023), Beijing University of Posts and Telecommunications (BUPT), Beijing, China
  - Research: Cloud Computing, Network Security
  - Transferred to Ph.D. program
- **B.E. in Software Engineering (Cloud Computing)** (2018 -- 2022), Beijing Information Science and Technology University (BISTU), Beijing, China
  - Joint program with BUPT (2018 -- 2021)
  - Recommended for graduate admission to BUPT

## Selected Publications

{% include base_path %}

{% assign sorted_pubs = site.publications | sort: 'order' | reverse %}
{% for post in sorted_pubs limit:5 %}
  {% if post.category == 'conferences' or post.category == 'manuscripts' %}
  - **{{ post.title }}**{% if post.ccf_rank %} <span style="background-color: #e74c3c; color: #fff; padding: 1px 6px; border-radius: 3px; font-size: 0.75em; font-weight: bold;">{{ post.ccf_rank }}</span>{% endif %}<br/>
    {{ post.citation | strip_html | replace: '"', '' }} ({{ post.date | date: "%Y" }})
  {% endif %}
{% endfor %}

## Invited Talks

- **Guest Speaker**, 97th CCF Student Pioneer Program (SPP), China Computer Federation (2024)

## Teaching

- **Guest Lecturer**, School of Public Administration, Renmin University of China (2024)
  - Invited by faculty to deliver a 6-hour lecture series on Machine Learning for graduate students
- **Graduate Teaching Assistant**, Future Internet: Emerging Technologies, BUPT (2023 -- 2025)
  - Assisted in course delivery, lab supervision, and student mentoring

## Contact

- Email: shaoxuanyun{AT}bupt.edu.cn
- [Google Scholar](https://scholar.google.com/citations?&user=yVy5JTkAAAAJ)
- [ORCID](https://orcid.org/0009-0003-5567-6737)
- [ResearchGate](https://www.researchgate.net/profile/Shaoxuan-Yun-3)
- [GitHub](https://github.com/howardyun)
