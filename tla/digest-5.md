---
# layout: default
layout: post
title: "TLA_insights digest #5 - Architecture Topologies and Scopes"
date: 2021-07-14
permalink: /tla_insights/digest-5
categories: [tla_digest]
tla_area: [tla]
digest: 5
---

Welcome to the digest #{{page.digest}} of my "Technical Leadership and Architecture insights" (or TLA_insights for short).

![light](/assets/tla_insights-text.png)

Very excited to share this digest. It has three very entries on a topic I am calling: "Architecture Topologies and Scopes". These are the three entries:

- one based on an article by Alberto Brandolini, discussing the relation between Context Maps and Team Topologies;
- one based on an article from from Ruth Malan and Dana Bredemeyer on architecture scopes and key elements to achieve a minimalistic approach to architecture;
- and finally one inspired by a great post by Gregor Hohpe on approaches to team scope architecture, which I ended up extending and introducing the idea of "Architecture Topologies" and furthermore discussing an example of a topology I am very fond of: "Architecture as Enabling Team".

Over the last years I have been thinking and exploring these topics extensively. I see them as foundational elements to approach [Sociotechnical Architecture](https://esilva.net/sociotechnical) design and evolution (which as you may have noticed from my articles and notes is a topic I consider key to unlocking new levels of performance in modern organizations). On this digest topic, and in a nutshell: we must have sound and suitable strategies to approach architecture (and how to evolve it) in organizations to truly maximize their potential. This is not a trivial discussion and depends on a lot of factors, such as: the state of the architecture and its practice in the organization; the maturity of teams and their practices; the nature of the products the organization is developing, etc. Nonetheless, what is clear is that all those factors and the organization "scopes" of architecture (shaped by the sociotechnical systems and architecture in place) are key to shaping the organization's approach to architecture. The three articles of this digest explore different elements of this.

When I published the entry on "Architecture Topologies" I got many interesting reactions and discussions. Those led me to start a GitHub repo ([Architecture Topologies](https://github.com/emgsilva/architecture-topologies)) to collect knowledge on this topic and hopefully capture interesting patterns for architecture topologies. The goal is not to create a solution, but to capture this knowledge and try to shape a better "language" to drive meaningful discussions on how to approach architecture in organizations. Because, whether we like it or not: every organization and system has an architecture... ignoring that is a recipe for issues. However, the uniqueness of each organization also means that we cannot use the same approach (topology) to architecture in every organization (there is no silver bullet). This is why I consider that it is more interesting to focus on shaping a "base language" that enables us to discuss how we approach architecture can be a powerful tool: each organization can shape (and evolve) the "architecture topology" that enables them the most. In some organizations it will be possible to have teams owning the "team scope" architecture, with some people or way-of-aligning the surrounding system scope architecture; in some other organizations we may need an explicit Architect (function) working in the teams... and many other flavors. (This idea is highly inspired by the great work and approach of Team Topologies, which as I mentioned a while ago "provide a [DSL for Org Design and Evolution](https://esilva.net/articles/techlab-team_topologies)).

On a personal note, and since the last digest: I have also published a new original article called [Sociotechnical Architecture as Enabler of Product Thinking](https://esilva.net/articles/sociotech_arch_enabling_prod_thinking). The article is a continuation (and deep dive) on my talk from DevOps Lisbon Meetup (["Evolving Tech-enabled Orgs Using Sociotechnical Architecture"](https://esilva.net/talks/#sociotechnical-devopslisbon_2021)) and follow-up interview I had an Manuel Pais (co-author from Team Topologies) - [DevOps is Not Enough for Scaling and Evolving Tech-Driven Organizations](https://www.infoq.com/articles/devops-not-enough-scaling-tech-driven-organizations/). This is a topic I am rather active lately (including first-hand experiences on [bol.com](http://bol.com/)'s product-led organization developments). This article, among other things, touches key elements and traits that I think we need to consider to truly empower tech-enabled product-led organizations. (Spoiler alert: it is not just product thinking, nor DevOps, each on their own silo). This topic also relates closely with the topic of this TLA_insights digest, namely the ideas of having structures and dynamics that holistically empower product development (from all the key perspectives needed, e.g.: value, people and technical). The article raised quite some interesting discussions and sparks, and there will be new articles on this topic in the near future.

I hope you enjoy these four entries! If you found this issue interesting or useful make sure to [subscribe to the newsletter](https://tinyletter.com/tla_insights) or [follow-me on twitter](https://twitter.com/emgsilva) so you get notified of new records in these and other topics. I hope you have fun and find some interesting insights here. Don't hesitate to [contact me](mailto:emgsilva@gmail.com) if you have questions or want to chat about these topics.

## <b>{{page.title}}</b>

 {% assign sorted_pages = site.pages %}
 {% assign sorted_pages = sorted_pages | where_exp: "item", "item.digest == page.digest" | sort:"date" %}
 {% assign sociotech_pages = sorted_pages | where_exp: "item", "item.tla_area contains 'tla_sociotech'" %}
 {% assign techleadership_pages = sorted_pages | where_exp: "item", "item.tla_area contains 'tla_tech-leadership'" %}
 {% assign software_pages = sorted_pages | where_exp: "item", "item.tla_area contains 'tla_software'" %}
 {% assign product_pages = sorted_pages | where_exp: "item", "item.tla_area contains 'tla_product'" %}
 {% assign productivity_pages = sorted_pages | where_exp: "item", "item.tla_area contains 'tla_productivity'" %}

{% if sociotech_pages.size > 0 %}
{% for page in sociotech_pages %}
### ![light](/assets/light-bulb.png) {{page.title}}<br>
<div style="background-color: #f3f5f2 ; padding: 10px; border: 0px">
{{page.summary}} <span class="post-meta" > 🏷{{page.categories}}</span>
</div>

> {{page.insightweet}}

<b><a href="{{ site.baseurl }}{{ page.url }}"> 🔗 full-text </a></b>
  
{% endfor %}
{% endif %}

{% if techleadership_pages.size > 0 %}
{% for page in techleadership_pages %}
### ![light](/assets/light-bulb.png) {{page.title}}<br>
<div style="background-color: #f3f5f2 ; padding: 10px; border: 0px">
{{page.summary}}  <span class="post-meta" > 🏷{{page.categories}}</span>
</div>

> {{page.insightweet}}

<b><a href="{{ site.baseurl }}{{ page.url }}"> 🔗 full-text </a></b>

{% endfor %}
{% endif %}

{% if software_pages.size > 0 %}
{% for page in software_pages %}
### ![light](/assets/light-bulb.png) {{page.title}}<br>
<div style="background-color: #f3f5f2 ; padding: 10px; border: 0px">
{{page.summary}} <span class="post-meta" > 🏷{{page.categories}}</span>
</div>

> {{page.insightweet}}

<b><a href="{{ site.baseurl }}{{ page.url }}"> 🔗 full-text </a></b>

{% endfor %}
{% endif %}

{% if product_pages.size > 0 %}
{% for page in product_pages %}
### ![light](/assets/light-bulb.png) {{page.title}}<br>
<div style="background-color: #f3f5f2 ; padding: 10px; border: 0px">
{{page.summary}} <span class="post-meta" > 🏷{{page.categories}}</span>
</div>

> {{page.insightweet}}

<b><a href="{{ site.baseurl }}{{ page.url }}"> 🔗 full-text </a></b>

{% endfor %}
{% endif %}

{% if productivity_pages.size > 0 %}
{% for page in productivity_pages %}
### ![light](/assets/light-bulb.png) {{page.title}}<br>
<div style="background-color: #f3f5f2 ; padding: 10px; border: 0px">
{{page.summary}} <span class="post-meta" > 🏷{{page.categories}}</span>
</div>

> {{page.insightweet}}

<b><a href="{{ site.baseurl }}{{ page.url }}"> 🔗 full-text </a></b>

{% endfor %}
{% endif %}

<form style="border:1px solid #ccc;padding:3px;text-align:center;" action="https://tinyletter.com/tla_insights"
    method="post" target="popupwindow"
    onsubmit="window.open('https://tinyletter.com/tla_insights', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true">
    <p><label for="tlemail">Enter your email to be notified of future TLA_insights</label></p>
    <p><input type="text" style="width:140px" name="email" id="tlemail" /></p><input type="hidden" value="1"
      name="embed" /><input type="submit" value="Subscribe" />
</form>
