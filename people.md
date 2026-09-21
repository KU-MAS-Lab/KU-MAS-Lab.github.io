---
layout: default
title: People
permalink: /people/
---
<div class="page">
<p class="eyebrow">PEOPLE</p>
# Our Team
<p class="ko-summary" lang="ko">MAS Lab은 영상물리, 하드웨어, 신호·영상처리, AI, biomedical application이 서로 연결되는 연구를 함께 만들어갑니다.</p>
<div class="member-grid">
{% assign sorted_members = site.members | sort: 'order' %}
{% for member in sorted_members %}
  <a class="member-card" href="{{ member.url | relative_url }}">
    {% assign card_photo = member.card_photo | default: member.photo %}
    {% if card_photo %}
      <img class="member-avatar" src="{{ card_photo | relative_url }}" alt="{{ member.name }}">
    {% else %}
      <div class="member-avatar member-placeholder">{{ member.name | slice: 0 }}</div>
    {% endif %}
    <strong>{{ member.name }}</strong>
    <div class="member-role">{{ member.role }}</div>
    {% if member.hobbies %}
      <div class="member-hobbies"><span aria-hidden="true">⚡</span>{{ member.hobbies }}</div>
    {% endif %}
  </a>
{% endfor %}
  <div class="member-card recruiting-card">

  <div class="member-info">
    <div class="recruiting-label">OPEN POSITIONS</div>

    <h3>We are recruiting!</h3>

    <p class="recruiting-positions">
      Undergraduate Researchers · M.S. · Ph.D. Students
    </p>

    <p>
      Interested in imaging, AI, acoustics, or biomedical applications?
    </p>

    <p class="recruiting-ko">
      MAS Lab에서 함께 연구할 학부연구생 및 대학원생을 모집합니다.
    </p>

    <a class="recruiting-link" href="{{ '/join/' | relative_url }}">
      Join MAS Lab →
    </a>
  </div>
</div>
</div>
</div>
