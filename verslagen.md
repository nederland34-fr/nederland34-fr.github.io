---
title: Foto Verslagen
menu: Verslagen
layout: flex
---

{::options parse_block_html="true" /}

{% assign sorted_pages = site.verslagen | reverse %}

{% for verslag in sorted_pages %}

<div style="width:50%">
 <img src="{{verslag.image}}" alt="{{verslag.title}}" style="width:150px;height:100px;float:left;margin-right:20px">
   <a href="{{verslag.url}}">{{verslag.title}}</a>
   {{verslag.description}}
</div>
{% endfor %}
