
### Every startup faces the same problems:

  * Making sure their initial objectives are properly focused on the core problem they are solving
  
  * Executing the development with the right balance of speed and quality.

#### Hey, I’m Mac.

**I help the best and brightest startups and entrepreneurs develop their ideas**, scrappily, efficiently, quickly, and agile, yet with the ability to scale. These are not terms you hear agencies using to describe themselves, as they’re built to solve a different set of problems with a different mindset that doesn’t jibe with the needs of a startup.

**I help increase efficiency by:**

  * Helping define the market, the problem, the need, and the solution before any code is written. If you’ve done your job, you should have this pretty well defined, or at least with some well defined hypothesis. You can expect me to want to hear all about it, and have you pitch it to me. I want to be convinced, and I want to believe in it. And I may try to poke holes in it.

  * Excellent communication. Communication, along with transparency, honesty, and trust is at the forefront of everything I do. I expect it from you, and I do everything I can to provide that for you. It makes every relationship and every project 100 times stronger, projects go smoother, and quicker.

**I help decrease development time and costs by:**

  * Being scrappy, and don’t take that to mean cutting corners, but rather being resourceful and creative. For example, if we’re early on, I won’t hesitate to throw your app on a $7/mo server that takes literally minutes to set up, instead of wasting days on provisioning a significantly more expensive server, along with automated deploys for when we hit 50,000 customers. I’m not wasting my time and your money on problems that don’t exist.

  * Being scrappy. For example, if we decide to offer a free 30-day trial, let’s launch without the ability to take payments to hit the market and get feedback sooner. We’ll have 30 days to get billing in. 

  * Being scrappy. MVP’s, V1’s, V2’s, whatever you prefer to call them, need to be functionally pretty solid. And you want them to be able to be built upon, not scrapped, if it continues to grow. But there’s a balance to be had. You don’t want a development environment that’s a mess, but it also doesn’t need to be over-architected for a bunch of theoretical if-this, if-that’s.

<span>For the last startup application I developed, I cut the proposed scope in half for launch, cutting costs by the same amount. We got to market sooner, learned what our customers wanted quicker, and made a better product as a result. Had we built the full initial scope, we’d have wasted a lot of time of features our customers didn’t actually want.</span>

{% for item in site.data.testimonials-featured %}
> “{{ item.quote }}”
>
>![{{ item.name }}](/assets/images/testimonials/{{ item.image  }}) 
>
>{{ item.name }}
>{: .cite }
>
>{{ item.title }} at [{{ item.company }}]( {{ item.url }} )
>{: .cite }
{% endfor %}

### Before you decide though, let’s make sure I’m the right fit for you

It’s true that you might benefit from my experience building countless SaaS apps for entrepreneurs and startups, having gone through acquisitions, failures, and everything in between. But I may not be the right person for you. I work best with, and provide the most value for a certain type of company, so let’s briefly touch on that.

#### I’m not for you if you’re:

  * Not committed to doing everything you can to make your app successful. I can only take on a handful of projects per year, and I want to work with people that mean it. 

  * Not willing to put off any features that aren’t core to the focused problem we’re solving. Successful startups don’t come from launching a product at the end of their roadmap, rather they launch quickly, iterate, analyze, learn, repeat. And that’s the way I’m committed to working.
  
  * Looking for someone to maintain an existing application.

When roadmapping and development is done with a startup mindset, with people that have experience in finding that perfect balance of scrappiness and solidity, with ability to scale, you’re setting your startup up for the it’s best chance at success. You need quick, forward momentum, with the ability to quickly adjust and pivot on a dime. You need to think and develop quickly, get to market quickly, learn, iterate, rinse and repeat. Ready? Get in touch today and tell me what you’re up to.

After you reach out, check out the podcast I host [The SaaS Bootstrapper podcast](http://thesaasbootstrapper.com/podcast/).

[Get in touch](mailto:mac.martine@gmail.com){: .btn } 

{% for item in site.data.testimonials-mvp %}
> “{{ item.quote }}”
>
>![{{ item.name }}](/assets/images/testimonials/{{ item.image  }}) 
>
>{{ item.name }}
>{: .cite }
>
>{{ item.title }} at [{{ item.company }}]( {{ item.url }} )
>{: .cite }
{% endfor %}



## Case Studies

<!--Here's a select sampling of recent projects:-->

{% assign items = site.case_studies | sort: 'order' %}
{% for item in items %}

<!--[![{{ page.title }} logo](/assets/images/case_studies/{{ item.logo }})]({{ item.url }}){: .a-plain }-->
<!--{: .case-study-logo }-->

### {{ item.title }}

[{{ item.siteurl }}]({{ item.siteurl }})

{{ item.intro }}

![{{ page.title }} screenshot](/assets/images/case_studies/{{ item.screenshot }})
{: .case-study-screenshot }

{{ item.content }}

<hr/>

{% endfor %}

{% for item in site.data.testimonials %}
> “{{ item.quote }}”
>
>![{{ item.name }}](/assets/images/testimonials/{{ item.image  }}) 
>
>{{ item.name }}
>{: .cite }
>
>{{ item.title }} at [{{ item.company }}]( {{ item.url }} )
>{: .cite }
{% endfor %}

<!--Quote-->

> It's the construction of the foundation that will stand the test of time. 
>
> *-- David Allen Coe*
{: .aside }


[Get in touch](mailto:mac.martine@gmail.com){: .btn } 
