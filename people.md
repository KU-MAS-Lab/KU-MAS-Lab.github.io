---
layout: default
title: People
permalink: /people/
---
<div class="page">
<p class="eyebrow">PEOPLE</p>
# Our Team
<p class="ko-summary" lang="ko">MAS Lab은 의료영상 기술 개발을 중심으로 영상물리·하드웨어·신호 및 영상처리·AI를 연결합니다. 새로운 영상으로 생체 변화를 정량화하고 초음파 자극·치료 연구에도 도전합니다.</p>
<div class="member-grid">
{% assign sorted_members = site.members | sort: 'order' %}
{% for member in sorted_members %}
{% unless member.status == 'incoming' %}
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
{% endunless %}
{% endfor %}
</div>

<section class="incoming-team" aria-labelledby="incoming-team-title">
  <p class="eyebrow">JOINING JANUARY 2027</p>
  <h2 id="incoming-team-title">Incoming Undergraduate Researchers</h2>
  <p class="incoming-team-intro">Our incoming undergraduate researchers will join MAS Lab in Winter 2027.</p>
  <div class="member-grid">
  {% for member in sorted_members %}
  {% if member.status == 'incoming' %}
    <a class="member-card incoming-member-card" href="{{ member.url | relative_url }}">
      {% if member.photo %}
        <img class="member-avatar" src="{{ member.photo | relative_url }}" alt="{{ member.name }}">
      {% else %}
        <div class="member-avatar member-placeholder" aria-label="Photo coming soon">{{ member.name | slice: 0 }}</div>
      {% endif %}
      <strong>{{ member.name }}</strong>
      <div class="member-role">{{ member.role }}</div>
      <p class="incoming-affiliation">{{ member.affiliation }}</p>
      {% if member.research_interests %}<p class="incoming-interest"><b>Research:</b> {{ member.research_interests }}</p>{% endif %}
      {% if member.award %}<p class="incoming-award">{{ member.award }}</p>{% endif %}
    </a>
  {% endif %}
  {% endfor %}
  </div>
</section>
<div class="member-grid recruiting-grid">
  <div class="member-card recruiting-card">

  <div class="member-info">
    <div class="recruiting-label">OPEN POSITIONS</div>

    <h3>We are recruiting!</h3>

    <p class="recruiting-positions">
      Undergraduate Researchers · M.S. · Ph.D. Students
    </p>

    <p>
      Interested in medical imaging, AI, instrumentation, or ultrasound therapeutics?
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
