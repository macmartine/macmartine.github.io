---
layout: default
title: book list
permalink:  /book-list/
---
<div class='pure-g'>
  <div class="pure-u-1" markdown="1">

### Books

I consume a lot of books on business, startups, marketing, persuasion psychology &mdash; and many other topics related to the startup process. Here is a list of what I've read in the recent past, and I continue to update this as the list grows. 

Lately I've been plucking more books from the <a href="https://personalmba.com/best-business-books/" target="_blank">Personal MBA reading list</a>, created by Josh Kaufman. I highly suggest checking out that list as well.

  </div>
</div>

{% for item in site.data.books %}
  <div class="pure-g reading-list-item">
    <div class="pure-u-1-6">
      <img src="/resources/images/books/{{ item.image }}" />
    </div>
    <div class="pure-u-5-6">
      <a href="{{ item.product_code }}">
        {{ item.title }}
      </a>
      <p>
        {{ item.description }}
      </p>
    </div>
  </div>
{% endfor %}
