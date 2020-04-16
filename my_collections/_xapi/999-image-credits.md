---
title: Image credits
subtitle: 
hasChildren: false
backgroundImage:
---
<table>
    <thead>
        <th>Page</th>
        <th>Credit</th>
    </thead>
    <tbody>
{% for slide in site.xapi %}
    {% if slide.backgroundImageCredit %}
    <tr>
        <td>{{ slide.title }}</td>
        <td><a href="{{ slide.backgroundImageSourceURL}}" target="_blank">{{ slide.backgroundImageCredit }}</a></td>
    </tr>
    {% endif %}
{% endfor %}
</tbody>
</table>