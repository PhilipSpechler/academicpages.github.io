---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
Please see my CV for complete publication record:<a href="https://philipspechler.github.io/files/Philip_Spechler_CV_2018.pdf"> 
Click Here </a>  

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
