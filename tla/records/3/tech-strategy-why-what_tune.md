---
layout: post
title:  "Tech Strategy: You Need it, But What is it?, Nick Tune"
permalink: /tla_insights/tech-strategy-why-what_tune
categories: [Tech-Vision-Strategy]
tla_area: [tla, tla_tech-leadership]
id: tech-strategy-why-what_tune
digest: 3
date: 2020-11-22
summary: | 
  Great article by Nick Tune that touches on the "Why" ("the need") of Tech Strategy within (tech) organizations and "What" exactly that can look like to enable the desired effect - technical alignment and velocity.
insightweet: |
  Tech Strategy, why you need it and what it can look like (in the form of a multi-level approach: enterprise > departments > products).
---

#### [[Article](https://medium.com/nick-tune-tech-strategy-blog/tech-strategy-you-need-it-but-what-is-it-af292421e422)]

> ![light](/assets/light-bulb.png) **My Insights:** Tech Strategy is a rather ambiguous term and construct in most organizations and for most people. This has many reasons, but the fact is all organizations have a Tech Strategy (like they have a Software Architecture): sometimes it is explicit and people "see it" and align to it, sometimes it is just an non-explicit thing that exists but is interpreted differently by different people. This last form is very risky and most of the time does not enable to maximize the alignment of the different parts of the organization. That leads to incoherent and conflicting decisions, e.g.: different teams working in extremely different tech stacks, or owning non-essential infrastructure platform systems, among many other things. Having clear (enabling and non-blocking) Tech Strategies is very important for organizations to optimize their "operating model" and how to support their teams on best building their products. As discussed in the referenced article (by Nick Tune), these Tech Strategies may be defined at different levels of abstraction, e.g.: an Enterprise wide Tech Strategy, to provide the "core elements that are common to all the products and teams in the whole organization"; and then have more specific strategies per departments (if needed) and products (as they are almost always at different levels of development and deal with different customer challenges). This enables people to be aligned, and if well defined will not block teams autonomy to take the best decisions on their particular context, but enable them to take those decisions more easily. Furthermore, and essentially: Tech Strategies should be defined to drive the Business Vision and Strategy, i.e.: should not be a pure "technical exercise" but a supporting construct to enable the end goal/ambition of the organization, i.e.: they will change overtime and must adapt/evolve to match each other.

### Analysis & Summary

These insights and notes are focused on Tech Strategy, and are driven by a great article by Nick Tune that touches the "Why" ("the need") of Tech Strategy within (tech) organizations and "What" exactly that can look like to enable the desired effect - technical alignment and velocity.

"Tech Strategy" is a term we hear often, but the way people scope and define it can be rather different (and most of the time ineffective on its implementation). The most common pattern I see is this being a (long) document created purely by higher-level leadership as a "one way communication channel" to address high-level concerns and governance of Tech developments in the company. What is the issue with that? That it becomes "yet another document" that (maybe) is read once, shares "aspirations" and creates some awareness, but does not truly connect to the veins of the organization - i.e.: people don't adopt it as an effective reference/north-star on their technical developments.

Nick does a great job on sharing ways to start addressing these concerns and effectively define a Tech Strategy that can create alignment (i.e.: common direction) for the different tech activities within the org. His proposal consists of a multi-level model to define and implement/operate Tech Strategy in organizations, namely:

- Enterprise level Tech Strategy
- Business/Department level Tech Strategy
- Product level Tech Strategy

**Enterprise-level Tech Strategy** focuses on the most foundational level of Tech Strategy. It provides a base and guidance for all the other Tech Strategy levels. This level may contain different elements and sections, namely:

