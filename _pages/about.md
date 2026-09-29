---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi, I'm **Junkai Luo**! I am an M.Sc. student in **Computational Science and Engineering at McMaster University**, affiliated with the **DeGroote School of Business** and supervised by [**Dr. Nooshin Salari**](https://ddoor.ca/) and [**Dr. Lingling Shi**](https://experts.mcmaster.ca/people/shil43). I received my bachelor's degree in Cyberspace Security from **Sichuan University**.

My research interests lie at the intersection of **machine learning and operations research**. I am particularly interested in combining reinforcement learning and optimization to support decision-making under uncertainty, with applications in resource allocation and operations management. My previous research has explored natural language processing and reinforcement learning.

[Email](mailto:luo109@mcmaster.ca) · [Google Scholar](https://scholar.google.com/citations?user=bfJHJWUAAAAJ) · [GitHub](https://github.com/otis704)

## Research Interests

- **Reinforcement learning:** learning effective policies for sequential decision-making, including deep reinforcement learning.
- **Data-driven optimization:** integrating predictive models with optimization to improve decisions under uncertainty.

## Publications

{% assign papers = site.publications | sort: "date" | reverse %}
{% for paper in papers %}
<div style="margin-bottom: 1.25em; line-height: 1.6;">
  <div><strong>{{ paper.title | escape }}</strong></div>
  <div style="font-size: 0.9em;">
    {% if paper.authors and paper.authors != empty %}{{ paper.authors | join: ", " | markdownify | remove: '<p>' | remove: '</p>' }}{% endif %}
    {% if paper.venue and paper.venue != empty %}({{ paper.venue | escape }}){% endif %}
  </div>
</div>
{% endfor %}

## Education

**McMaster University**  
M.Sc. in Computational Science and Engineering · 2026–present  
DeGroote School of Business

**Sichuan University**  
Bachelor's degree in Cyberspace Security · 2022-2026

## Honours and Awards

- **Outstanding Undergraduate Award**, Sichuan Province (Top 3% in the province) — 2026
- **“Top 100 Students of the Year”**, Sichuan University (Top 0.3% in the university) — 2026
- **National Scholarship**, Ministry of Education of China (Top 0.2% in China) — 2024
- **BYD Scholarship**, BYD AUTO INDUSTRY CO., LTD. (1 out of 180) — 2025

## Academic Service

- **Teaching Assistant**, DeGroote School of Business, McMaster University — 2DA3: *Decision Making with Analytics*.
- **Seminar Committee Member**, McMaster Computational Science and Engineering — helping organize research talks for the CSE community.

## Get in Touch

I'm happy to connect with researchers and students interested in reinforcement learning, optimization, and their applications. Feel free to reach out at [luo109@mcmaster.ca](mailto:luo109@mcmaster.ca).
