---
title: Startup development and asset resources
category: Resources
---
<div class='row resource-list' markdown='1'>

### {{ page.title }}<

Below are the best resources I'm aware of for some of the various needs of startups.
Many of these are development resources such as hosting, and website and application templtes,
but there are also asset resources, such as the best places to find (free!) stock photography,
fonts, email teplates and more. You'll also find indispensable tools for building email ists, and more.

This list has a strong emphasis on easy-to-use, and affordability. In building a Lean Startup,
we need tools to help us be more effecient and more effective, not depleting our cash.

</div>

<div class='row resource-list'>
{% for category in site.data.resources.categories %}

  <div class="12u">
    <h3>
      {{ category.name }}
    </h3>
  </div>

  <div class="12u">
    {% for item in category.items %}
      <div class="row" >
        <div class="4u">
          <img src="/assets/images/resources/{{ item.image }}" />
        </div>
        <div class="8u">
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
