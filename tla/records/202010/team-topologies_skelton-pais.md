---
layout: post
title:  Team Topologies, Matthew Skelton & Manuel Pais
permalink: /tla_insights/team-topologies_skelton-pais
categories: [tla, tla_sociotech]
id: team-topologies_skelton-pais
digest: 2
date: 2020-10-09
---

#### [[Book](https://www.teamtopologies.com)]

> ![light](/assets/light-bulb.png) **My Insights:** Team Topologies is a great contribution to develop and mature many of the elements required to set up sociotechnical systems & architectures. It brings many insights and raises awareness on the issues organizations may get into if they ignore to have an holistic co-design approach of their of technical and organizational systems. Furthermore, the book gives a clear, small and simple language to discuss, design and evolve team setups and interactions. As I said on my review of the book: "To me, Team Topologies is becoming a reference book to help on the design and evolution of organizations and their sociotechnical architecture!"

### Analysis & Summary

The book Team Topologies is one of those books that brings a lot of interesting ideas to the table, but also provide clear and actionable principles and constructs that one can immediately start using. In a nutshell, the book focuses on how to set up teams (business and technology) and organization for "fast flow". What does it mean? Means to explicitly consider Conway's Law; means considering the teams size and "cognitive load" (when interacting with other teams and owning their applications) when setting up strategies for our products, i.e.: stop to purely focus on the design of the technical system and also consider the actual organizational system in the problem & solution design space. Their proposal to approach this is to have a "team-first strategy", in which the team "cognitive load" is a major variable on assessing whether the team can successfully own a new product (or be part of a given activity). In order to design these teams and also mitigate on how to empower them they present 4 different "Team Topologies" (see Figure bellow).

<div align="center"><img src="/assets/team-topologies-team-types.png" alt="Team Topologies" width="650"/></div><br>

- **Stream Aligned Teams (SATs)**: the teams building a part of the product that supports a certain value stream to the customer.
- **Enabling Teams**: facilitate SATs on overcoming obstacles and in that way enable them to do better. Detect missing capabilities and can help on elements that don't necessarily belong to any specific SAT.
- **Complicated Subsystem Teams**: are teams that own complex parts of the landscape, which by being abstracted into such sub-systems enable to simplify the applications from SATs and with that reduce the required team cognitive load. By having a simpler product the SAT can also increase their velocity (compared with when they have to own such complex systems by themselves).
- **Platform Teams**: focus on building "internal products" that accelerate and simplify how SATs build their own applications (and products). This is done by taking away complexity of SATs, which enables them to have more cognitive load available to work on the business problems.

The goal is to have Stream-Aligned Teams (SATs) working at high-velocity on improving their value stream of the product (to their customer). For that, we have the other three team topologies supporting different aspects to empower SATs.

However, teams don't live in isolation, nor are static in time (a classical mistake of "org design" - the authors propose instead to think about "org dynamics", as organizations change and evolve, and so having ways to address that explicitly helps). For this the authors propose three interaction modes for teams (see Figure bellow).

<div align="center">
<img src="/assets/team-topologies-interaction-modes.png" alt="Team Topologies Interactions" width="650"/><br>
<sub>(Image Credits: Team Topologies, Matthew Skelton and Manuel Pais.)</sub></div>

- **Collaboration**: interaction mode where two (or more) teams collaborate for a defined period of time to learn and discover how to proceed on their developments (e.g.: identify boundaries of a legacy system and with that each team can own a clear boundary and proceed to work on it on their own).
- **Facilitating**: one team helps and mentors another team. This is a very common interaction mode to enable bringing new knowledge within the team or kickstart something new.
- **X-as-a-Service**: one team provides another with something "as a service" (e.g.: an API with a clear contract that the other team can consume without the need of continuous collaboration).

The book has a lot of amazing complementary [resources](https://teamtopologies.com/resources), you can find them here. Furthermore, they also have multiple open source [resources](https://github.com/teamtopologies) on GitHub (such as different templates for assessing cognitive load, setting up Team APIs, among others).

(Find my in-depth review of the book [here](https://esilva.net/articles/review-team_topologies))

**InsighTweet**

<blockquote class="twitter-tweet"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/TLA_insights?src=hash&amp;ref_src=twsrc%5Etfw">#TLA_insights</a>: Team Topologies provides a language to design and evolve orgs and their sociotechnical architecture, i.e.: set up teams that can own &amp; iterate on their products at high-velocity.<br><br>References: <a href="https://twitter.com/TeamTopologies?ref_src=twsrc%5Etfw">@teamTopologies</a>, <a href="https://twitter.com/manupaisable?ref_src=twsrc%5Etfw">@manupaisable</a>, <a href="https://twitter.com/matthewpskelton?ref_src=twsrc%5Etfw">@matthewpskelton</a><a href="https://t.co/wRFbvFZjSY">https://t.co/wRFbvFZjSY</a></p>&mdash; Eduardo da Silva (@emgsilva) <a href="https://twitter.com/emgsilva/status/1317098468524101634?ref_src=twsrc%5Etfw">October 16, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<br>

<form style="border:1px solid #ccc;padding:3px;text-align:center;" action="https://tinyletter.com/tla_insights"
  method="post" target="popupwindow"
  onsubmit="window.open('https://tinyletter.com/tla_insights', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true">
  <p><label for="tlemail">Enter your email to be notified of future TLA_insights</label></p>
  <p><input type="text" style="width:140px" name="email" id="tlemail" /></p><input type="hidden" value="1"
    name="embed" /><input type="submit" value="Subscribe" />
</form>
