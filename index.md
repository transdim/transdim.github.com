---
layout: page
title: About author
cover: false
---

Hi, I am Xinyu Chen, a Ph.D. candidate at Polytechnique Montreal affiliated with University of Montreal. Currently, I am leading an innovative and interesting GitHub project. That is **transdim** (GitHub repository: [https://github.com/xinychen/transdim](https://github.com/xinychen/transdim)), which is a problem-oriented project for **trans**portation **d**ata **im**putation. It has covered the Python implementation of a manifold of machine learning models. In the meanwhile, my collaborators have developed some tensor learning models with me for spatiotemporal data imputation and forecasting.


## News
* **2020/05**: transdim gets [300+ stars](https://github.com/xinychen/transdim/stargazers) and [100+ forks](https://github.com/xinychen/transdim/network/members) on GitHub.
* **2020/05**: Paper "A nonconvex low-rank tensor completion for spatiotemporal traffic data imputation" (authors: Xinyu Chen, Jinming Yang, [Lijun Sun](https://lijunsun.github.io/)) is accepted by the journal [*Transportation Research Part C: Emerging Technologies*](https://www.journals.elsevier.com/transportation-research-part-c-emerging-technologies/). The Python implementation is available at [Imputation-LRTC-TNN.ipynb](https://nbviewer.jupyter.org/github/xinychen/transdim/blob/master/experiments/Imputation-LRTC-TNN.ipynb).
* **2020/03**: transdim project is awarded by [IVADO Excellence PhD funding](https://ivado.ca/en/ivado-scholarships/excellence-scholarships-phd/) (proposal: "City-scale traffic data imputation and forecasting with tensor learning").
* **2018/09**: Xinyu Chen starts transdim project with personal interest at Sun Yat-Sen University. He thinks *transdim project would help a lot for the research community*.

## Highlights

- Several publicly available spatiotemporal **data sets** ([data set list](https://github.com/xinychen/transdim/tree/master/datasets))
- Two standard **data modeling problems** (imputation & prediction)
- A number of **machine learning solutions** (baseline models & newly proposed solutions)
- Well-documented **Python implementation** on Jupyter Notebook


<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

