
## SaaS MVP development done right

Been burned by unreliable, uncommunicative developers in the past that go over budget?

Yeah, don't do that again. 

I help entrepreneurs and startups whittle down their vision to it's core, to determine the best MVP to start iterating on. Approaching this process with experience, research and educated hypotheses, I'm often able to shave thousands, if not tens of thousands off what clients were initially planning to build.

As someone who almost solely develops SaaS MVP's, I've gotten the process down, am incredibly efficient, and get things built quicker than just about anyone. You'll communicate directly with me, instead of some member of an agency that isn't the one actually building your app. There'll be no communication breakdown, no paying unneeded project managers, and no suprises of blowing past estimates.

While I often do all the work myself, I have a powerful army of amazing design and brand folks to bring in if your project calls for it.

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


[Get in touch](mailto:mac.martine@gmail.com){: .btn.learn-more } 
