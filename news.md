---
layout: default
title: News
permalink: /news/
---
<div class="page news-page">
<p class="eyebrow">NEWS</p>
# Lab News
<p class="news-page-lead">Updates from MAS Lab—research, people, academic activities, and the communities we learn from.</p>
<div class="news-grid">
{% assign sorted_news = site.news | sort: 'date' | reverse %}
{% for post in sorted_news %}
  <a class="news-card{% unless post.image %} news-card-text-only{% endunless %}" href="{{ post.url | relative_url }}">
    {% if post.image %}
      <div class="news-card-media">
        <img src="{{ post.image | relative_url }}" alt="{{ post.image_alt | default: post.title }}" loading="lazy">
      </div>
    {% endif %}
    <div class="news-card-body">
      <div class="news-date">{{ post.date | date: "%Y.%m.%d" }}</div>
      <h3>{{ post.title }}</h3>
      <div class="muted">{{ post.excerpt | strip_html | truncatewords: 28 }}</div>
      <span class="news-read-more">Read story →</span>
    </div>
  </a>
{% endfor %}
</div>
</div>
