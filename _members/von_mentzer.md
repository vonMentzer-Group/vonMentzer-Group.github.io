---
name: Astrid von Mentzer
aliases:
  - Astrid von Mentzer
  - A. von Mentzer
  - A von mentzer
image: images/head_astrid.jpg
role: pi
links:
  orcid: 0000-0002-2167-1394
  email: astrid.von.mentzer@gu.se
  github: avonm
  twitter: miss_avonm
---

Astrid is....

{% include float.html clear=true %}

## All papers under von Mentzer's ORCID:

{% capture content %}

{% include list.html data="citations" component="citation" filters="member: von_mentzer" %}

{% endcapture %}

{% include grid.html content=content %}
