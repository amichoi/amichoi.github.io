---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

You can find my articles on **[my Google Scholar profile.](https://scholar.google.com/citations?user=0Yx2f9kAAAAJ&hl=en)**

I have contributed to several survey collaborations since 2004. Thus, many of my authorships are due to infrastructure work enabling a wide range of science.  Here, I list papers for which I made substantial contributions specific to the papers themselves.  Click on the paper title to get more information about the paper contents and a description of my role.

{% for post in site.publications reversed %}
 {% include archive-single.html %}
{% endfor %}
