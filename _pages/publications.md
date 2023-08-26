---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can find a full list of my publications from:
    * <a href="{{author.inspire}}">iNSPIRE profile</a>
    * <a href="{{site.author.googlescholar}}">Google Scholar profile</a>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
