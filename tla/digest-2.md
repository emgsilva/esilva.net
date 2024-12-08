---
layout: default
title: "TLA_insights digest #2"
date: 2020-11-01
permalink: /tla_insights/digest-2
categories: [tla_digest]
tla_area: [tla]
digest: 2
---

Welcome to the digest #2 of my "Technical Leadership and Architecture insights" (or TLA_insights for short).

![light](/assets/tla_insights-text.png)

Although this is just iteration #2, I am already pivoting the format a lot 😄  (*learn fast and make it better*). The following changes were made:

- will start publishing multiple records individually in the course of the month. Those will be announced on [Twitter](https://www.twitter.com/emgsilva) & [LinkedIn](https://www.linkedin.com/in/emgsilva) as I publish them - you can follow me there to be notified of new records;
- at the end of the month I will send a digest of the new entries of the particular month. Furthermore, will also send a small update on interesting developments on my side or interesting things I see happening in the TLA_insights topics. You can find all the Monthly Digest entries here: [https://esilva.net/tla_insights/#monthly-digest](https://esilva.net/tla_insights/#monthly-digest)
- will publish each record separately and keep a list of all of them, which makes it easier to reference to a specific record (and not have to go in a given issue/digest). You can find all the past records here, organized per area and date of publication: [https://esilva.net/tla_insights](https://esilva.net/tla_insights/)

I hope you appreciate these changes, I am really excited about them as it allows more regular and interesting insights to be published and also create a clearer knowledge base of insights. I have a few other ideas in mind that I will be working on moving forward, so stay tuned!

On a personal note: September and October were very eventful in terms of developments on topics relevant to TLA_insights:

- published a [new article](https://esilva.net/sociotechnical/sociotechnical-architecture_traits-and-strategies.html) on my Introduction to Sociotechnical Architecture [series](https://esilva.net/sociotechnical), which gives a lot of insights on important traits of Sociotechnical Architecture and Systems. In that article I also provide insights on strategies to approach those traits (furthermore will be publishing real-world examples soon);
- [participated on the TechLab podcast](https://techlab.bol.com/sociotechnical-architecture-to-maximize-impact/) talking about Sociotechnical Architecture, and how this is so important to maximize the impact of our efforts while building software products;
- published long overdue reviews: first for the book [Team Topologies](https://esilva.net/articles/review-team_topologies), which is also my first entry in this record and then for the book [Escaping the Build Trap](https://esilva.net/articles/review-escaping_the_build_trap). Both of these books are amazing resources for Sociotechnical Architects - I find them extremely complementary and a great combo to address the "sociotechnical evolution loop" (from customer understanding, to the organizational and technical systems to be set up and support to maximize/optimize the "value exchange" with customer).

If you found this issue interesting or useful make sure to [follow-me on LinkedIn](https://www.linkedin.com/in/emgsilva) or [Bluesky](https://bsky.app/profile/esilva.net) so you get notified of new records in this topic and other TLA_insights areas. I hope you have fun and find some interesting insights here. Don't hesitate to [contact me](mailto:emgsilva@gmail.com) if you have questions or want to chat about these topics.

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
