---
permalink: /
#title: "Under construction"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am Chunjong "CJ" Park. I am a software enginner at Google Research, working at the intersection of multimodal LLMs and health. 

Prior to Google, I received PhD in Computer Science and Engineering at the <a href="https://www.cs.washington.edu/">University of Washington</a>, where I worked with <a href="https://homes.cs.washington.edu/~shwetak/">Shwetak Patel</a> in the <a href="https://ubicomplab.cs.washington.edu">Ubiquitous Computing Lab</a>. I recieved BS and MS in Computer Science at <a href="http://cs.kaist.ac.kr/">KAIST</a>, where I worked with <a href="https://sites.google.com/site/wewantsj/">Sung-Ju Lee</a>, <a href="https://juhokim.com/">Juho Kim</a>, <a href="https://nclab.kaist.ac.kr/professor_page.html">Junehwa Song</a>, and <a href="http://an.kaist.ac.kr/~sbmoon/">Sue Moon</a>.

<h2>Publications</h2>
<div class="archive">
{% for post in site.publications reversed %}
  {% include archive-single-publications.html %}
{% endfor %}
</div>
