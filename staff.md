---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign reader_tutor = site.staffers | where: 'role', 'Reader Tutor' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}


{% assign reader_tutor = site.staffers | where: 'role', 'Reader Tutor' %}
{% assign num_read_tutor = reader_tutor | size %}
{% if num_reader_tutor != 0 %}

## Reader / Tutor

{% for staffer in reader_tutor %}
{{ staffer }}
{% endfor %}
{% endif %}
