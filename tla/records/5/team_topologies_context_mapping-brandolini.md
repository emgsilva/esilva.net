---
layout: post
title: About Team Topologies and Context Mapping, Alberto Brandolini 
permalink: /tla_insights/team_topologies_context_mapping-brandolini
categories: ["Socio-Technical"]
tla_area: [tla, tla_sociotech]
id: team_topologies_context_mapping-brandolini
digest: 5
date: 2021-05-07
summary: |
  Review of article by Alberto Brandolini on on the core ideas, parallels, connections and complementary points of Team Topologies and Context Mapping (and in general Strategic Domain-Driven Design (DDD) aspects). Alberto explores these ideas and presents several interesting insights that I am sure will increasingly gain more traction - as these two approaches really complement and enrich each other on a lot of aspects to approach sociotechnical architecture evolution.
insightweet: |
  Organizations need to start "speaking" a clear language for understanding and driving organization's sociotechnical architecture evolution. Team Topologies and DDD Context Mapping offer many elements for that language.
---

> ![light](/assets/light-bulb.png) **My Insights:** In this article Alberto Brandolini (inventor of [EventStorming](https://www.eventstorming.com)) goes over the parallels, connections and complementary points of Team Topologies and Context Mapping (and in general Strategic Domain-Driven Design (DDD) aspects). Although DDD tends to be associated with the "technical and functional aspect" of software architecture (the "models"), the reality is that all of the aspects of DDD are equally applicable (and relate) to organizational architecture aspects (ones that are very explicitly covered in Team Topologies book). Alberto explores the core ideas of each approach and presents several interesting insights on where these approaches complement each other and address issues that are still rather neglected and may benefit from applying this “combo” (namely "organic growth of our organizations" without explicit design and strategy). I am seeing these two approaches being picked up a lot, most of the time in separation, but some people are bringing them together. I see a lot of value in their combination and think their combined usage will be gaining more traction, as they provide a lot of interesting elements to address sociotechnical architecture evolution in a more robust manner.

(Subscribe <a href="https://tinyletter.com/tla_insights" target="_blank">here</a> or <a href="https://twitter.com/emgsilva">follow me on Twitter</a> to get notified about new TLA_insights)

## Analysis & Summary

The insights and notes of this record are inspired and driven by an [article](https://blog.avanscoperta.it/2021/04/22/about-team-topologies-and-context-mapping) from Alberto Brandolini (inventor of [EventStorming](https://www.eventstorming.com)) on the core ideas, parallels, connections and complementary points of Team Topologies and Context Mapping (and in general Strategic Domain-Driven Design (DDD) aspects). Alberto explores these ideas and presents several interesting insights that I am sure will increasingly gain more traction - as these two approaches really complement and enrich each other on a lot of aspects to approach sociotechnical architecture evolution.

### The problem Space (of proper organizational design and evolution) is largely uncharted territory

Most organizations grow organically and without clear strategies or people owning and explicitly looking at this essential element of an organization's effectiveness.

> **Notes:** I find myself repeating this a lot lately: "to address sociotechnical architecture challenges, organizations can't just do a transformation project and be done; organizations are (& should accept that they are) continuously evolving". As Matthew Reinbold [recently also said](https://twitter.com/stoplightio/status/1385207468217753602): "you are only done when there's no more organization". So, it is key to empower people and systems that cater for organization sociotechnical evolution. These shouldn't "control evolution", but foster understanding and enable conditions that support the "best evolution" (given all the understanding we have - which changes as we learn more things).

This lack of approaches and "ownership" and strategy for organization evolution leads to people taking the (what seems) “easy road” and go for adopting "successful models" that work in other organizations and contexts. Best examples here are the Spotify Model or Lean from Toyota. However, when these models are used without a clear understanding of our own organization challenges and context they tend to cause more harm than good. This is why Team Topologies and DDD Context Mapping (patterns) - among other techniques - can help a lot: **they offer a rich vocabulary and semantics (“language”) for understanding and discussing organization’s sociotechnical architecture evolution**.

### Team Topologies & Context Mapping Basic Ideas

Alberto presents [Team Topologies key concepts](https://teamtopologies.com/key-concepts) (the Four Types of Teams & Three Interaction Modes). Then he establishes a parallel with Strategic DDD Context Mapping. Context Mapping basically covers the same problem space (as Team Topologies), however uses different (and much more semantically fine grained) constructs. Example: Context Mapping Patterns offer many different types of "Collaboration" (as in Team Topologies).

He gives an overview on the mapping of teams and DDD "Bounded Contexts" (which defines a "logical and language boundary" for the “parts”/models of the architecture), and show several types of topologies for these two (e.g.: one team owning multiple Bounded Contexts; multiple teams on Bounded Context, and the "ideal setup" of One Team per Bounded Context), depicting properties and challenges on each. This is a very important clarification, as many people still think that a Team always maps into a Bounded Context (or even worse a "Microservice"). These vary a lot as a function of the state of the sociotechnical architecture and the types of Bounded Contexts we are in (i.e.: core, supporting or generic). It is key to have this in mind when approaching organizational design and evolution. Alberto touches a few interesting "drivers for evolution", e.g.: the number of Bounded Contexts, which may be a lot and may not enable to have the "ideal" one per team; another very interesting one is the nature and required speed of evolution of different Bounded Contexts: some may be very stable and others may change very often - which impose different types of dynamics and risks, and consequently also may affect the strategy we have for the teams setup.

> **Notes:** although Alberto does not touch on this in this article, an interesting dimension of team and Bounded Context setup design is the nature of the (sub)domain where the Bounded Context lies. DDD defines three major types of (sub)domains: "core" (the differentiating domains of the business/product); "supporting" (supporting to the "core" domains) or "generic" (these are generic elements that we need to run our business and product). This nature can also be mapped into the ideas from Simon Wardley and his [Wardley Maps](https://medium.com/wardleymaps), namely: products go through an evolution, it is a natural thing. This means different Bounded Contexts will be in different phases of evolution (and that will change in time). This is key to define the type of team or approach for that particular Bounded Context, e.g.: a non-core and commoditized Bounded Context may be "outsourced" or replaced with a cloud managed service, while core Bounded Contexts tend to be better served by in-house teams with a lot of available capacity (“cognitive load”) to develop those key differentiating elements of the product.

### Comparing Both Approaches

This section has a nice reflection on the differences and similarities between the approaches, e.g.: Context Mapping doesn't talk about teams (explicitly) but models. Nevertheless all its patterns can pretty much be applied to the notion of teams and their collaborations too. I really found the following remark very insightful and interesting: _"Team Topologies provides a reference towards a desirable to-be state, while DDD context mapping provides more fine-grained patterns for assessing the current state."_

> **Notes:** I agree with this remark, although we could argue that Team Topologies can provide a lot of value on assessing the "as-is" state. That will help in deciding on interesting steps of evolution. But I agree with Alberto, using (complementing it with) the richer language of DDD Context Mapping can help a lot in understanding challenges in more detail, and then be able to define conditions and strategies to evolve into a more desirable "to-be" situation.

Alberto finishes the article by making a great remark on organization evolution: _"every solution will be ephemeral by design"_. All the elements that Team Topologies and DDD Context Mapping enable and make explicit should be done in a continuous conversation (again, these two approaches provide organizations a language to discuss sociotechnical architecture evolution!). Organizations should pay attention to the context changes in order to again iterate and act on the elements that need attention. This is a continuous process, and “will never end” - and that is just how it should be. Failing to embrace and acknowledge this is a recipe for remaining on the old fashioned "organic growth", which we know is not a great place to be in our ever increasingly competitive landscape.

**InsighTweet**

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">&gt; 💡 <a href="https://twitter.com/hashtag/TLA_insights?src=hash&amp;ref_src=twsrc%5Etfw">#TLA_insights</a>: Organizations need to start &quot;speaking&quot; a clearer language to understand &amp; drive sociotechnical architecture evolution. <a href="https://twitter.com/TeamTopologies?ref_src=twsrc%5Etfw">@TeamTopologies</a> and DDD Context Mapping offer many elements for that language.<br><br>References: <a href="https://twitter.com/ziobrando?ref_src=twsrc%5Etfw">@ziobrando</a><br><br>+details ⤵️<a href="https://t.co/wIE7VhTMgT">https://t.co/wIE7VhTMgT</a></p>&mdash; Eduardo da Silva (@emgsilva) <a href="https://twitter.com/emgsilva/status/1390609721619632132?ref_src=twsrc%5Etfw">May 7, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<br>

<form style="border:1px solid #ccc;padding:3px;text-align:center;" action="https://tinyletter.com/tla_insights"
  method="post" target="popupwindow"
  onsubmit="window.open('https://tinyletter.com/tla_insights', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true">
  <p><label for="tlemail">Enter your email to be notified of future TLA_insights</label></p>
  <p><input type="text" style="width:140px" name="email" id="tlemail" /></p><input type="hidden" value="1"
    name="embed" /><input type="submit" value="Subscribe" />
</form>