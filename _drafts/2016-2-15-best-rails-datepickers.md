---
title: Best Datepickers for use in Rails (or without Rails)
abstract: 
location: Portland, Oregon
comments: true
---

# Overview

In this post I'll be reviewing a few Datepickers. I'll be using this in a Rails application, but these are all Javascript datepickers, so they can be used in any web application, Rails for not. 

If you are using Bootstrap, there's a post specifically dedicated to [Bootstrap datepickers][1].

While our focus here is picking dates, some have the option to allow picking times as well. If your application requires both date and time picking, it may be worth a deeper search than what you'll find here. 

Additionally, if your application requires the selection of a date range, as opposed to just a single date, you can do that with any of these simply by implementing two of them, one for the start date and another for the end date.

# Installation options

Some have associated Rails gems to simplify the installation, but while this is sometimes convenient, it doesn't carry much weight, as all that's needed to install any of these, is just the inclusion of some Javascript and CSS files. 

A benefit of requiring these files yourself is that you can reference these libraries from a CDN[1], which is essentially a hosted, cached version of the library, so you don't need to store the files, and they'll be faster. Win/win. Also, when you want to upgrade versions, simply change the version number in the path the the files on the CDN.

# Before we begin

It's worth noting that as of February 2016, all of the datepicker's mentioned here are still actively being developed or maintained.  

### jQuery Datepicker []

While not as full-featured and customizable as some of the other datepickers discussed here, The jQuery Datepicker, in many cases will get the job done. It does have a few things going for it:

* If you're alreay using jQuery UI, you may already be including this, so it wouldn't require any extra Javascript or CSS includes
* If you're using the jQuery ThemeRoller[], or other jQuery theme, the datepicker will automatically fit right in with the look of your application
* It's comes with localization in several languages
* Can display multiple months at once, in a single view
* Can easily be shown inline (embedded in the page, as opposed to a being a pop-up)

It also supports some of the jQuery animations if that floats your boat.

Here's what the inline jQuery Datepicker looks like, by default, with a basic jQuery theme:

![jQuery datepicker]({{ site.url }}/resources/images/posts/2016-02-16-datepickers/jquery-datepicker.png)

#### Pikaday

Pikaday is a great little datepicker, weighing in at less than 5kb, with no external dependencies. While I haven't tried is with Moment.js[], the docs tout they play very well together. There's also a jQuery plugin for those of you already using jQuery, but again, jQuery is not a dependency here.

Additionally there's a Rails gem to manage the install for Rails apps if you prefer going that route [https://rubygems.org/gems/pikaday-gem].

While Pikaday does not in itself support time selection, there are a couple forks that have apparently implemented it, though I cannot speak to those.
[https://github.com/dbushell/Pikaday/issues/1]
[https://github.com/dbushell/Pikaday/issues/18]

![Pikaday datepicker]({{ site.url }}/resources/images/posts/2016-02-16-datepickers/pikaday-1.png)

#### Pickadate 

Pickadate is our favorite all-around Javascript datepicker for use in, or out of Rils. There are tons of customization options, as well as an API for extending the functionality, if you have unusual needs. Pickadate also supports time selection. 

The docs are great, the site is clean, and it's a full-featured as most of use could even need in a datepicker for use in a web application.

![Pickadate datepicker]({{ site.url }}/resources/images/posts/2016-02-16-datepickers/pickadate-1.png)
![Pickadate datepicker]({{ site.url }}/resources/images/posts/2016-02-16-datepickers/pickadate-2.png)

[] https://jqueryui.com/datepicker/
http://jqueryui.com/themeroller/

{% include disqus.html %}