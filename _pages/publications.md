---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<div class="archive">
    <h1 class="page__title">Current Projects</h1>
    <div class="list__item">
        
    </div>
</div>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