- Business and Organizational Context: starts with a clear positioning and understanding of the "business and organization context", i.e.: the purpose and goals behind the business and/or product(s) we are building. This should be a strong driver for the Tech Strategy (i.e.: "the Why" behind defining a certain Tech Strategy). If there is no clear understanding of the business behind, the Tech Strategy is "not grounded" (as Nick mentions: "if you can't communicate the problem you are solving, you probably should not be creating a strategy").
- High-level IT Vision: defines the technology vision that will enable supporting business/products vision and strategy. This section may be rather "high-level vision", focusing on the big elements, which provide a "north star" for the different strategies being defined.
- Current IT Landscape: this presents an overview of the current IT landscape. Make explicit how our current landscape looks like, so we can start seeing how we can move from "as-is" to the "high-level IT vision" (the "to-be" situation). This section may also list challenges we are facing on the current landscape.
- Proposed IT Landscape: depicts an overview of the vision for the landscape, justifying the proposed vision and how the different elements that define the desired target state. A recurring issue in this part (as Nick mentions) is the lack of attention to "organizational setup" that will be building and owning those the depicted target IT landscape (yes, this is Conway's Law - i.e.: the organizational and technical components/systems must be aligned). Another important point in this section is: we want to provide some clarity on the most foundational elements of the IT landscape, but not be too prescriptive - i.e.: "Ivory Tower Architects".
- Who creates this strategy? This is a great question and one I do not have a clear answer. I do agree with Nick: "responsibility for enterprise-level tech strategy resides with senior IT leaders". However, we should involve people that can understand and work with all those parts to bring together a strategy that enables them. Involving can be done in different manners, and does not mean this makes people involved "responsible".
- Who is it intended for? This level of Tech Strategy is normally intended for "everyone". Example: it allows "middle management" to have guidance, but also provides clear guidelines/direction for teams building applications/systems and taking decisions on how to evolve them.

**Business/Department level Tech Strategy** addresses strategies targeting particular elements of departments/parts of the company. This level contains things such as:

- Agreements and alignment regarding policies, standardizations and how the teams in the department plan to move in terms of technical strategies.
- These strategies should touch on elements to drive technology decisions, but also processes, people and priority setting (i.e.: be a sort of framework that enables people navigate through their decision making processes within a given business department).
- Who creates this strategy and who is it for? In general someone within an IT leadership position within that department or business unity (with the involvement of people from different parts, including the people that are going to use this). This document tends to be targeted to the people delivering the work, i.e.: it is a sort of blueprint or guidebook acting as alignment across the different teams.

**Product level Tech Strategy** entails specific elements for a product within a department:

- Having Product-level strategy is very important as different products require different strategies, e.g.: some products may be greenfield - and allow for different technical solutions to be crafted; while many times products are in place and have certain teams and ways of working, which impose specific constraints and conditions on the strategies for them.
- This is a key strategy level in modern product-led organizations to enable products to sharpen their strategies to the particular challenges of the product. To enable that, the enterprise and department strategies should really be lean and focus on creating guidance/accelerate teams on elements that are common to all products, while not block innovation on the developments of products.
- Tech Strategy at this level tends to have good architectural diagrams to help show where we are and where we want to go. Furthermore, it will also provide clear guidelines on "practices" recommended, in order to have alignment across the different teams that are contributing to building the product.

Nick finishes with this question: "So what is Tech Strategy and When do we need it?

- In his own words: "Tech strategy is a collective set of non-trivial decisions created to guide the use of technology and related factors in order to achieve business or end-user outcomes. It involves not just technology choices, but process, organization design, and cultural elements."

Some extra remarks:

- It is about "alignment" and "guidance" to navigate "decision making" processes, and that is why it is so important to have different levels of granularity - to align across company, per department and per product.
- It can have different forms, it is not an exact science. The important thing is to "set clear game rules and language" at the start and have a clear understanding of the "Why" for the Tech Strategy. This can vary from company to company, but in general it should be linked to the business/product strategies and vision, as a way to enable them.
- Tech Strategies at the different levels evolve, like anything within organizations. Given this, don't write your strategies on stone, but create feedback loops/mechanisms to continuously observe your org, and take that knowledge and insights to "calibrate" the Tech vision and strategies.

**InsighTweet**

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">💡 <a href="https://twitter.com/hashtag/TLA_insights?src=hash&amp;ref_src=twsrc%5Etfw">#TLA_insights</a>: Tech Strategy, why you need it and what it can look like (in the form of a multi-level approach: enterprise &gt; departments &gt; products).<br><br>References: <a href="https://twitter.com/ntcoding?ref_src=twsrc%5Etfw">@ntcoding</a><br><br>+details ⤵️<a href="https://t.co/WyqDNcWXey">https://t.co/WyqDNcWXey</a></p>&mdash; Eduardo da Silva (@emgsilva) <a href="https://twitter.com/emgsilva/status/1330987553684680704?ref_src=twsrc%5Etfw">November 23, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
