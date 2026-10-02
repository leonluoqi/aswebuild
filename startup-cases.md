---
layout: single
title: "北美创业案例"
permalink: /北美创业案例/
author_profile: true
---

{% assign matched_posts = "" | split: "" %}

{% for post in site.posts %}
  {% if post.tags contains "北美创业案例" or post.tags contains "创业案例" or post.tags contains "加拿大创业案例" or post.tags contains "创业案例分析" or post.tags contains "北美创业" or post.tags contains "加拿大创业" %}
    {% assign matched_posts = matched_posts | push: post %}
  {% endif %}
{% endfor %}

{% assign matched_posts = matched_posts | uniq %}

<ul>
{% for post in matched_posts %}
  <li style="margin-bottom: 10px; line-height: 1.6;">
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span style="font-size: 0.85em; color: #888; margin-left: 8px;">({{ post.date | date: "%Y-%m-%d" }})</span>
  </li>
{% endfor %}
</ul>