---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
Please see <a href="https://philipspechler.github.io/files/Philip_Spechler_CV_October2018.pdf"> my CV</a> for complete publication record  
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
