---
layout: archive
permalink: /talkmap/
author_profile: true
---

Please visit [my KU Leuven page](https://lirias.kuleuven.be/cv?Username=u0043788) for full overview and details of output. 
Few selected talks are listed below.

## Upcoming talks

I will present at: University of Barcelona (March 2026), Warsaw School of Economics (in September 2025).

## Examples of past talks, keynotes, seminars

{% for post in site.publications reversed %}
  {% if post.pubtype == 'keynote' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

