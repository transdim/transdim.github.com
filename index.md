---
layout: page
title: About me
cover: false
---

I am Xinyu Chen. Currently, I am leading an innovative and interesting GitHub project. That is [**transdim**](https://github.com/xinychen/transdim), which is a problem-oriented project for **trans**portation **d**ata **im**putation. It has covered a manifold of machine learning models. In the meanwhile, my collaborators have developed some tensor learning models with me for spatiotemporal data imputation forecasting.


## News
* **2020/5**: Paper xx is accepted by xx.
* **2020/3**: transdim project is awarded by IVADO Excellence PhD funding.
* **2018/9**: Xinyu Chen starts transdim project with personal interest at Sun Yat-Sen University. He believes *this project would help a lot for the research community*.

## Research Highlights

<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

