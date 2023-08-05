---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

## Faculty Organizers

{% assign instructors = site.staffers | where: 'role', 'Assistant Professor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign instructors = site.staffers | where: 'role', 'Associate Professor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Teaching Assistants

{% assign teaching_assistants = site.staffers | where: 'role', 'Graduate Student' %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Research Specialist' %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Postdoctoral Researcher' %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
