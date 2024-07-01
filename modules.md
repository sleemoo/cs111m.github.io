---
layout: page
title: Modules
nav_order: 2
description: Listing of course modules and topics week by week
has_children: true
---

# Week by Week
# Change this to be a TOC of the weekly topics

{% for module in site.modules %}
{{ module }}
{% endfor %}
