---
title: Historique
layout:  null
tab: true
order: 3
tags: OWASPQC
---

# 2020

{% assign page_event_2020 = site.pages | sort: 'name' | where_exp: "page", "page.path contains 'event/2020'" %}

{% for page in page_event_2020 %}
* [{{ page.title }}]({{site.baseurl }}{{ page.url }})
{% endfor %}



