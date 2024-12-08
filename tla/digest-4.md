---
# layout: default
layout: post
title: "TLA_insights digest #4 - Systems Thinking & Product Thinking"
date: 2021-04-11
permalink: /tla_insights/digest-4
categories: [tla_digest]
tla_area: [tla]
digest: 4
---

Welcome to the digest #{{page.digest}} of my "Technical Leadership and Architecture insights" (or TLA_insights for short).

![light](/assets/tla_insights-text.png)

This is a long overdue "digest"... this delay is mostly caused by quite some other activities going on. Nevertheless, here it is a "digest" of four records I added over the last few months to my TLA_insights: two on Product Thinking and two on Systems Thinking. These are entries that contain a lot of very interesting insights.

Most of these entries are direct references and preparation materials for several talks and articles I worked on over the past 2-3 months. Namely, my Domain-Driven Design Europe (DDD EU) talk on ["Sociotechnical Architecture as Enabler of Product Thinking"](https://esilva.net/talks/#sociotechnical-dddeu_2021) and a talk I gave for DevOps Lisbon Meetup entitled ["Evolving Tech-enabled Orgs Using Sociotechnical Architecture"](https://esilva.net/talks/#sociotechnical-devopslisbon_2021). I had a lot of fun on these two talks and there are a lot of interesting discussions and follow-up activities. I want to highlight one, namely an interview for InfoQ with Manuel Pais (co-author from Team Topologies), which was placed as a follow-up from the DevOps Lisbon talk. In this interview we go into the subject of why [DevOps is Not Enough for Scaling and Evolving Tech-enabled Organizations](https://www.infoq.com/articles/devops-not-enough-scaling-tech-driven-organizations/), and what other things we need to consider to address that. I have published a [new article on Sociotechnical Architecture](https://esilva.net/articles/evolve_tech_orgs_using_sociotech) and have two others being prepared on the same topic, so stay tuned for more.

If you found this issue interesting or useful make sure to [follow-me on LinkedIn](https://www.linkedin.com/in/emgsilva) or [Bluesky](https://bsky.app/profile/esilva.net) so you get notified of new records in this topic and other TLA_insights areas. I hope you have fun and find some interesting insights here. Don't hesitate to [contact me](mailto:emgsilva@gmail.com) if you have questions or want to chat about these topics.

## <b>TLA_insights digest #4 - System Thinking & Product Thinking</b>

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
