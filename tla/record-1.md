---
layout: post
title: "TLA_insights digest #1"
date: 2020-09-03
permalink: /tla_insights/record-1
categories: [tla_digest]
tla_area: [tla]
digest: 1
---

Welcome to the digest #1 of my "Technical Leadership and Architecture insights" (or TLA_insights for short).

![light](/assets/tla_insights-text.png)

**What is this?** TLA_insights is compilation of insights (![light](/assets/light-bulb.png) "*deeper understanding*") I develop in the topics of Technical Leadership and Architecture (in context of Building Software products). This is a rather broad area, which means one needs to develop all sorts of skills and knowledge to be able to "develop & make things better". To accomplish this I tend to study different resources, from which I take notes to distill the most interesting insights. With TLA_insights I want to curate those insights further and give some of my own views and interpretations. Hopefully these curated insights are useful for other people interested in these topics.

> I will be publishing a digest of TLA_insights at least once a month. This also may look like a newsletter, but it really is about sharing curated insights, which may not be "news" all the time, so I am calling it an "Insights-letter".

**Why am I doing this?** Two reasons:

- 1: curate and consolidate the insights I develop, as I will further process and organize them in my mind while writing them down, and with that I improve my knowledge and command of these topics
- 2: to share these insights with others, who can also benefit from that

**How is this organized?** It is basically a collection of summaries & insights from resources I find interesting. I will be organizing these into sections, which represent areas I am really interested and actively developing/researching in the wider topic of Technical Leadership and Architecture. Currently these are the areas:

- Sociotechnical Architecture & Systems Design
- Technical Leadership
- Software {Architecture, Engineering & Tech}
- Personal Productivity

I hope you have fun and find some interesting insights here. Don't hesitate to [contact](mailto:emgsilva@gmail.com) me if you have questions or want to chat about these topics.

## <b>TLA_insights digest #{{page.digest}}</b>

 {% assign sorted_pages = site.pages %}
 {% assign sorted_pages = sorted_pages | where_exp: "item", "item.digest == page.digest" | sort:"date" %}
 {% assign sociotech_pages = sorted_pages | where_exp: "item", "item.tla_area contains 'tla_sociotech'" %}
 {% assign techleadership_pages = sorted_pages | where_exp: "item", "item.tla_area contains 'tla_tech-leadership'" %}
 {% assign software_pages = sorted_pages | where_exp: "item", "item.tla_area contains 'tla_software'" %}
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
{{page.summary}} <span class="post-meta" > 🏷{{page.categories}}</span>
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
