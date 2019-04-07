---
title: Links
layout: flex
menu: Links
---

{::options parse_block_html="true" /}

<div style="width:100%">
# Links
</div>

{% for link in site.links %}

<div style="width:20%">
<img src="{{link.image}}" alt="{{link.title}}" style="border: 0px;max-height:80px;">
</div>
<div style="width:65%">
<a href="{{link.url}}">{{link.title}}</a>
{{link.description}}
</div>
{% endfor %}
