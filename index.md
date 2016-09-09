---
layout: default
title: Work
---

<div class="pure-g">
  <div class="pure-u-1 pure-u-md-1-2 bg-1">
		<div class="padded-box">
{% include home_cta.md %}  
		</div>
  </div>
  <div class="pure-u-1 pure-u-md-1-2" markdown="1">
{% for item in site.data.testimonials %}
> {{ item.quote }}
>
><em>
>![{{ item.name }}](/resources/images/testimonials/{{ item.image  }}) 
>{{ item.name }}
><br />
>{{ item.title }} at [{{ item.company }}]( {{ item.url }} )
></em>
>
{% endfor %}
  </div>
</div>

{% include home-popup.html %}
