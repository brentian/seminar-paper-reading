---
layout: page
title: Schedule
description: The weekly event schedule.
---

# Weekly Schedule
The schedule will be finalized by Tencent Meeting links. 
{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
