---
layout: default
---

{% assign pages = (site.pages | sort: "page-category" | reverse | where_exp: "page", "page.page-category == 'session' or page.page-category == 'junior-session'")  %}

# Programm

<div class="program">
<h2>9:00 bis 9:50</h2>

<div class="card-deck">
{% assign slotPages = (pages | where: "slot", "S0900") %}
{% for page in slotPages %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
        {% capture page-category %}{{ page.page-category }}{% endcapture %}
        {% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url page-category=page-category  %}
{% endfor %}
</div>

<h2>10:00 bis 10:50</h2>

<div class="card-deck">
{% assign slotPages = (pages | where: "slot", "S1000") %}
{% for page in slotPages %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
        {% capture page-category %}{{ page.page-category }}{% endcapture %}
        {% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url page-category=page-category  %}
{% endfor %}
</div>

<h2>11:10 bis 12:00</h2>

<div class="card-deck">
{% assign slotPages = (pages | where: "slot", "S1100") %}
{% for page in slotPages %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
        {% capture page-category %}{{ page.page-category }}{% endcapture %}
        {% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url page-category=page-category  %}
{% endfor %}
</div>

<h2>12:00 - 12:45 Mittagspause</h2>

<h2>12:45 bis 13:35</h2>

<div class="card-deck">
{% assign slotPages = (pages | where: "slot", "S1300") %}
{% for page in slotPages %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
        {% capture page-category %}{{ page.page-category }}{% endcapture %}
        {% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url page-category=page-category  %}
{% endfor %}
</div>

<h2>13:45 bis 14:35</h2>

<div class="card-deck">
{% assign slotPages = (pages | where: "slot", "S1400") %}
{% for page in slotPages %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
        {% capture page-category %}{{ page.page-category }}{% endcapture %}
        {% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url page-category=page-category  %}
{% endfor %}
</div>

<h2>14:45 bis 15:35</h2>

<div class="card-deck">
{% assign slotPages = (pages | where: "slot", "S1500") %}
{% for page in slotPages %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
        {% capture page-category %}{{ page.page-category }}{% endcapture %}
        {% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url page-category=page-category  %}
{% endfor %}
</div>

<h2>15:45 bis 16:00</h2>

<div class="card-deck">
{% assign slotPages = (pages | where: "slot", "S1600") %}
{% for page in slotPages %}
        {% capture title %}{{ page.title }}{% endcapture %}
        {% capture speaker %}{{ page.speaker }}{% endcapture %}
        {% capture speaker-id %}{{ page.speaker-id }}{% endcapture %}
        {% capture room %}{{ page.room }}{% endcapture %}
        {% capture url %}{{ page.url }}{% endcapture %}
        {% capture page-category %}{{ page.page-category }}{% endcapture %}
        {% include card.html title=title speaker=speaker speaker-id=speaker-id room=room url=url page-category=page-category  %}
{% endfor %}
</div>
</div>