---
layout: archive
permalink: /research/
author_profile: true
title: " "
---

## Working papers, publications and external reports

Find below: [working papers](/research/#working-papers), [published papers](/research/#publications) in refereed journals and [external reports](/research/#external-reports). Contributions are labelled according to the following research topics and acronyms. 

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
| Telematics insurance | Tele |


## <span>Working papers</span>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'workingpaper' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


## <span>Publications</span>

Please visit [my KU Leuven page](https://lirias.kuleuven.be/cv?Username=u0043788) for full overview and details of output.  

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

