---
layout: default
---

# Programm

## 9:00 bis 9:50

<div class="card-deck">
{% for page in site.pages %}
	{% if page.page-category == "session" and page.slot == "S0900" %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
{% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url  %}
	{% endif %}
{% endfor %}
</div>

## 10:00 bis 10:50

<div class="card-deck">
{% for page in site.pages %}
	{% if page.page-category == "session" and page.slot == "S1000" %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
{% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url  %}
	{% endif %}
{% endfor %}
</div>

## 11:10 bis 12:00

<div class="card-deck">
{% for page in site.pages %}
	{% if page.page-category == "session" and page.slot == "S1100" %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
{% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url  %}
	{% endif %}
{% endfor %}
</div>

## 12:00 - 12:45 Mittagspause

## 12:45 bis 13:35

<div class="card-deck">
{% for page in site.pages %}
	{% if page.page-category == "session" and page.slot == "S1300" %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
{% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url  %}
	{% endif %}
{% endfor %}
</div>

## 13:45 bis 14:35

<div class="card-deck">
{% for page in site.pages %}
	{% if page.page-category == "session" and page.slot == "S1400" %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
{% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url  %}
	{% endif %}
{% endfor %}
</div>

## 14:45 bis 15:35

<div class="card-deck">
{% for page in site.pages %}
	{% if page.page-category == "session" and page.slot == "S1500" %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
{% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url  %}
	{% endif %}
{% endfor %}
</div>

## 15:45 bis 16:00

<div class="card-deck">
{% for page in site.pages %}
	{% if page.page-category == "session" and page.slot == "S1600" %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
{% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url  %}
	{% endif %}
{% endfor %}
</div>