---
layout: default
title: "Events"
---

<section class="portfolio" id="events">
    <h2 class="section_title">Events</h2>
    <div class="box portfolio_box">
        {% for event in site.data.events %}
            {% include event_card.html event=event %}
        {% endfor %}
    </div>
</section>
