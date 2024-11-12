---
layout: default
title: "Talks & Trainings"
---

<section class="portfolio" id="talks">
    <h2 class="section_title">Talks & Trainings</h2>
    <div class="box portfolio_box">
        {% for talk in site.data.talks %}
            {% include talk_card.html talk=talk %}
        {% endfor %}
    </div>
</section>

## Minor change
