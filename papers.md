---
layout: page
title:  Papers
cover:  false
menu:   true
order:  4
---

> **transdim** project is from the following papers, please cite these papers if they help your research.



<ul>
{% for paper in site.data.papers.papers %}
  <li>
  {% include paper.html paper=paper %}
  </li>
{% endfor %}
</ul>

