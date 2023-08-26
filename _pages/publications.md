---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>

{% if author.inspire %}
  You can also find my articles on <u><a href="{{author.inspire}}">my iNSPIRE profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
