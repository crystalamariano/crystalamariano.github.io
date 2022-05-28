---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

Respiratory illnesses are among the leading causes of morbidity and mortality worldwide. Chronic pulmonary disease can result in irreversible lung tissue damage where mechanical ventilation is often the only means of intervention, as witnessed during the COVID-19 pandemic. Modern ventilators push air into the lungs to deliver oxygen using positive pressure, which can cause further lung damage as it contradicts the way we naturally breathe.

My research aims to use digital image correlation to assess how ventilation techniques affect local pulmonary mechanics while simultaneously characterizing the relationship of lung mechanics to natural and artificial breathing. This includes ex-vivo lung experiments that will inform the development of alternative, more effective ventilation strategies.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
