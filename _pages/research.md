---
layout: archive
permalink: /research/
author_profile: true
---

Please visit [my KU Leuven page](https://lirias.kuleuven.be/cv?Username=u0043788) for full overview and details of output. 
<br>
Contributions are labelled below according to research topics and acronyms.

| Topic        | Acronym | 
| :----------- | :------ |
| Claims reserving non-life insurance |   ClResNLI   | 
| Mortality modelling | MoMo|
| Insurance data science | IDS |
| Non-life insurance pricing | NonLifeIP |
| Insurance fraud risk modelling | IFRM |
| Loss modelling | LossM |
| Data science for operations mgmt | DSOpsMa|
| Algorithmic fairness | AlgoFair|
| Workers' compensation insurance | WorkComp|
| Motor insurance | Motor |
| Life insurance | Life |


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

