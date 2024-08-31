---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

This calendar is preliminary and subject to revision.  Readings marked
"Paper Discussion" are for E-Discussion by Thursday and student
presentation in our Friday meetings.  Readings not marked as such are
either covered in mini-lecture or supporting material.

{% for module in site.modules %}
{{ module }}
{% endfor %}
