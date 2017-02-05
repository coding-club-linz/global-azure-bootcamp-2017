---
layout: default
---

# Programm!

## 9:00 bis 9:50

<div class="card-columns">
{% for page in site.pages %}
	{% if page.page-category == "session" and page.slot == "S0900" %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
{% include card.html title=title speaker=speaker room=room url=url  %}
	{% endif %}
{% endfor %}
</div>

## 10:00 bis 10:50

<div class="card-columns">
{% for page in site.pages %}
	{% if page.page-category == "session" and page.slot == "S1000" %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
{% include card.html title=title speaker=speaker room=room url=url  %}
	{% endif %}
{% endfor %}
</div>