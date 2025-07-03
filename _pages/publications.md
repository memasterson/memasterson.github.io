---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Below is a list of my first-author publications. For the full list of my publications, please see my 
<a href="https://memasterson.github.io/files/Masterson_CV_June2025.pdf">CV</a>.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
