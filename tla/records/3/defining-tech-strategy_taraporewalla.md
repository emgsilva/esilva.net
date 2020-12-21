---
layout: post
title:  Defining a Tech Strategy, Sarah Taraporewalla 
permalink: /tla_insights/defining-tech-strategy_taraporewalla
categories: [Tech-Vision-Strategy]
tla_area: [tla, tla_tech-leadership]
id: defining-tech-strategy_taraporewalla
digest: 3
date: 2020-11-28
summary: |
  Elements to consider when creating what Sarah calls "The Strategy Document". What I find refreshing in this article is that Sarah does not stop on the writing of the document, but goes on and makes great remarks on the execution of the Tech Strategy (namely: how to go about distributing it and even more importantly "continuously improving it over time").
insightweet: | 
  Tech Strategy is not a project, it is a product: continuously improved and calibrated based on learnings. Goal: create more alignment and a clearer framework for decision making for teams / org.

---

#### [[Article](https://sarahtaraporewalla.com/agile/design/architecture/Defining-a-Tech-Strategy)]

> ![light](/assets/light-bulb.png) **My Insights:** In modern ("Agile + DevOps + Product-led") organizations there is a tendency to not spend time/efforts looking ahead more than a few weeks in time. While I fully agree with driving our developments incrementally based on discovery with customer, I see a lot of waste and misalignment due to the lack of longer term vision and strategy on how teams take decisions on how to build their products (and platform supporting them). This is where a clear Tech Vision and Strategy can help. Tech Vision and Strategy should be enabling, grounded and realistic, so that it empowers teams to take faster and better decisions. With this teams should be achieving better outcomes, while still have freedom to find the best approach for their specific product/challenge. A key trait to achieve this is to stop treating Tech Strategy as a (one-off) project (done purely top-down), it should be treated as a product that we continuously improve and calibrate based on our learnings (mixing top-down and bottom-up perspectives). Another very important and challenging element is to create conditions to make sure it is properly executed/operated, i.e.: making sure it is usable by teams and it captures the needs of teams and business, etc. To achieve that I strongly believe that companies need to have strong enabling people/teams/communities (e.g.: Architects and/or Tech Leads) that take more explicit ownership on "maintaining" this in close collaboration with teams and leadership.

(Subscribe <a href="https://tinyletter.com/tla_insights" target="_blank">here</a> to get notified about new TLA_insights)

### Analysis & Summary

