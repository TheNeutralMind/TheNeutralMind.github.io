---
layout: page
title: Publications
permalink: /publications/
toggle: on
rank: 2
---

\* Equal contributions


<div class="lab-wrapper">
    <body class="lab-list">
    {% for pub in site.data.pubs %}
	    {% if pub.header %}
            {{ pub.header }}
        {% endif %}
        {% if pub.year and pub.type != 'press' %}
            {% include pub_entry.html %}
        {% endif %}
		
		{% if pub.type == 'press' %}
            {% include press_entry.html %}
        {% endif %}
		
    {% endfor %}
    </body>
</div>
