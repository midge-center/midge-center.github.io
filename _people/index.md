---
layout: index_page
category: people
title: People
---

The members of the MIDGE Center represent a diverse array of backgrounds, interests, and goals.

### Viruses
{% assign page_array = site.people | where:"status", "virus"    %}
{% include picture_grid.html pages=page_array columns=4	%}

### Bacteria
{% assign page_array = site.people | where:"status", "bacteria" %}
{% include picture_grid.html pages=page_array columns=4	%}

### Fungi
{% assign page_array = site.people | where:"status", "fungus"   %}
{% include picture_grid.html pages=page_array columns=4	%}

### Technology & Data Core
{% assign page_array = site.people | where:"status", "tech"     %}
{% include picture_grid.html pages=page_array columns=4	%}

### Administrative Core
{% assign page_array = site.people | where:"status", "admin"    %}
{% include picture_grid.html pages=page_array columns=4	%}