The notes and insights of this record are driven by [an article by Sarah Taraporewalla](https://sarahtaraporewalla.com/agile/design/architecture/Defining-a-Tech-Strategy), which focuses on elements to consider when creating what Sarah calls "The Strategy Document". What I find refreshing in this article is that Sarah does not stop on the writing of the document, but goes on and makes great remarks on the execution of the Tech Strategy (namely: how to go about distributing it and even more importantly "continuously improving it over time").

The article has three main parts: Purpose; Format and Distribution, which should provide a great guidance for people looking at insights on building a Tech Strategy document.

**Purpose:** this part starts with a clear statement on how tech strategy supports the business strategy. From there it focuses on setting a clear framework for alignment and effective technical decision making. To accomplish that purpose several elements need to be considered, namely:

- Values, principles and guidelines to inform architecture and decisions.
- Architecture vision and (an idea of the first steps on the) roadmap to that vision.
- Cross-Functional Requirements (or Non-Functional Requirements - interesting fact, Sarah was the person that coined the term "Cross-Functional Requirements"). This defines guidelines to assess how we should operate our systems.
- Architecture Operating Model, which provides a framework to support the elements of the Tech Strategy in a continuous manner.

All these elements will evolve (i.e.: should be continuously updated). However, Tech Strategy should provide enough direction without requiring continuous review and updates (e.g.: should be sufficient enough to support teams for six months). Sarah recommends revisiting Tech Strategy quarterly to remind teams of the direction and update it with what we have learned from implementing the Tech Strategy. Furthermore, it also should be kept aligned with the Business Vision and Strategy - i.e.: Tech Strategy should be a living document.

> **Notes:** I strongly agree more with this "evolutionary" positioning and see its neglect as one of the major points companies fail on truly executing and benefiting their Tech Strategies. Organizations are "living and evolving systems", if our Tech Vision (*North Star of alignment of the different teams and developments*) and Strategies (*concrete initiatives we define and execute to move towards our vision*) are not "calibrated" based on that evolution (i.e.: the learnings we gather and observe) we will be operating in a sub-optimal setting. Sarah mentions "six months" of support for teams, I do agree that is a great goal for "near-future strategies", but we should also have clearer longer-term vision and strategies in order to enable more clarity and alignment for a longer period of time (this is very important to support decision making on developments that are more complex).

**Format:** Sarah recommends "wordy document instead of a slide-based approach". The main reason is that such a document (with proper images, tables, etc.) can stand on its own and people can quickly understand it without having to have someone explaining it when needed. This also becomes an excellent tool for onboarding new people. Overview of proposed sections:

- Executive Summary: few clear sentences on the title page to explain the main points of the tech vision and strategy. Additionally highlight the changes in the latest version, compared with previous (so people can quickly understand the "diff").
- Purpose: clear statement of the goal of the document - to make sure there are no misinterpretations.
- Business Strategy: contextualize the business/product vision and strategy in order to see how the Tech vision strategy can be shaped to best support those.
- Tech Vision: "elevator pitch" for "where we want to go", i.e.: this is our "North Star", and "Why" (how to connect to the previous points).
- Architecture Vision: provide an overview of the current state we are (including diagrams), the target state we want to move to and some guidelines on the first steps to move there. Important to take an evolutionary architecture approach, i.e.: assume changes will take place and we should not define a hard end-state but calibrate as we learn more.
- Cross-Functional Requirements (CRFs) : specify the CRFs/NFRs to help understand and judge how our systems should operate in Production. This provides base-lines for CFRs cross-organization and features implemented on different parts/products should adjust according to their particular requirements.
- Tech Radar: Tech Radar can be a great way to provide a balancing act between autonomy and consistency across teams in the organization. Tech Radar enables discussion on the technology portfolio used in the company, and with that there is an alignment and knowledge exchange between people in the org. The result is a clearer statement on the tools, technologies, techniques and platforms used in the organization.
- Architecture Operating Model: an approach and framework to support the architectural decisions ("the important decisions") and direction. This makes several elements explicit (e.g.: roles and responsibilities, WoW, decision making process, decision tracking, etc.), which helps in the execution/operation of the Tech Strategy.

> **Notes:** I fully agree with Sarah on the need of an operating model to make things explicit, integrated on the veins of the organization as a way to support the decision making process. To me this is one of the major problems in most Tech Strategy docs - they are just docs and don't get into the organization operating model. The result is: they are read once and then forgotten (until next year, when a new document is written from scratch), which does not yield the impact we want.

**Distribution:** avoid the endless perfectionism, create a "minimum usable version" and release it (it should be usable and not generate more questions than alignment!). Fact: it will (should) change in time, and as such will be iterating and improving it (with new learnings). Sarah shares some good pointers to "go live":

- start with a public presentation to the teams that will use it;
- follow with an email with a copy and then add the document to the teams Wiki/Confluence/etc. (make sure there is a single location where we keep the versions of the doc we produce - with the changes we make);
- iterate as needed and share the changes so people can "update" their view on it.

**InsighTweet**

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">💡 <a href="https://twitter.com/hashtag/TLA_insights?src=hash&amp;ref_src=twsrc%5Etfw">#TLA_insights</a>: Tech Strategy is not a project, it is a product: continuously improved and calibrated based on learnings. Goal: create more alignment and a clearer framework for decision making for teams / org.<br><br>References: <a href="https://twitter.com/sarahtarap?ref_src=twsrc%5Etfw">@sarahtarap</a><br><br>+details ⤵️<a href="https://t.co/YlnpYFixx1">https://t.co/YlnpYFixx1</a></p>&mdash; Eduardo da Silva (@emgsilva) <a href="https://twitter.com/emgsilva/status/1333048014370451462?ref_src=twsrc%5Etfw">November 29, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<br>

<form style="border:1px solid #ccc;padding:3px;text-align:center;" action="https://tinyletter.com/tla_insights"
  method="post" target="popupwindow"
  onsubmit="window.open('https://tinyletter.com/tla_insights', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true">
  <p><label for="tlemail">Enter your email to be notified of future TLA_insights</label></p>
  <p><input type="text" style="width:140px" name="email" id="tlemail" /></p><input type="hidden" value="1"
    name="embed" /><input type="submit" value="Subscribe" />
</form>
