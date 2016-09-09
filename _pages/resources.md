---
layout: default
title: Resources
permalink:  /resources/
---

<div class="pure-g bg-1" >
  <div class="pure-u-1">
    <div class="padded-box">
{% include resources_cta_body.md %}
    </div>
  </div>
</div>

<div class="pure-g resource-aside" >
  <div class="pure-u-1 pure-u-md-1-2">
    <div class="padded-box">
      <h1>Reading list</h1>
      <p>
        There are so many good books out there, and I consume as many of them as I
        can. Check out the list of books I've read recently and find your next book.
      </p>
      <p>
        <a href="/book-list" class="pure-button">Check out the book list</a>
      </p>
    </div>
  </div>
  <div class="pure-u-1 pure-u-md-1-2">
    <div class="padded-box">
      <h1>Startup development tools</h1>
      <p>
        There are so many great tools out there for startup Founders and developers.
        <br />
        Here's a list I've compiled of the best, most useful resources I'm aware of.
      </p>
      <p>
        <a href="/startup-resources" class="pure-button">Check out the resource list</a>
      </p>
    </div>
  </div>
</div>

<hr />

<div class="pure-g" >
  <div class="pure-u-1">
    <div class="padded-box">

      {% for cat in site.categories %}

        <h1>{{ cat[0] }}</h1>

        <ul>
          {% for posts in cat %}
            {% for post in posts %}
              <li>
                <p><a href="{{ post.url }}">{{ post.title }}</a></p>
              </li>
            {% endfor %}
          {% endfor %}
        </ul>

      {% endfor %}

    </div>
  </div>
</div>
