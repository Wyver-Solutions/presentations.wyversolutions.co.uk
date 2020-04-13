---
title: Image credits
subtitle: 
hasChildren: false
backgroundImage:
---
{% for slide in site.ufiwebinar %}
{% if slide.backgroundImage %}
{{ slide.title }}: <a href="{{ slide.backgroundImageSourceURL}}" target="_blank">{{ slide.backgroundImageCredit }}</a>
{% endif %}
{% endfor %}