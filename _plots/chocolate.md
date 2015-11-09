---
title: "Chocolate"
layout: default
---

Hello world

I should produce an index.html file at website forward slash plot/chocolate... and I do

Debugging the collection info in site.collections tag gives:

    {% for collection in site.collections %}
    <section>
        <h1><a href="{{ collection.directory }}">{{ collection.title }}</a></h1>
        Label: {{ collection.label }}
    </section>
{% endfor %}

Check out /plot/box/chocolate for how this renders as HTML
