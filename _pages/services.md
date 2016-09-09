---
layout: default
title: Services
permalink:  /services/
---


<!--What we do-->

# What I Do

<div class="pure-g" markdown="1">
<div class="pure-u-1" markdown="1">
Have an idea that you need to develop with an MVP (minimum viable product), or to validate with a proof of concept?

With years of experience, I've developed what has been dubbed the “Truing” process. This process is designed to help develop and nurture your idea through a combination of idea validation, design, discovery, development and early-stage marketing that’s unique to your situation, budget and goals.

We whittle down the feature set to what’s core to the platform, and get creative in finding ways to reduce requirements. The [Truing process](#process) can shave thousands of dollars off your initial development phase. As a one-man band with a dispersed set of potential contributors, overhead costs are extremely low. I have a proven, flexible, repeatable process in place that enables us to deliver amazing value to my clients.
</div>
</div>

<!--What people say-->

<!--# What Clients Say-->


<div class="pure-g aside">
{% for item in site.data.testimonials %}
<div class="pure-u-1 pure-u-md-1-2 bg-1">
  <blockquote>
    <p>
      {{ item.quote }}
    </p>
    <em>
      <img src="/resources/images/testimonials/{{ item.image  }}" />
      {{ item.name }}
      <br/>
      <a href="{{ item.url }}">{{ item.title }} at {{ item.company }}</a>
    </em>
  </blockquote>
</div>
{% endfor %}
</div>

<!--*"You're brilliant. You go the extra mile. You're a delightful human being."*-->
 
<!--*"Your smarts and your can-do attitude are amazing. "*-->
 
<!--*"Let's do this again soon."*-->


<!--Case Studies-->

<!--## {{ page.title }}-->

# Case Studies
{% assign items = site.case_studies | sort: 'order' %}
{% for item in items %}

<!--## [{{ item.title }}]({{ item.url }})-->
<div class="pure-g" markdown="1">
<div class="pure-u-1 text-center" markdown="1">
[![{{ page.title }} logo](/resources/images/case_studies/{{ item.logo }})]({{ item.url }}){: .a-plain }
{: .case-study-logo }

![{{ page.title }} screenshot](/resources/images/case_studies/{{ item.screenshot }})
{: .case-study-screenshot }
</div>
<div class="pure-u-1" markdown="1">

{{ item.intro }}

{{ item.content }}

<hr/>

{% endfor %}

<!--Quote-->

> It's the construction of the foundation that will stand the test of time. 
>
> *-- David Allen Coe*
{: .aside }


<!--The Process-->

<!--# The Process-->

<!--[>## The True-Up Process<]-->

<!--<div class="pure-g" markdown="1">-->
<!--<div class="pure-u-1" markdown="1">-->
<!--Each idea that comes to me is unique, and each comes in various stages of maturity. While I tailor the process to your needs, almost everything I take on today consists of two separate phases:-->

<!--### Discovery/Road-mapping-->

<!--I’ve been honing my MVP road-mapping process for awhile now, and continue to fine-tune it as I discover more ways to be effective. The process has become unique enough to deserve its own name, which we call the "Truing Process".  The term comes from the bike world, where wheels are “trued” or aligned through a process of inspection, analysis, patience and precision.-->

<!--Through this process, we take a deep dive into what you want to build. After poring over any existing thoughts, documents and research, I take the time to truly understand the idea, the market and competitors. Together we determine the goals of the project and start considering budget. I then map out a feature backlog, a set of deliverables, and several development plan options along with fixed quotes.-->

<!--While I hope to earn your business for the development phases, you will have ample documentation to shop around to get other development quotes if you so choose.-->

<!--### Development-->

<!--The best part of the discovery phase is how easy and seamless it makes the development phase. All key decisions have been made, from architecture to features to time to budget. You can sit comfortably knowing exactly what you’re going to get and what it’s going to cost you. There aren’t many questions unanswered.-->

<!--So, it’s head-down development time with periodic checkins to keep you up to speed on how things are going. We raise and red flags as soon as we spot them.-->


</div>
</div>
