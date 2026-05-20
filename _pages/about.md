---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. student at [Beijing University of Posts and Telecommunications (BUPT)](https://www.bupt.edu.cn/), Beijing, China. My research interests lie in **Network Security** and **Software/Large Model Supply Chain Security**.

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

{% assign sorted_pubs = site.publications | sort: 'order' %}
{% for post in sorted_pubs limit:5 %}
  {% if post.category == 'conferences' or post.category == 'manuscripts' %}
  - **{{ post.title }}**<br/>
    {{ post.citation | strip_html | replace: '"', '' }} ({{ post.date | date: "%Y" }})
  {% endif %}
{% endfor %}

## Contact

- Email: shaoxuanyun{AT}bupt.edu.cn
- [Google Scholar](https://scholar.google.com/citations?&user=yVy5JTkAAAAJ)
- [ORCID](https://orcid.org/0009-0003-5567-6737)
- [ResearchGate](https://www.researchgate.net/profile/Shaoxuan-Yun-3)
- [GitHub](https://github.com/howardyun)
