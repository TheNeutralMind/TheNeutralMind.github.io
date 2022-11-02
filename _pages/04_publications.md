---
layout: page
title: Publications
permalink: /publications/
toggle: on
rank: 2
---

<h2>Preprints</h2>

<!-- Preprints -->
<div class="lab-wrapper">
    <body class="lab-list">
    {% for pub in site.data.pubs %}
        {% if pub.type == 'preprint' %}
            {% include pub_entry.html %}
        {% endif %}
    {% endfor %}
    </body>
</div>

<h2>2022</h2>

<div class="lab-wrapper">
    <body class="lab-list">
    {% for pub in site.data.pubs %}
        {% if pub.year == '2022' and pub.type != 'preprint' %}
            {% include pub_entry.html %}
        {% endif %}
    {% endfor %}
    </body>
</div>

<h2>2021</h2>

<!-- Preprints -->
<div class="lab-wrapper">
    <body class="lab-list">
    {% for pub in site.data.pubs %}
        {% if pub.year == '2021' and pub.type != 'preprint' %}
            {% include pub_entry.html %}
        {% endif %}
    {% endfor %}
    </body>
</div>