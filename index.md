---
layout: page
title: About Author
cover: false
---

I am Xinyu Chen. Currently, I am leading an innovative and interesting GitHub project. That is [**transdim**](https://github.com/xinychen/transdim), which is a problem-oriented project for **trans**portation **d**ata **im**putation. It has covered a manifold of machine learning models. In the meanwhile, my collaborators have developed some tensor learning models with me for spatiotemporal data imputation forecasting.


## News
* **2020/5**: Paper xx is accepted by xx.
* **2020/3**: transdim project is awarded by IVADO Excellence PhD funding.
* **2018/9**: Xinyu Chen starts transdim project with personal interest at Sun Yat-Sen University. He believes *this project would help a lot for the research community*.

## Research Highlights

Machine learning models make important developments in the field of spatiotemporal data modeling - like how to forecast near-future traffic states of road networks. But what happens when these models are built with incomplete data commonly collected in real-world systems?

In the transdim (transportation data imputation) project, we build machine learning models to help address some of the toughest challenges of spatiotemporal data modeling - from missing data imputation to time series prediction. The strategic aim of this project is creating accurate and efficient solutions for spatiotemporal traffic data imputation and prediction tasks.


<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

