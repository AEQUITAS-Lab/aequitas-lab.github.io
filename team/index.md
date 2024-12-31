---
title: Team
nav:
  order: 3
---

# {% include icon.html icon="fa-solid fa-people-group" %}Team


{% include section.html %}

## Current Members

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: doc, group: " %}
{% include list.html data="members" component="portrait" filters="role: ms, group: " %}
{% include list.html data="members" component="portrait" filters="role: ug, group: " %}
{% include list.html data="members" component="portrait" filters="role: visitor, group: " %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filters="group: alum" style="small" %}
