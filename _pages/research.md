---
layout: archive
permalink: /research/
author_profile: true
title: " "
---

## Featured lab publications

<div class="paper-grid">

  <a href="https://doi.org/10.1016/j.insmatheco.2017.08.005">
    <img src="/images/papers/IME-1.png" alt="IME paper">
    <div class="paper-caption">
 IME (2017)&nbsp; →
</div>
  </a>

  <a href="https://doi.org/10.1111/rssc.12283">
    <img src="/images/papers/JRSSC-1.png" alt="JRSS C paper">
    <div class="paper-caption">
 JRSS C (2019)&nbsp; →
</div>
  </a>

  <a href="https://projecteuclid.org/journals/statistical-science/volume-37/issue-3/Modeling-the-Occurrence-of-Events-Subject-to-a-Reporting-Delay/10.1214/21-STS831.pdf">
    <img src="/images/papers/StatScience-1.png" alt="Stat Science paper">
    <div class="paper-caption">
 Stat Science (2021)&nbsp; →
</div>
  </a>

  <a href="https://doi.org/10.1017/asb.2023.14">
    <img src="/images/papers/ASTIN.png" alt="ASTIN paper">
        <div class="paper-caption">
 ASTIN (2023)&nbsp; →
</div>
  </a>

  <a href="https://www.tandfonline.com/doi/full/10.1080/10920277.2025.2451860">
    <img src="/images/papers/NAAJ.png" alt="NAAJ paper">
    <div class="paper-caption">
 NAAJ (2025)&nbsp; →
</div>
  </a>

  <a href="https://doi.org/10.1093/jrsssa/qnaf052">
    <img src="/images/papers/JRSSA.png" alt="JRSS A paper">
    <div class="paper-caption">
 JRSS A (2026)&nbsp; →
</div>
  </a>

</div>

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

