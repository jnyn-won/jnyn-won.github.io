---
title: "Git"
layout: archive
permalink: categories/git
author_profile: true
sidebar_main: true
published: true
---

{% assign posts = site.categories.git %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}