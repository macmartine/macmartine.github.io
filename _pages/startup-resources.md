---
layout: default
title: Startup development and asset resources
permalink: /startup-resources/
---
<div class='pure-g'>
<div class='pure-u-1' markdown='1'>

### {{ page.title }}

Below are the best resources I'm aware of for some of the various needs of startups.
Many of these are development resources such as hosting, and website and application templtes,
but there are also asset resources, such as the best places to find (free!) stock photography,
fonts, email teplates and more. You'll also find indispensable tools for building email ists, and more.

This list has a strong emphasis on easy-to-use, and affordability. In building a Lean Startup,
we need tools to help us be more effecient and more effective, not depleting our cash.

</div>
</div>

<div class='pure-g'>
{% for category in site.data.resources.categories %}

  <div class='pure-u-1'>
    <h3>
      {{ category.name }}
    </h3>
  </div>

  <div class='pure-u-1'>
    {% for item in category.items %}
      <div class="pure-g resource-item" >
        <div class="pure-u-1-3">
          <img src="/resources/images/resources/{{ item.image }}" />
        </div>
        <div class="pure-u-2-3">
          <a href="{{ item.url }}">
            {{ item.title }}
          </a>
          <p>
            {{ item.description }}
          </p>
        </div>
      </div>
    {% endfor %}
  </div>
      
{% endfor %}
</div>
