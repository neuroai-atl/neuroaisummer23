---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

## Faculty Organizers

{% assign instructors = site.staffers | where: 'role', 'Faculty Organizer' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}


## Teaching Assistants

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
