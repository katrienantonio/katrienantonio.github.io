---
layout: archive
permalink: /talkmap/
author_profile: true
---

Please visit [my KU Leuven page](https://lirias.kuleuven.be/cv?Username=u0043788) for full overview and details of output. 
Few selected talks are listed below.

## Upcoming talks

I will present at: Verbond Van Verzekeraars (October 2026), University of Luxembourg and Institute of Actuaries in Luxembourg (October 2026), assembly of the German actuarial association in Mannheim (November 2026).

## Examples of past talks, keynotes, seminars

{% for post in site.publications reversed %}
  {% if post.pubtype == 'keynote' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

