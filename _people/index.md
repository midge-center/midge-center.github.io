---
layout: index_page
category: people
title: People
---

The members of the MIDGE Center represent a diverse array of backgrounds, interests, and goals.

{% assign page_array = site.people | where:"status", "current"		%}
{% include picture_grid.html pages=page_array columns=4	%}
