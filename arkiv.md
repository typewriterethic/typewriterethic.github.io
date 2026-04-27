---
layout: default
title: Arkiv
permalink: /arkiv/
---

{% assign postsByYear = site.posts | group_by_exp: "post", "post.date | date: '%Y'" %}

{% for year in postsByYear %}
<section class="archive-year">
  <h2 class="archive-year__heading">{{ year.name }}</h2>
  <ul class="archive-list">
    {% for post in year.items %}
    <li class="archive-list__item">
      <time class="archive-list__date" datetime="{{ post.date | date_to_xmlschema }}">
        {{ post.date | date: "%-d. %b" }}
      </time>
      <a href="{{ post.url | relative_url }}" class="archive-list__title">{{ post.title }}</a>
    </li>
    {% endfor %}
  </ul>
</section>
{% endfor %}
