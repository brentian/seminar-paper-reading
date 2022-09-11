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


## Organizers

{% assign organizers = site.staffers | where: 'role', 'Organizer' %}
{% assign num_organizers = organizers | size %}
{% if num_organizers != 0 %}
{% for staffer in organizers %}
{{ staffer }}
{% endfor %}
{% endif %}
