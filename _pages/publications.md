---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

#{% if author.googlescholar %}
#  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
#{% endif %}

see my publication list from [\[**Google Scholar**\]](https://scholar.google.com/citations?user=bGL6kUQAAAAJ&hl=en)
and [\[**ADS**\]](https://ui.adsabs.harvard.edu/user/libraries/PkFi6jPtRS-1GXEa9ugtGg).<br/>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
