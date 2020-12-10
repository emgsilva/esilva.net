---
layout: post
title: GitLab Strategy Operating Model
permalink: /tla_insights/strategy_operating_model-gitlab
categories: [tla, tla_tech-leadership]
id: direction_strategy_operating_model-gitlab
digest: 3
date: 2020-11-29
---

> ![light](/assets/light-bulb.png) **My Insights:** defining company and product (or Tech) vision and strategy is just one part of the equation. Many times people forget about the goal of such activities, which is (in my view): to help the company to understand where to move to ("the vision") and (in different time-windows) what strategies and/or plans to move forward in order to take steps towards that vision. GitLab has a rather explicit approach to comprehensively address this, which I find very refreshing. They define clear time-windows and a cadence of activities per phase. This is key and crucial, as we cannot have the same type of actions/activities on a 1 year time-window and a 10 (or even more 30) year window. In far future time-windows (e.g.: 10 or 30 years time) we plans make no sense (the world is a "Chaotic System" - as in Cynefin [<a href="#cynefin">Cynefin</a>], so you "cannot" plan in such time-windows). However, that does not mean we can set a "vision" and/or "north star" to set a common long-term goal/direction for the whole company and product. Furthermore, there are things we can work on in the present to enable moving towards that vision. These tend to be "Values" and foundations for growth, which don't necessarily need a clear plan for a 30 year window. The shorter term strategies, e.g.: 3 year strategies, are much more closer to plans of action. For these we can define "strategic themes" which are more specific and zoom-in into the specific topics to work on the product development in coming years. With that, we can (for example) yearly define even more concrete investment plans, which then can be aligned by the whole company in a regular fashion (e.g.: Quarterly via OKRs and measuring KPIs that enable assessing progress). This connected strategic approach with the right sort of action/focus per period is a powerful tool to enable developing and moving forward as a company and product - i.e.: defines a sort of "Strategy Operating Model".

(Subscribe <a href="https://tinyletter.com/tla_insights" target="_blank">here</a> or <a href="https://twitter.com/emgsilva">follow me on Twitter</a> to get notified about new TLA_insights)

### Analysis & Summary

The insights and notes of this record are inspired and driven by multiple "open resources" from GitLab used to provide the company with an aligned "direction and strategy" for their organization and product development. In this article I mostly focus on the general principles behind the company and product vision and strategy. However, these can be easily extended and used to define Tech organization vision and strategy. 

