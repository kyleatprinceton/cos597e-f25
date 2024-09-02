---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

With one exception[^1] all meetings are in-person, Fridays 
1:30&ndash;4:30&nbsp;PM in 302 Computer Science.

Readings marked **Paper Discussion**{: .label .label-purple } are for
[pre-reading and e-discussion]({{ "/readings" | relative_url }})
by midnight Thursday
and student [presentation]({{ "/paperpres" | relative_url}})
in our Friday meetings.
Readings marked **Pre-Read**{: .label .label-green } are for
pre-reading by Friday.  Readings not marked as such are either covered
in our meeting or are supporting material to refer to after
meeting.

{% for module in site.modules %}
{{ module }}
{% endfor %}


{: .note}
This calendar is preliminary and subject to revision.  

[^1]: We will meet at the regular time on Tuesday of Thanksgiving week (November 26), which follows a Friday meeting pattern.
