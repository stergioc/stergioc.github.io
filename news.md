---
layout: page
title: News
---

<div class="card border-0">
  {% assign news = site.news | sort: 'date' | reverse %}
  {% for new in news %}

  <div class="row">
    <div class="col-12 col-sm-3">
      <strong>{{ new.date | date: "%d %b %Y"}}</strong>
    </div>
    <div class="col-12 col-sm-9">
      {{ new.content }}
    </div>
  </div>

  {% endfor %}
</div>

<!-- <h1 class="mb-5 display-4" style="font-size: x-large;"> Social Feed </h1>

  <script type="module" src="https://cdn.jsdelivr.net/npm/bsky-embed/dist/bsky-embed.es.js" async></script>
  <bsky-embed
    username="stergioc.bsky.social"
    mode="dark"
    limit="5"
    load-more="true"
  >
  </bsky-embed> -->