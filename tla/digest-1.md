---
layout: default
title: TLA_insights digest \#1
permalink: /tla_insights/digest-1
categories: [tla_digest]
redirect_from:
  - /tla_insights/record-1
---

Welcome to the digest #1 of my "Technical Leadership and Architecture insights" (or TLA_insights for short).

![light](/assets/tla_insights-text.png)

**What is this?** TLA_insights is compilation of insights (![light](/assets/light-bulb.png) "*deeper understanding*") I develop in the topics of Technical Leadership and Architecture (in context of Building Software products). This is a rather broad area, which means one needs to develop all sorts of skills and knowledge to be able to "develop & make things better". To accomplish this I tend to study different resources, from which I take notes to distill the most interesting insights. With TLA_insights I want to curate those insights further and give some of my own views and interpretations. Hopefully these curated insights are useful for other people interested in these topics.

> I will be publishing a digest of TLA_insights at least once a month. This also may look like a newsletter, but it really is about sharing curated insights, which may not be "news" all the time, so I am calling it an "Insights-letter".

**Why am I doing this?** Two reasons:

- 1: curate and consolidate the insights I develop, as I will further process and organize them in my mind while writing them down, and with that I improve my knowledge and command of these topics
- 2: to share these insights with others, who can also benefit from that

**How is this organized?** It is basically a collection of summaries & insights from resources I find interesting. I will be organizing these into sections, which represent areas I am really interested and actively developing/researching in the wider topic of Technical Leadership and Architecture. Currently these are the areas:

- [Sociotechnical Architecture & Systems Design](#sociotech)
- [Technical Leadership](#tech-leadership)
- [Software {Architecture, Engineering & Tech}](#software)
- [Personal Productivity](#productivity)

I hope you have fun and find some interesting insights here. Don't hesitate to [contact](mailto:emgsilva@gmail.com) me if you have questions or want to chat about these topics.

 {% assign sorted_pages = site.pages %}
 {% assign sorted_pages = sorted_pages | where_exp: "item", "item.digest == 1" | sort:"date" %}
 {% assign sociotech_pages = sorted_pages | where_exp: "item", "item.categories contains 'tla_sociotech'" %}
 {% assign techleadership_pages = sorted_pages | where_exp: "item", "item.categories contains 'tla_tech-leadership'" %}
 {% assign software_pages = sorted_pages | where_exp: "item", "item.categories contains 'tla_software'" %}
 {% assign productivity_pages = sorted_pages | where_exp: "item", "item.categories contains 'tla_productivity'" %}

<a name="sociotech"></a>
## Sociotechnical Architecture & Systems Design</h2>

{% for page in sociotech_pages %}
### <a href="{{ site.baseurl }}{{ page.url }}"> {{ page.title }} </a>
{{page.content}}
{% endfor %}

<a name="tech-leadership"></a>
## Technical Leadership

{% for page in techleadership_pages %}
### <a href="{{ site.baseurl }}{{ page.url }}"> {{ page.title }} </a>
{{page.content}}
{% endfor %}

<a name="software"></a>
## Software {Architecture, Engineering & Tech}

{% for page in software_pages %}
### <a href="{{ site.baseurl }}{{ page.url }}"> {{ page.title }} </a>
{{page.content}}
{% endfor %}

<a name="productivity"></a>
## Personal Productivity

{% for page in productivity_pages %}
### <a href="{{ site.baseurl }}{{ page.url }}"> {{ page.title }} </a>
{{page.content}}
{% endfor %}

<form style="border:1px solid #ccc;padding:3px;text-align:center;" action="https://tinyletter.com/tla_insights"
    method="post" target="popupwindow"
    onsubmit="window.open('https://tinyletter.com/tla_insights', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true">
    <p><label for="tlemail">Enter your email to be notified of future TLA_insights</label></p>
    <p><input type="text" style="width:140px" name="email" id="tlemail" /></p><input type="hidden" value="1"
      name="embed" /><input type="submit" value="Subscribe" />
</form>
