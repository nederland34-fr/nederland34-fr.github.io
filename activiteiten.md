---
title: Activiteiten
menu: Activiteiten
layout: flex
---

{::options parse_block_html="true" /}

{% for activiteit in site.activiteiten %}

<div style="width:30%;margin-right:20px;">
<img src="{{activiteit.image}}" alt="{{activiteit.title}}" >
</div>
<div style="width:50%">
## {{activiteit.title}}

{{activiteit.description}}

<a href="{{activiteit.url}}">Lees verder ...</a>

</div>
{% endfor %}
