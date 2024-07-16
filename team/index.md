---
title: Team
nav:
  order: 3
  tooltip: Our Team!
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

## Current Members
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi|alumni$)" %}

## Alumni
We will miss you guys!
{% include list.html data="members" component="portrait" filters="role: alum-postdoc, alum-phd, alum-ms, alum-undergrad" %}
