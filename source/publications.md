---
layout: pages
title: Publications
permalink: /publications/
---

<section class="post-list">
  {% for post in site.publications reversed %}
    {% include article.html %}
  {% endfor %}
</section>
