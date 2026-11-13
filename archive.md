---
layout: page
title: Regulation archive
description: Every aviation regulation explained in plain English — 14 CFR, Part 107, NTSB 830. One rule a day, indexed and searchable by section number.
permalink: /archive/
---

Every regulation explained so far, newest first. One rule a day, in plain
English — with the full offline text always available in
[FAR AIM Pocket](https://play.google.com/store/apps/details?id=com.faraimpocket.app).

<ul>
{% for post in site.posts %}
  <li>{{ post.date | date: "%b %-d, %Y" }} —
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
