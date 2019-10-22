---
layout: archive
#title: "Publications"
permalink: /publications/
#author_profile: true
---

{% include base_path %}

<h2>Current Projects</h2>
{% for post in site.projects reversed %}
  {% include archive-single-projects.html %}
{% endfor %}

<h2>Publications</h2>

{% for post in site.publications reversed %}
  {% include archive-single-publications.html %}
{% endfor %}
