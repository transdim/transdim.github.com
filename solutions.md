---
layout: page
title:  Solutions
cover:  false
menu:   true
order:  2
---

> _I would have written a shorter letter, but I did not have the time._
>
> ---Blaise Pascal

<ul>
{% for paper in site.data.papers.papers %}
  <li>
  {% include paper.html paper=paper %}
  </li>
{% endfor %}
</ul>

