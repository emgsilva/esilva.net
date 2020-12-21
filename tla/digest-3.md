---
layout: default
title: TLA_insights digest \#3
permalink: /tla_insights/digest-3
categories: [tla_digest]
digest: 3
---

Welcome to the digest #{{page.digest}} of my "Technical Leadership and Architecture insights" (or TLA_insights for short).

![light](/assets/tla_insights-text.png)

This is a special "aggregate" issue of TLA_insights focused on "Tech Vision and Strategy", especially on the topic of "Setting and Operating" or "Life-cycle" of Tech Vision and Strategy (yes, I see it as a cycle that should be continuously operated).

> "Aggregate Issue" - yet another pivot on TLA_insights format, where I put together ("aggregate") a series of TLA_insights records on a specific topic. The idea is to create a sort of "state-of-the-art" overview on a given topic, while also bringing some consolidation and insights from my side.

This topic is still a bit "mystical" (as Will Larson, a reference in this issue says): people/orgs approach it differently; a lot of special ceremonies and overhead is put into it; many times people in the tech organization don't embrace it as they don't understand why it is important for them or how it enables them; and worst of all, and the most common pattern: approach it as a "one-off" thing, built top-down as a long document done once a year, which is "skimmed once" and then forgotten.

I have selected several interesting references to shade some light on the issues mentioned above and explain:

- Why is it important (in a nutshell "it enables aligned and accelerated technical decision making by teams in the organization");
- How to approach it (i.e.: how to build it, but also "operate it" - as to maximize its potential it should not be a one-off thing, it should be a continuous process embraced by the whole technical community);
- What it can look like (i.e.: important sections and elements to make sure this is an effective and used resource);
- When to do What (i.e.: the cadence for activities and time-windows to consider, e.g.: Vision should target a multi-year window to provide safety on longer-term decision making, while a lot of tactical strategies will target shorter term and are much more concrete and scoped - still contributing/aligning with the longer term vision).

I hope you enjoy this special issue and stay tuned as I will be publishing follow-up material on this topic (new entries on this "aggregate", and an article on the topic with my own views and consolidation of the insights gathered from these and other resources).

On a personal note: last 2 months were very busy, but also very interesting on topics relevant to TLA_insights (especially on the "Technical Leadership" area):

- I became "Principal Tech Lead" at [bol.com](http://bol.com) (the largest online shopping platform of Netherlands and Belgium). I am leading the official kickstarting of Tech Lead function in the organization. [Bol.com](http://bol.com) has had "unofficial" Tech Leads (or Software Architects) organized in a rather "ad-hoc" manner for a good while. However, with the very fast growth we have been going through over the last 5 years or so, that model was not scaling well anymore, so we have introduced Tech Leads as an official function with clearer "areas of responsibility" and empowerment. We are positioning them as "Enabling Teams" (as in Team Topologies), and their mission is to maximize the potential of the product teams they work with and create an explicit network of knowledge and technical enabling in the organization. (I have an article on the pipeline to share Why we took this decision, What it looks and How we are approaching setting up this "team" or "network" of people on our product-led organization).
- Related with kickstarting the Tech Leads at bol.com, we have also had the honor of having Pat Kua giving us his "Shortcut to Tech Leadership" virtual training. Pat Kua has been an inspiration and reference for me as Tech Lead for more than 5 years now, and it was great having him sharing a lot of insights and tools for our new Tech Leads (most of them been working as Engineer - "Maker" role, and now transitioning to a Tech Lead - "Multiplier" role, which is the exact focus of this workshop by Pat). Highly recommended to help new Tech Leads, but also to more experience Tech Leads (as a way to consolidate and organize the many things being a Tech Leader involves).

If you found this issue interesting or useful make sure to [subscribe to the newsletter](https://tinyletter.com/tla_insights) or [follow-me on twitter](https://twitter.com/emgsilva) so you get notified of new records in this topic and other TLA_insights areas. I hope you have fun and find some interesting insights here. Don't hesitate to [contact me](mailto:emgsilva@gmail.com) if you have questions or want to chat about these topics.

## <b>TLA_insights digest #3 - "Tech Vision and Strategy"</b>

 {% assign sorted_pages = site.pages %}
 {% assign sorted_pages = sorted_pages | where_exp: "item", "item.digest == 3" | sort:"date" %}
 {% assign sociotech_pages = sorted_pages | where_exp: "item", "item.categories contains 'tla_sociotech'" %}
 {% assign techleadership_pages = sorted_pages | where_exp: "item", "item.categories contains 'tla_tech-leadership'" %}
 {% assign software_pages = sorted_pages | where_exp: "item", "item.categories contains 'tla_software'" %}
 {% assign productivity_pages = sorted_pages | where_exp: "item", "item.categories contains 'tla_productivity'" %}

{% if sociotech_pages.size > 0 %}
{% for page in sociotech_pages %}
### ![light](/assets/light-bulb.png) {{page.title}}<br>
<div style="background-color: #f3f5f2 ; padding: 10px; border: 0px">
{{page.summary}}
</div>

> {{page.insightweet}}

<details>
  <summary>record</summary>
  
  {{page.content}}
</details>
<br>
{% endfor %}
{% endif %}

{% if techleadership_pages.size > 0 %}
{% for page in techleadership_pages %}
### ![light](/assets/light-bulb.png) {{page.title}}<br>
<div style="background-color: #f3f5f2 ; padding: 10px; border: 0px">
{{page.summary}}
</div>

> {{page.insightweet}}

<details>
  <summary>record</summary>
  
  {{page.content}}
</details>
<br>
{% endfor %}
{% endif %}

{% if software_pages.size > 0 %}
{% for page in software_pages %}
### ![light](/assets/light-bulb.png) {{page.title}}<br>
<div style="background-color: #f3f5f2 ; padding: 10px; border: 0px">
{{page.summary}}
</div>

> {{page.insightweet}}

<details>
  <summary>record</summary>
  
  {{page.content}}
</details>
<br>
{% endfor %}
{% endif %}

{% if productivity_pages.size > 0 %}
{% for page in productivity_pages %}
### ![light](/assets/light-bulb.png) {{page.title}}<br>
<div style="background-color: #f3f5f2 ; padding: 10px; border: 0px">
{{page.summary}}
</div>

> {{page.insightweet}}

<details>
  <summary>record</summary>
  
  {{page.content}}
</details>
<br>
{% endfor %}
{% endif %}
