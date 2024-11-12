---
layout: default
title: "Home"
---

{% include about.html %}
{% include featured.html %}

<section class="portfolio" id="portfolio">
    <h2 class="section_title">Portfolio</h2>
    <h4 class="section_subtitle">Most Recent Work</h4>
    <div class="box portfolio_box">
        {% for item in site.data.portfolio %}
            {% include portfolio_card.html item=item %}
        {% endfor %}
    </div>
</section>

<div class="contact-me" id="contact">
    <p>Want to collaborate on a project?</p>
    <a class="button" href="mailto:{{ site.email }}" target="_parent">Contact Me!</a>
</div>
    
