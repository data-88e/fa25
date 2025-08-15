---
layout: page
title: Data 88E Home
nav_exclude: true
permalink: /
seo:
  type: Course
  name: Data 88E
---

# Data 88E: Economic Models

{: .mb-2 }
UC Berkeley, Fall 2025
{: .mb-0 .fs-6 .text-grey-dk-000 }

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% for module in site.modules %}
{{ module }}
{% endfor %}