GitLab is a truly inspiring company: they are fully remote and extremely open on their strategies and ways of working. Sid Sijbrandij (GitLab's CEO) shares [<a href="#gitlab-open-strategy">GitLab-Open-Strategy</a>] that this "Open Strategy" is key to enable customers to understand "why certain choices are made" and this explicitness is key to make clear to everyone around the world working at GitLab what are the important things to focus on. This is very explicit on this statement at the bottom of their Strategy page [<a href="#gitlab-strategy">GitLab-Strategy</a>]:

> *Our strategy is completely public because transparency is one of our values. We're not afraid of sharing our strategy because, as Peter Drucker said, "Strategy is a commodity, execution is an art."*

In the following I will share some notes on some core documents GitLab used to shape and operate the vision and strategy at GitLab.

**GitLab Strategy** [<a href="#gitlab-strategy">GitLab-Strategy</a>] document defines core elements of the "operating model" for the company with respect of company strategy. It specifies the Why, What, How and When elements on different strategic time periods/windows in the future.

<div align="center"><img src="/assets/gitlab-strategy-om.png" alt="GitLab Strategy" width="750"/></div><br>

(Credits: GitLab Strategy page [<a href="#gitlab-strategy">GitLab-Strategy</a>])

- **30 years: Mission**
  - **Why**: sharp motivation for GitLabs existence: "everyone can contribute".
  - What: focus on the Mission (long term vision for the company, sort of "North Star"). This is a really inspiring message ("when everyone can contribute... we greatly increase the rate of human progress"). To achieve this mission GiLab further defines what they call a BHAG ("Big Hairy Audacious Goal"), which basically puts down a very their 30-year audacious goal ("in the next 30 years become the most popular collaboration tool for knowledge workers...").
  - **How**: to step towards this (really) long-term mission (~30 years in the future) GitLab focuses on "Values", i.e.: the "heart and blood of the company". This is the sort of thing we can focus and (with high level of confidence) develop now in order to step towards that long-term mission. I find this a very strategic and pragmatic approach, as at this time-window you cannot make plans, the level of uncertainty is just too high (i.e.: plans at this time-window tend to be "wild guesses" → waste!). So, focusing on creating strong Values to drive how you operate your company is your best "bet".
- **10 years: Vision**
  - **What**: at this time-window GitLab defines "Vision" and "Goals". (Product) Vision is a paragraph statement for the "target state" envisioned for the Product ("single application... that enables everyone should be able to afford and adapt... everyone can contribute"). Then the Goals section defines a list of more concrete points, which sort of defines the "strategic areas" for the company and product to focus on.
  - How: to scope and enable stepping towards that vision GitLab defines a series of core elements that provide context and scope for this 10 year product vision. For example, it details the view on "Everyone can Contribute", "Customer Acceptance" but also clear statements on the fact that the market is evolving and also risks around the product. All in all, the "How" at this time-window focuses on scoping a bit further the direction for the product development, while having room and clear that this is not yet specific enough, so it also has clear statements on managing risks and leaving room for "maneuverability" to cope with the market and forces around the product.
- **3 year: Strategy**
  - **What**: defines the specific 3-year strategic goal ("become the leading complete DevOps platform") and then details strategic themes and priorities to enable accomplish that goal (which per se aims at realizing the (10 year) "Vision"/"Goals"). In this section a few (in case of GitLab 4) strategic themes are presented, which really set the scopes GitLab wants to focus in the next 3 years. These are "action statements", e.g.: "Accelerate market maturity around the DevOps Platform". This is shaped iteratively (using GitLab's Merge Requests (MRs) in order to sharpen it up.
  - **How**: the how to develop work on these strategic themes (for coming 3 years) is founded on a few elements, namely:
    - Principles: to guide how teams/people execute their work. Example: being "fast follower", they don't want to/need-to be the first on doing something, but want to be able to move fast on embedding the great developments on their area.
    - Assumptions: which defines and scopes elements that provide a "context" for the company to be on the same page (especially important on decision making and how they work). Example: "Open Source stewardship", which defines this clear assumption that as a company they will put "the wider community first... and play well with others and shape the pie with other organizations commercializing GitLab".
    - Pricing: provides a clear picture of the GitLab pricing model.
    - Dual Flywheels: setting clear the "business model" and "development strategy" for the product (and company). Namely GitLab has an open-core model, which means investment on the open source will drive more features that can be embedded on their commercial offerings, which then brings more users and also revenues/contributions. It is really interesting to have this also as part of setting the strategic context (i.e.: people joining the company can get this clearly in a few minutes and get into the right frame).
    - KPIs: key element to measure success of the strategies and the development of the product. In this section you can see the essential KPIs, to which part of the flywheel they belong to and who is owner of that.
- **1 year: Plan**
  - **What**: these are the actual investments to be made on tactical strategies and implementations over the next year. These align and contribute to the 3 year strategic themes. This is a rather concrete plan, which defines the investment on the portfolio of products of the company over the next year.
  - **How**: on this part of the document we are redirected to a page GitLab calls "Direction" [<a href="#gitlab-direction">GitLab-Direction</a>]. This is a rather interesting page from GitLab, and it basically focuses on setting clear the Product Vision and Strategy (which provides "Direction" to the whole company). This page has several sections, namely:
    - Vision: which coincides with the Strategy page (10 year) Vision - to set clear the big vision topics.
    - 3 year Strategy: which extends the Strategy page "3 year strategy" section by with a more detailed overview. In this section they follow a very interesting template, namely, based on the general "Strategic Themes" defined they define more specific "Strategic Challenges" and the "Strategic Responses" they foresee to approach them. Again, this enables people to start aligning on the important "challenges" and also get ideas on the "responses" that we will (most likely) follow when defining more specific plans.
    - 1 year plan:  at this levels you get a very sharp set of key themes to work on the product over the next year. They provide detailed plan per theme so that everyone can understand them (and the implications).
    - Quarterly Objectives and Key Results (OKRs): to make sure that goals are clearly defined (and in sync with the yearly plan) and aligned throughout the organization.

GitLab "explicitness" on how they approach their vision, strategy and planning does not stop in these two core documents ("Strategy" and "Direction"). They have another very interesting document called "Cadence" [<a href="#gitlab-cadence">GitLab-Cadence</a>], which basically puts on paper the company cadence, i.e.: the time-periods/windows they have and the types of activities the company and its people do in each. Bellow I present a simplified overview of GitLab's cadence (and a list some of the core activities per period):

1. **Day**
    1. Team work
    2. Calls
2. **Week (5 workdays)**
    1. 1-1 cadences
    2. Team work
3. **Month (4.3 weeks)**
    - Releases
    - Retrospectives
    - KPIs
4. **Quarter (3 months)**
    - OKRs
5. **Year (4 quarters)**
    - Annual plan
    - Most Direction
6. **Strategy (3 years)**
    - Most Strategy
    - Some Direction
7. **Vision (10 years, 3.3x)**
    - Product Vision
    - Principles
    - Vision Areas
8. **Mission (30 years, 3x)**
    - Mission
    - BHAG (Big Hairy Ambitious Goal)
    - Values

This clarity and connected strategies provides a lot of clarity and in a way sets a clear "Operating Model" for the company, i.e.: how the different people (spread over the world) get a clear understanding and direction on what is important and what to focus on. This enables them to build on each others developments instead of pushing in different ways.

### References

- [Cynefin] [https://en.wikipedia.org/wiki/Cynefin_framework](https://en.wikipedia.org/wiki/Cynefin_framework); [The Cynefin Framework (Video)](https://www.youtube.com/watch?v=N7oz366X0-8), Dave Snowden <a name="cynefin"></a>
- [GitLab-Open-Strategy] [https://about.gitlab.com/blog/2016/02/09/gitlab-open-strategy](https://about.gitlab.com/blog/2016/02/09/gitlab-open-strategy/)<a name="gitlab-open-strategy"></a>
- [GitLab-Strategy] [https://about.gitlab.com/company/strategy](https://about.gitlab.com/company/strategy)<a name="gitlab-strategy"></a>
- [GitLab-Direction] [https://about.gitlab.com/direction](https://about.gitlab.com/direction)<a name="gitlab-direction"></a>
- [GitLab-Cadence] [https://about.gitlab.com/handbook/ceo/cadence](https://about.gitlab.com/handbook/ceo/cadence)<a name="gitlab-cadence"></a>

<br>

<form style="border:1px solid #ccc;padding:3px;text-align:center;" action="https://tinyletter.com/tla_insights"
  method="post" target="popupwindow"
  onsubmit="window.open('https://tinyletter.com/tla_insights', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true">
  <p><label for="tlemail">Enter your email to be notified of future TLA_insights</label></p>
  <p><input type="text" style="width:140px" name="email" id="tlemail" /></p><input type="hidden" value="1"
    name="embed" /><input type="submit" value="Subscribe" />
</form>
