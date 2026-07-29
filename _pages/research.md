---
layout: archive
permalink: /research/
author_profile: true
title: " "
---

## Featured lab publications

<table style="border:none; margin:auto; border-collapse:collapse;">
<tr>

<td align="center" style="border:none; padding:5px;">
<img src="/images/papers/IME.png"
     style="height:240px; width:auto; border:1px solid #d9d9d9;">
<br>
<a href="https://doi.org/10.1016/j.insmatheco.2017.08.005">
<em>In IME (2017)</em> →
</a>
</td>

<td align="center" style="border:none; padding:5px;">
<img src="/images/papers/telematics.png"
     style="height:240px; width:auto; border:1px solid #d9d9d9;">
<br>
<a href="https://doi.org/10.1111/rssc.12283">
<em>In JRSS C (2019)</em> →
</a>
</td>


<td align="center" style="border:none; padding:5px;">
<img src="/images/papers/StatScience.png"
     style="height:240px; width:auto; border:1px solid #d9d9d9;">
<br>
<a href="https://projecteuclid.org/journals/statistical-science/volume-37/issue-3/Modeling-the-Occurrence-of-Events-Subject-to-a-Reporting-Delay/10.1214/21-STS831.pdf">
<em>In Statistical Science (2022)</em> →
</a>
</td>


</tr>

<tr>

<td align="center" style="border:none; padding:5px;">
<img src="/images/papers/ASTIN.png"
     style="height:240px; width:auto; border:1px solid #d9d9d9;">
<br>
<a href="https://doi.org/10.1017/asb.2023.14">
<em>In ASTIN Bulletin (2023)</em> →
</a>
</td>

<td align="center" style="border:none; padding:5px;">
<img src="/images/papers/NAAJ.png"
     style="height:240px; width:auto; border:1px solid #d9d9d9;">
<br>
<a href="https://www.tandfonline.com/doi/full/10.1080/10920277.2025.2451860">
<em>In NAAJ (2025)</em> →
</a>
</td>

<td align="center" style="border:none; padding:5px;">
<img src="/images/papers/jrssa.png"
     style="height:240px; width:auto; border:1px solid #d9d9d9;">
<br>
<a href="https://doi.org/10.1093/jrsssa/qnaf052">
<em>In JRSS A (2026)</em> →
</a>
<br>
</td>

</tr>
</table>

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

