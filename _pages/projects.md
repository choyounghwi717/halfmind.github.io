---
title: "프로젝트 (Projects)"
permalink: /projects/
layout: archive
author_profile: true
sidebar:
  nav: "docs"
---

{% if site.posts.size == 0 %}
  <p class="notice--warning">아직 발행된 글이 없거나, 날짜/태그 설정 오류로 글이 숨겨졌습니다.</p>
{% else %}
  <div class="entries-grid">
    {% for post in site.posts %}
      {% include archive-single.html type="grid" %}
    {% endfor %}
  </div>
{% endif %}
