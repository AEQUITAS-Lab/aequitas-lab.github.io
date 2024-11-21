---
title: News
nav:
  order: 4
  tooltip:
---

# {% include icon.html icon="fa-regular fa-newspaper" %}News

{%
  include section.html
%}

{% 
  include list.html data="posts" component="post-excerpt" 
%}