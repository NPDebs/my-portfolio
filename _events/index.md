---
layout: default
title: "Events"
---

<h2>Events</h2>
{% for event in site.data.events %}
  <div class="event">
    <h3>{{ event.title }}</h3>
    <p>{{ event.description }}</p>
    <a href="{{ event.link }}">Read more</a>
  </div>
{% endfor %}
