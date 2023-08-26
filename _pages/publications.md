---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% if (site.author.inspire or site.author.googlescholar) %}
You can find a full list of my publications from:
    {% if author.inspire %}
    * <a href="{{author.inspire}}">iNSPIRE profile</a>
    {% endif %}
    {% if site.author.googlescholar}
    * <a href="{{site.author.googlescholar}}">Google Scholar profile</a>
    {% endif %}
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
