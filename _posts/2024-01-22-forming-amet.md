---
layout: post
title:  "Forming an Architecture Modernization Enabling Team (AMET)"
---

> _I co-authored this article with [Nick Tune](https://nick-tune.me/) ([article on Nick's blog](https://medium.com/nick-tune-tech-strategy-blog/forming-an-architecture-modernization-enabling-team-amet-50d70a789331)) based on our experiences and learnings from working together with clients on architecture modernization initiatives. This is the second article of a series on Architecture Modernization Enabling Teams (AMETs). Find more about AMETs here: <a href="/amet">esilva.net/amet</a>_

<br>

Architecture modernization initiatives are strategic efforts involving many teams, usually for many months or years. They often compete with product/feature development work, resulting in them falling flat and failing to deliver the promised business benefits that triggered them.

To address this concern and increase the chances of a successful modernization, we [previously wrote](https://esilva.net/articles/architecture-modernization-enabling-team) about an effective pattern we have observed in our work as consultants working with various clients - Architecture Modernization Enabling Teams (AMET).

> AMET Definition: An AMET is an architecture Enabling Team that helps to coordinate and upskill all teams and stakeholders involved in a modernization initiative.

In this article, we address one of the most important and difficult challenges we see organizations we work with facing when introducing an AMET - forming the team and setting it up for success. To help answer those questions, this article covers when to form an AMET and how to do it effectively by following a structured approach we have been developing over the past year.

## When to form an AMET

No single point in a modernization journey is universally optimal for forming an AMET. It depends on factors like:

- Size and scope of modernization
- Pre-existing modernization efforts that help justify and support the new AMET
- Capabilities of existing teams and structures to modernize without additional support (e.g., external consultants or training)
- Preference for waiting for the problems to arise (indicating the need for an AMET) or forming an AMET early to prevent issues arising
- Confidence level that modernization will actually happen (sometimes it is just too unclear and lacking priority)
- How quickly do you want/need to modernize?
- Expected level of pushback, politics, and inertia
- Whether you want people 100% dedicated to supporting the modernization
- Amount of time the AMET needs to prepare and upskill itself
- And many others

Understanding how modernization journeys get started is useful for identifying when it is a good moment to form an AMET in your context. The figure below shows the typical life-cycle of an architecture modernization initiative, including commonly observed points where we have observed AMET formation.

<div align="center"><a href="/assets/forming-amet.png"><img src="/assets/forming-amet.png" alt="Forming AMET" width="90%"/></a></div>
<br>

Typically, there’s a period where modernization is discussed as the pains of legacy systems and/or ways of working are noticed and become ever more prominent, blocking the business strategy. Some companies talk about modernizing for years before they make a serious commitment. We informally call this the **Noticing stage**.

At some point, additional effort will be invested in identifying the value, costs, and planning for the modernization. We refer to this as the **Framing and Validating stage**. Sometimes, this happens abruptly during a crisis. Other times, it emerges as a bottom-up initiative led by teams fed up with the current situation.

A **Typical AMET** is usually formed as *Framing and Validating* starts to confirm a serious need for modernization and an AMET to do it successfully. Sometimes, **Early AMETs** are formed during the *Noticing* state or at the start of *Framing and Validating*. That earlier formation happens because the AMET needs to commit more time to help facilitate the modernization earlier. It may also need to upskill itself to be ready when serious modernization begins.

If *Framing & Validating* proceeds well, the next escalation is typically an investment in modernization. In our work with clients, we have seen companies starting small with one or two teams while others immediately go for a larger investment. The size, scale, and timeframes all vary significantly. We usually call this the **Kickstarting stage** because it’s about building the initial momentum where some modernization is starting. However, buy-in for the full scope of modernization is generally yet to be secured.

If the *Kickstarting* stage proves successful and the desired investment is attained, modernization moves towards the **Executing stage** - a wider investment in modernization is secured, and modernization scales out. We have seen that companies don’t realize the need for AMET until during this stage or wait until a clear need has arisen, effectively a **Late AMET**.

## How to effectively form an AMET

Recently, we helped multiple organizations kickstart their modernization journeys and form AMETs. We noticed many uncertainties around forming an AMET, like who should be on the team, what the team should work on, how they should work, and how much time to spend on AMET work.

This section outlines a structured approach to addressing the key aspects of forming effective AMETs - by leveraging the AMET API Canvas ([available on Miro](https://miro.com/app/board/uXjVN64eHFE=/?share_link_id=722010282564)), a type of [Team API](https://github.com/TeamTopologies/Team-API-template). We use it to ask important questions and discuss essential topics to consider when forming an AMET. This will likely surface tensions that must be addressed to set the team up for success.

<div align="center"><a href="/assets/amet-api-canvas.png"><img src="/assets/amet-api-canvas.png" alt="AMET API Canvas" width="90%"/></a></div>
<br>

To demonstrate this process, we will build a canvas for the following fictitious example (inspired by real examples from our consulting work).

> *A large logistics company wants to expand into new verticals and integrate its offerings into an emerging open marketplace. They are targeting 3 - 5x revenue growth in the next 5 years.*
>
> *Their technology landscape has a high level of what they consider to be legacy or heritage systems — monolithic systems with tens or hundreds of developers working in them.*
>
> *Adding new features is inefficient, and deployments happen once per month.*
>
> *The organization needs to innovate faster to become more competitive. They need a more loosely coupled architecture and empowered teams.*
>  
> *The Warehousing Modernization Enabling Team (an AMET) has been established to guide modernization in the Warehousing domain, which consists of 100+ software engineers and a monolithic codebase.*

### Name

<div align="center"><a href="/assets/amet-api-canvas-name.png"><img src="/assets/amet-api-canvas-name.png" alt="AMET API Canvas / Name" width="90%"/></a></div>
<br>

Naming an AMET is important because it is part of the team's identity and affects how they are perceived by others. As mentioned in our previous article, we recommend a name that reflects the team's purpose and area of responsibility.

In our example, we named the “Warehousing Modernization Enabling Team”, articulating their scope and enabling focus.

### Mission

<div align="center"><a href="/assets/amet-api-canvas-mission.png"><img src="/assets/amet-api-canvas-mission.png" alt="AMET API Canvas / Mission" width="90%"/></a></div>
<br>

We've observed that when forming an AMET, defining their precise purpose can be difficult, especially concerning how their responsibilities relate to other teams and the exact mandate the team has.

When the purpose is unclear, the team isn't sure what they should do. When the mandate isn't clear, the team may be unsure exactly what they are accountable for, and other teams might refuse to take them seriously.

To help with this, we recommend structuring the mission section into 4 sub-sections: scope, business opportunity, current obstacles, and mandate. You can add more if you wish, but we suggest these four as a minimum.

- **Scope**: the part of the business, architecture, and/or operating model that AMET supports. In our example, the AMET is responsible for the operating model of the warehousing domain, which comprises around 10 teams.
- **Business opportunity**: the primary reason for the modernization. Is the company looking to expand into new markets, build new products, reduce costs, consolidate acquisitions, or something else? And how does this scope (to be modernized) support those business objectives?
- **Existing obstacles:** What is insufficient about the current system and operating model that necessitates modernization to best address the desired business opportunity?
- **Team mandate**: the team's principal objective(s) and level of influence. Are they just there to provide advice and encouragement, or can they exert more influence if necessary? In the warehousing example, it is clear that the team is working on behalf of the VP Eng to ensure objectives are achieved. They will try to lead by influence but have the authority to drive the modernization when needed.

This section of the canvas shouldn't be too verbose: a summary of the key points and links to other more detailed documentation and resources, such as the strategy deck or wiki.

### Team Members

<div align="center"><a href="/assets/amet-api-canvas-members.png"><img src="/assets/amet-api-canvas-members.png" alt="AMET API Canvas / Team Members" width="90%"/></a></div>
<br>

As a good [Enabling Team](https://teamtopologies.com/key-concepts), the AMET should be formed of people who can help upskill and address missing capabilities in modernization topics. These can be people from teams (pioneering ways of addressing the modernization) or experts (including external experts if the org does not yet have the skills required for the modernization). Given the complexity of the modernization efforts, the AMET should also have people who are good at facilitating complex initiatives and coaching people.

One common challenge we see in this stage is to be clear about how much time each team member can commit. We regularly find organizations that want to form an AMET with skilled and senior people who already have many existing commitments, which makes it challenging for them to contribute much.

When filling out the canvas, we recommend being explicit and honest up-front by listing the people involved, what they bring to the team, and precisely how much time they can spend doing AMET work. Without clarity on the team's capacity, you won't know if the team's mission is achievable.

In addition to team members, we also suggest listing key partners. People or groups that the team will regularly interact with or may impact in some way. If you are unsure whether certain topics will be handled by the AMET or a partner, just make a note here to explore later. Remember: the AMET should not be trying to do everything themselves.

### Targets and Metrics

<div align="center"><a href="/assets/amet-api-canvas-targets_metrics.png"><img src="/assets/amet-api-canvas-targets_metrics.png" alt="AMET API Canvas / Targets and Metrics" width="90%"/></a></div>
<br>

Clear targets with measurable outcomes help to solidify an AMET's mission, keep tabs on the level and speed of progress, and communicate the team's. They serve as an effective dashboard for the AMET and other teams involved in modernization.

Usually, targets are derived from the overall modernization objectives since an AMET exists to support the modernization journey. However, an AMET is not solely responsible for certain modernization metrics; it may derive its input metrics that more precisely track their contribution.

As a default format for structuring this canvas section, we suggest a tree-like structure that starts with the **top-level target** for the AMET and branches off into more granular sub-targets with themes and progress metrics attached.

In our example,  the top-level modernization metric the AMET is working towards is the full transition to the Warehousing domain's new operating model. To accomplish that, they have defined two sub-targets: define the target operating model and transition to the target operating model. Each has different themes associated, like facilitating the work and upskilling.

Metrics for tracking the progress include the number of subdomains defined in the target operating model and the percentage of the legacy system that is accounted for in the target operating model. Where possible, it's nice to indicate progress as with the latter, although it's not always possible due to the total amount of work being unknown in advance as with the former.

The next section of the canvas shows how the team will work towards their target and when certain targets will be achieved.

### Roadmap

<div align="center"><a href="/assets/amet-api-canvas-roadmap.png"><img src="/assets/amet-api-canvas-roadmap.png" alt="AMET API Canvas / Roadmap" width="90%"/></a></div>
<br>

The roadmap is a tool for planning and communicating progress toward the targets and metrics. When first forming the team, drafting the roadmap also helps to sense-check that everybody is aligned and the team's expectations are achievable.

As we all know, roadmaps can be controversial. They can become rigid plans where deviations from commitments are seen as failures. Equally, there are risks in not having some roadmap-style planning and not being able to plan, which is crucial when coordination of multiple teams is involved and a mixture of modernization and general product work.

Typically, the further out roadmaps get, the less detailed they become. In the example below, you can see that we define more specifically what the AMET will be working on in the following two quarters, and for years two and three of the journey, only the high-level targets are shown.

As with all canvas sections, regularly reviewing the roadmap section and treating it as a living dashboard is a recommended practice.

### Ways of Working

<div align="center"><a href="/assets/amet-api-canvas-wow.png"><img src="/assets/amet-api-canvas-wow.png" alt="AMET API Canvas / Ways of Working" width="90%"/></a></div>
<br>

Having clear ways of working is crucial for an AMET to operate effectively. This is about the team defining how they want to work and ensuring they are all aligned on how they will operate.

We recommend breaking ways of working down into internal and external or similar:

- **Internal ways of working**: how the team will work among themselves. For example, rituals like planning, status updates, retrospectives, and other agreements like how, when, and where the team will communicate (e.g., a slack channel).
- **External ways of working**: how the team will interact with those outside the team. For example, how do people outside the team contact the AMET? What rituals does the AMET hold that others are invited to, like a periodic office hours session where anybody can drop in?

### Resources

<div align="center"><a href="/assets/amet-api-canvas-resources.png"><img src="/assets/amet-api-canvas-resources.png" alt="AMET API Canvas / Resources" width="90%"/></a></div>
<br>

While an AMET does not own parts of an architecture, it will likely manage resources related to its mission, like documentation, training material, presentations, standards, guidelines, etc.

## How to fill in the canvas

You can fill in the canvas however you feel best suits your needs. However, we recommend filling some parts of the canvas as early as possible to surface any major issues that need urgent attention, certainly before the team’s work ramps up. For example, as the first people forming the AMET come together, they can start defining the mission and targets.

You can also experiment with various workshop formats. You can mix working alone, pairs, whole group activity, and other [design aspects](https://www.whenandhowstudios.com/design-aspects) to design group experiences that give everyone in the team a voice and a chance to share their thoughts before merging responses.

We advise that the canvas always be up-to-date so anyone involved in the initiative can use it to view plans and progress. The AMET should incorporate reviewing and updating the canvas into their rituals, such as during regular review & planning sessions. In the beginning, when there is still a lot of uncertainty around modernization, it may be reviewed and updated more frequently.

## When to fill in the Canvas

As the activities progress, the AMET should be iterating on the canvas. Initially, add ideas and details, and as validation and kickstarting activities occur, add more details on the targets and metrics, roadmap, and ways of working.
