---
layout: archive
permalink: /research/
author_profile: true
---

Please visit [my KU Leuven page](https://lirias.kuleuven.be/cv?Username=u0043788) for full overview and details of output.

## <span>Working papers</span>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'workingpaper' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


## <span>Publications</span>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'publication' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


## <span>External reports</span>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'external' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

