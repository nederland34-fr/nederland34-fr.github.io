---
title: Medelanders
menu: Medelanders
layout: flex
---

{::options parse_block_html="true" /}

<div style="width:100%">
# Medelanders
</div>

{% assign sorted_pages = site.medelanders %}

{% for medelander in sorted_pages %}

<div style="width:45%;border-top: 1px solid grey;margin-bottom:20px">
   <h2>{{medelander.title}}</h2>
   <p><i>{{medelander.description}}</i> <a href="{{medelander.url}}">Lees verder ...</a></p>
</div>
{% endfor %}
