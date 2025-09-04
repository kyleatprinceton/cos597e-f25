---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

<!-- With one exception[^1] --> All meetings are in-person, Tuesdays
and Thursdays 3:00&ndash;4:15&nbsp;PM in Room 301 Computer Science.

Readings marked **Paper Discussion**{: .label .label-purple } are for
[pre-reading and e-discussion]({{ "/readings" | relative_url }})
by midnight before meeting
and student [presentation]({{ "/paperpres" | relative_url}})
in meeting.
Readings marked **Pre-Read**{: .label .label-green } are for
pre-reading before meeting.  Readings not marked as such are either covered
in our meeting or are supporting material to refer to after
meeting.

{% for module in site.modules %}
{{ module }}
{% endfor %}


{: .note}
This calendar is preliminary and subject to revision.  

<!-- [^1]: We will meet at the regular time on Tuesday of Thanksgiving
week (November 26), which follows a Friday meeting pattern. -->
