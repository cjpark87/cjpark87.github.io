---
layout: archive
#title: "Publications"
permalink: /publications/
#author_profile: true
---

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single-projects.html %}
{% endfor %}

{% for post in site.publications reversed %}
  {% include archive-single-publications.html %}
{% endfor %}
