---
layout: home
title: DaRMoD
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: DaRMoD
---

## Welcome to the Data Readiness, Model Development, and Model Deployment (DaRMoD) program

## Recent Announcements

{% assign num_recent_announcements = 2 %}
{% assign all_announcements = site.announcements | sort: "date" | reverse %}
{% for announcement in all_announcements limit: num_recent_announcements %}
{{ announcement }}
{% endfor %}
[See All Announcements](#all-announcements){: .btn .btn-outline}

### About Vector Institute

In March 2017, Canada was the first country in the world to announce a national strategy for AI — the Pan-Canadian AI Strategy — with a $125 million investment by the federal government. As a result, Vector Institute was founded to drive excellence and leadership in Canada’s knowledge, creation, and use of AI to foster economic growth and improve the lives of Canadians. Vector works with industry, institutions, start-ups, and government to advance AI research and drive its application, adoption and commercialization across Canada.

Vector’s scientific network currently includes 500+ active researchers with expertise in machine learning and deep learning, including faculty members, postdoctoral fellows, graduate researchers and affiliates from across Canada, many of whom claim top prizes from the world’s most important conferences and journals

## All Announcements

{% for announcement in all_announcements %}
{{ announcement }}
{% endfor %}
