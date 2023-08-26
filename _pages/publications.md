---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

## You can find a full list of my publications from:
* [iNSPIRE profile]({{site.author.inspire}})
* [Google Scholar profile]({{site.author.googlescholar}})

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
