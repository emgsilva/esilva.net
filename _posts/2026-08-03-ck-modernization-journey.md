---
layout: post
title: CircleK eMobility Organization Journey of Sustainble Scaling with Continuous Modernization
permalink: /case-studies/ck-emobility-modernization
visible: false
---

### Summary

This deep-dive article provides a detailed overview and analysis of the evolution of the Circle K eMobility organization over the past decade. It explores how this organization began in Norway in 2018 and evolved through different phases to address scaling and expansion needs, and how its products, organization, and architecture transformed to meet those demands. We explore and share the main challenges, improvement interventions, and insights of the different phases of this journey. We also explore how the organization adopted a continuous modernization and improvement approach, focused on learning and evolving its capabilities to support necessary growth (e.g., new locations, new products) in a more sustainable way.

**Authors:** This article was written by <a href="https://www.linkedin.com/in/emgsilva">Eduardo da Silva</a> (Independent Consultant specialized in Enabling Continuous Modernization, working with Circle K eMobility since 2023), with input and feedback from <a href="https://www.linkedin.com/in/jsolhoy">Jan Solhoy</a> (CPTO Circle K eMobility from 2022-2026), <a href="https://www.linkedin.com/in/guro-fladvad-st%C3%B8rdal-38a7b0a3">Guro Stordal</a> (Director of Technology Circle K eMobility) & <a href="https://www.linkedin.com/in/kassian-p-473b5475">Kassian Pause</a> (Director of Product).

> 💡**Eduardo Notes:** Throughout the article, we share several insights, patterns, and anti-patterns (💡) to support effective modernizations.

> **Credits:** Special thanks to everyone at Circle K eMobility. The outcomes and accomplishments we highlight in this article are the result of your daily efforts. Keep up the good work.

> You can also check out <a href="https://esilva.net/talks/#ffc_2025">FastFlowConf 2025 talk</a>, which provides a short summary of this journey.

### Table of Contents

- [Circle K eMobility](#circle-k-emobility)
- [Part 1: Startup Phase (2018 - 2022)](#part-1-startup-phase-2018---2022)
  - [Organization Overview](#organization-overview)
  - [Expansion Outside Norway](#expansion-outside-norway)
  - [Growth and Scaling Challenges](#growth-and-scaling-challenges)
  - [Improvement Interventions](#improvement-interventions)
  - [Too much focus on moving fast and building new features | Becoming a Burning Platform](#too-much-focus-on-moving-fast-and-building-new-features--becoming-a-burning-platform)
- [Part 2: Scaling Up Sustainably (2022 - 2024)](#part-2-scaling-up-sustainably-2022---2024)
  - [Platform Strategy: deeply understanding the challenges and landscape](#platform-strategy-deeply-understanding-the-challenges-and-landscape)
  - [Kickstarting Architecture Modernization](#kickstarting-architecture-modernization)
  - [First Domain Modernization Kickstarter Workshop](#first-domain-modernization-kickstarter-workshop)
  - [Overview of Domain Modernization Process & Tools](#overview-of-domain-modernization-process--tools)
  - [Pivotal Workshop: Customer Experiences](#pivotal-workshop-customer-experiences)
  - [Sustainable Domains Reorganization and Positive Outcomes](#sustainable-domains-reorganization-and-positive-outcomes)
- [Part 3: Towards Cross-functional Value Streams (2024 - Now)](#part-3-towards-cross-functional-value-streams-2024---now)
  - [Breaking silos beyond Product & Technology](#breaking-silos-beyond-product--technology)
  - [Cross-functional Value Streams Operating Model](#cross-functional-value-streams-operating-model)
- [Closing Remarks](#closing-remarks)

<div style="border:1px dotted black; padding:1em; background-color: beige">
    <h3><b>ℹ️ I offer consulting services and products on this topic</b></h3>
    <p>If you are looking for help on these topics feel free to <a href="mailto:eduardo@esilva.net">contacting me</a>, and/or check my <a href="/consulting">consulting</a> and <a href="/products">products</a> pages for more details on how I may be of help.</p>
</div>

## Circle K eMobility

Circle K is a company focused on convenience and fuel retailing. It operates on a global scale, with more than 14.000 stores across more than 25 countries.

Over the past decade, Circle K has made a strategic shift to increase its support for Electric Vehicle (EV) charging. As an established company with extensive infrastructure, the mission is to complement and extend its existing offerings and while supporting the ongoing transition to EVs.

To accomplish that, Circle K created a new organization called "eMobility". This organization was launched in Norway in 2018, and has since expanded to multiple European countries, and will continue scaling globally.

In this article, we will share our journey of starting up and scaling up, along with the challenges we faced and the improvements we made over the years to cope with the rapid growth it required.

<br>
<div align="center">
  <a href="/assets/ck-emobility-growth.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-growth.png" alt="Circle K eMobility Journey of Growth" width="100%" /></a>
  <br>
  Figure - Circle K eMobility Journey of Growth
</div>
<br>

## Part 1: Startup Phase (2018 - 2022)

In this first phase, from 2018 to about 2022, what we could call the "Startup phase", there was a big focus on kickstarting and validating things. This is why the starting initiative was called "Norway as a Lab". That framing had a clear objective: to experiment and learn how Circle K could grow its capabilities in Electric Vehicle (EV) charging and the emerging ecosystem around it.

<br>
<div align="center">
  <a href="/assets/ck-emobility-startup-phase.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-startup-phase.png" alt="Startup phase" width="100%" /></a>
  <br>
  Figure - Startup phase
</div>
<br><br>

It is important to highlight that doing so in Norway was also strategic, since Norway has been a worldwide pioneer in EV adoption, with many incentives and infrastructure available compared with other countries.

### Organization Overview

> **Note**: Throughout this article, we will use Team Topologies [TT-REF] visualizations to depict the organization across its phases over the years. To get a quick overview of the basic Team Topologies elements, check this page: <https://teamtopologies.com/key-concepts>

The following diagram provides an overview of the organization at its start, around 2018.

<br>
<div align="center">
  <a href="/assets/ck-emobility-tt-phase1.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-tt-phase1.png" alt="Team Topologies Phase 1 - Startup" width="100%" /></a>
  <br>
  Figure - Team Topologies Phase 1 - Startup
</div>
<br><br>

As we can observe, the organization was essentially one team of Business, Sales, Operations, and Network people. Business and sales people focused on exploring opportunities to establish charging locations, while operations and network people were more hands-on with setting up and managing the infrastructure. This was a small group of people who worked very closely together as a startup. Their focus was on Norway and, in particular, B2C customers.

At this stage, they decided to buy and leverage a white-label "All-in-One Charging Platform". This platform provided all the necessary basic capabilities to get started, including charger commissioning, charger management, charging apps, and payment.

As shown in the picture above, this was an external platform for Circle K eMobility. They embraced the idea of leveraging these capabilities through a third-party partner. This is a strategic move, as the organization was small and focused on experimentation, learning, and positioning itself in Norway's booming EV market. So, building all of these basic capabilities was not (yet) a priority, and if anything, would hinder that mission.

> 💡**Don't optimize too early, but make sure you can modernize continuously.** Often, organizations try to "optimize" all their capabilities too early, which stifles their ability to develop the most important and unique capabilities for their current context and specific needs. The other extreme may also be dangerous: an organization that takes too many shortcuts and lacks the conditions for sustainable evolution. Ideally, organizations should strive to enable continuous modernization [REF-Eduardo-Enabling_Continuous_Modernization_Page], strategically focus on the most pressing needs they face at the moment, and embrace the fact that certain capabilities will naturally be modernized when they become critical to achieving business goals and creating value. In the following sections, we will explore this principle in depth.
>
### Expansion Outside Norway

Around 2021, building on the experimentation and validation learnings from Norway, eMobility began expanding into other Scandinavian countries.

<br>
<div align="center">
  <a href="/assets/ck-emobility-expansion-outside-norway.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-expansion-outside-norway.png" alt="Expansion outside Norway" width="100%" /></a>
  <br>
  Figure - Expansion outside Norway
</div>
<br><br>

At the time, there were around 500 Charge Points running on the initial platform setup, but this growth also meant establishing a "Competence Center" and placing greater focus on Operational support to enable that expansion. At the same time, there were steps towards supporting a fully digital charging experience, built on top of the white-label platform in use.

Even though during those first years there was a strong focus on experimenting and validating, there was also a clear goal of building a strong foundation of competence and a team with the right skills and mindset to cope with the organization's rapid growth. This was a deliberate and crucial focus, as we can see in the following testimony from Hakon Stiksrud, VP of Global eMobility.

<br>
<div align="center">
  <a href="/assets/ck-emobility-hakon-testimony.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-hakon-testimony.png" alt="Testimony Hakon Stiksrud" width="100%" /></a>
  <br>
  Figure - Testimony Hakon Stiksrud
</div>
<br>

### Growth and Scaling Challenges

The years went by, and the growth continued; so did the ambitions to further scale. This also meant that, naturally, some challenges began to emerge to support that scaling. The following diagram details some of the most relevant challenges observed around 2021.

<br>
<div align="center">
  <a href="/assets/ck-emobility-tt-phase2.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-tt-phase2.png" alt="Growth and scaling challenges" width="100%" /></a>
  <br>
  Figure - Growth and scaling challenges
</div>
<br><br>

In particular, there were four interesting challenges:

- **New business domains started emerging (e.g., B2B and Home Charging)**, requiring additional capabilities.
- **Scaling to new geographies required customizations** that were difficult to accomplish on the existing setup and white-label platform.
- **The platform was lagging in “Charging Operations” capabilities** required for new products and geographies.
- **The Platform “White-label App” was not suitable to customize experiences** in the new domains and geographies

These challenges were natural at this stage of the business and were driven by its growth and expansion. As these challenges and signals became clearer, the organization took several actions/improvement interventions to address them.

> 💡**Listen to the signals for evolution**: Every successful business will eventually have growth challenges. They are not bad; they are a natural part of the journey of growing and coping with changes in customers and the market, and other elements of the "Environment", such as technological and regulatory changes. Organizations should not try to avoid these challenges or try to prepare for them too early. Instead, they should strive to have the conditions to listen to these “signals” and to respond to them effectively. This is a core principle of enabling continuous modernization [REF-Eduardo-Enabling_Continuous_Modernization] in organizations.

### Improvement Interventions

Informed by those challenges and signals for evolution, the organization took several improvement steps. The following diagram details the main improvement interventions (✅).

<br>
<div align="center">
  <a href="/assets/ck-emobility-tt-phase3.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-tt-phase3.png" alt="Improvement interventions to cope with growth challenges" width="100%" /></a>
  <br>
  Figure - Improvement interventions to cope with growth challenges
</div>
<br><br>

In essence, there were two main areas of improvement:

✅ **Kickstart In-house Product Management, Design, and Engineering capabilities** to meet the increasing demand for customized product development across new lines of business and expanding geographies. The focus was on increasing the organization's capabilities in Product Management, Product Design, and Engineering. This was done by hiring for those roles and establishing those functions in the organization. Product Management and Product Design joined the existing team in Norway, while Engineering Teams were set up in Circle K's Poland Development. This move was also fundamental to coping with the limitations of the "white-label mobile apps." Now, these new people could create better apps that improved the charging experience.

**✅ Improved Charging Platform capabilities** - to cope with the lagging charging platform capabilities,
a decision was made to adopt a second, more feature-rich platform. This move helped address the lagging charging operations and the need for more advanced capabilities required in new geographies.

With these improvements, the company was better equipped to cope with the urgent need to expand its product line and enter other Scandinavian countries.

### Becoming a Burning Platform

Even though the improvement interventions introduced in the previous section worked for a while, the company's growth continued at a rapid pace. This meant hiring more people and creating multiple teams focused on the different activities that the original small multidisciplinary team handled. For example, setting up a "Business Development" team, "Sales & Marketing" team, "Product Management" Team, among others. Also, the Engineering teams were growing to keep up with the increased demand to build new custom capabilities across the different domains and countries being supported. This rapid growth was a natural consequence of the success of the first years of activities.

However, at this stage, there was an intense focus on building new features and scaling the key functions needed to continue growing the business. This was done in a way that led to the architecture of the teams and systems being built rather organically. As depicted in the following diagram, at this moment, several teams were working together on the same systems and problems, with many unclear (or "undefined") interactions with each other because their focus and scope of work were blurred.

<br>
<div align="center">
  <a href="/assets/ck-emobility-tt-phase4.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-tt-phase4.png" alt="Undefined teams and interactions" width="100%" /></a>
  <br>
  Figure - Undefined teams and interactions
</div>
<br><br>

> **💡 Phase of "Undefined Interactions" and "Undefined Team Types"** - as you can see in the diagram above, there are several "undefined interactions" and "undefined team types". When modeling organizations using Team Topologies language, it is important to express that these "undefined" teams and interactions exist and don't fit the fundamental Team Topologies team types or interaction modes. Being explicit about these, particularly when they are "undefined", is very important, as it makes clear that attention and intervention are needed to move towards a "valid" team type and interaction mode.
These unclear team boundaries and scope led to complex interactions and work dynamics, which hindered the ability to support a sustainable, fast flow of value creation.
For example, the Product team was based in Oslo, Norway, and, together with business stakeholders, would define all sorts of requirements and projects for the Engineering Teams based in Warsaw, Poland. The teams in Warsaw were building the necessary systems to support the company's products, but they were working in a rather organic way, with everyone implementing changes on the same systems, often a monolithic application with distinct capabilities. This was creating a "Big Ball of Mud" (BBoM) [BBoM-REF], i.e., many teams/people adding logic from different problems in the same entangled systems.
<br>
<div align="center">
  <a href="/assets/ck-emobility-tt-phase4-challenge-bbom.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-tt-phase4-challenge-bbom.png" alt="Big Ball of Mud" width="100%" /></a>
  <br>
  Figure - Big Ball of Mud
</div>
<br><br>

In parallel, there were other very relevant challenges with the new Platform (Platform 2), which looked very promising; however, it quickly began to pose several challenges for the company in scaling and building new offerings. This manifested in various ways, particularly because the platform's "core capabilities" did not meet eMobility's needs. Addressing those challenges and extending the platform with the necessary features was slow or nearly impossible. This led to a lot of "compensation work" built on the eMobility team's side, which posed several challenges for the company. That became even more evident when expanding into new regions.

<br>
<div align="center">
  <a href="/assets/ck-emobility-tt-phase4-challenge-outsourced-core.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-tt-phase4-challenge-outsourced-core.png" alt="Challenges of outsourcing core capabilities" width="100%" /></a>
  <br>
  Figure - Challenges of outsourcing core capabilities
</div>
<br><br>

> **💡 Outsourcing core capabilities/domains will hinder the ability to move fast and build the organization's differentiating capabilities.** "Own the core domains" is a key strategic pattern from Domain-Driven Design (DDD). Companies that outsource their "core domains", or highly differentiating capabilities, tend to have difficulty moving fast, since these often change frequently and require unique in-house knowledge, development, and continuous experimentation. It is essential that companies own those core domains and capabilities and can evolve them as they see fit. This is a fundamental consideration for build-vs-buy strategies. This is not to say that there may be related capabilities that we can still outsource or buy off the shelf. Still, the capabilities that are core and that we know will change often, or that require very specific domain knowledge, should NOT be outsourced to external partners.

The combination of rapid growth and market demand and an increasingly unsuitable architecture of systems and teams (the "Sociotechnical Architecture") was leading to a "Burning Platform"[REF] situation. The organization and its systems were unfit to cope with the exponential growth around them.

<br>
<div align="center">
  <a href="/assets/ck-emobility-tt-phase4-challenge-bbom-burning-platform.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-tt-phase4-challenge-bbom-burning-platform.png" alt="Becoming a burning platform" width="100%" /></a>
  <br>
  Figure - Becoming a burning platform
</div>
<br><br>

Even though these signals were challenging, they were very clear, and the eMobility leadership listened and took action, marking a pivotal moment for the organization. Amid rapid change and market demands, they took a step back, decided to "slow down," and fix fundamental aspects of their approach and operating model. Given their growth and scaling needs, it became clear they needed to pivot towards a model in which they "own the core" capabilities of their business and adopt an operating model suited to meet customer and market demands. And that is what happened, triggering the next phase of the organization's evolution focused on "scaling up sustainably".

> 💡**Adapting to growth challenges is a natural consequence of success.** This is a good thing. Often, companies try to get it all right on the first try, but that is very difficult if not impossible. Some see growth challenges as mistakes; however, they are natural elements of a healthy and successful company. One of the most important principles, though, is to embrace a continuous process of learning, taking the "next best action" in context, and adapting over time. Still, it is important to avoid known anti-patterns, such as outsourcing your core capabilities to generic platforms, as discussed in previous paragraphs, or making decisions that make certain potentially good options very difficult or impossible in the future (often these are important architecture and business decisions). This is hard, but considering these important patterns and principles should help navigating these journeys of growth.
>
## Part 2: Scaling Up Sustainably (2022 - 2024)

Motivated by the major challenges shared in the previous section, and with the goal of achieving a more sustainable, fast flow of value creation, the eMobility leadership set a simple goal for this phase: "design for speed, scale and adaptability". This led to a series of objectives detailed in the following diagram.

<br>
<div align="center">
  <a href="/assets/ck-emobility-phase2-scaling-sustainably.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-phase2-scaling-sustainably.png" alt="Designing for speed, scale and adaptability" width="100%" /></a>
  <br>
  Figure - Designing for speed, scale and adaptability
</div>
<br><br>

To accomplish those objectives, the following activities were defined:

- **Clarify the domains and product capabilities within eMobility** to gain a clear understanding how best to build and evolve them.
- **Refactor the platform from a monolith to a microservices-based architecture** to address to address sociotechnical architecture scalability challenges and the distinct domains emerging within the organization.
- **Refine the sourcing strategy** for each capability within the organization's domains to ensure a suitable approach is taken.
- **Define an operating model** that supports the growth strategy and addresses the current blockers and gaps.
- **Improve the culture and work style** to foster the traits and behaviors that enable the organization to continue scaling and handle the rapid growth it needs.

To begin addressing the challenges and achieving these objectives, a group began working on these activities, calling the effort the "Platform Strategy".

### Platform Strategy: deeply understanding the challenges and landscape

The "Platform Strategy" aimed to develop a clear picture of the landscape, including existing capabilities, challenges, key developments, etc. This deep understanding should enable us to define better interventions and strategies for improvements.

In practice, this meant several working sessions with people from different teams in the eMobility organization, particularly those in the product and technology teams.

For example, Value Stream Mapping sessions were held to map the most important activities in eMobility. Using those activities, we identified a first list of candidate domain boundaries for the different capabilities in eMobility. To sanity-check whether these were reasonable starting points, we used the "Independent Service Heuristics (ISH)" [ISH-REF] from Team Topologies to assess if these candidate domains exhibited traits of being independent elements. The outcome was positive for most of them, giving the group confidence to further explore those candidates.

At this moment, the working group and eMobility leadership had a good enough understanding of the landscape and challenges to address. It was also clear that this would not be a simple undertaking and that considerable effort and time would be required to address the current challenges. They also realized that they lacked the internal skills and capabilities to effectively continue the activities and to go deeper into the necessary modernization journey. To address that, they decided to start a collaboration with two (sociotechnical) architecture modernization experts: Eduardo da Silva and Nick Tune.

> **💡 When the organization lacks the skills and capabilities to undertake complex modernization efforts, a strategic move is to leverage collaborations with external consultants and experts to help overcome and address those skill and capability gaps.** This is a very important move, as it helps address specific challenges more quickly and, when done well, enables the organization to learn and develop the skills and capabilities needed to become "self-sufficient" in approaching similar challenges in the future. However, for that to happen effectively, it is fundamental that this collaboration be defined as a partnership in which the external consultants help the organization learn and become self-sufficient in those areas, i.e., they act as "enabling agents" (as in Team Topologies' Enabling Teams). If that is not the case, the organization will create yet another dependency, which potentially creates new bottlenecks and constraints.

### Kickstarting Architecture Modernization

When Eduardo and Nick started working, they positioned themselves as an "Enabling Team" with the mission of positioning, kickstarting, and facilitating the complex modernization efforts started in the Platform Strategy initiative.

<br>
<div align="center">
  <a href="/assets/ck-emobility-eduardo-nick-enabling-team.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-eduardo-nick-enabling-team.png" alt="Eduaredo and Nick as an Enabling Team" width="100%" /></a>
  <br>
  Figure - Eduardo and Nick (Modernization Consultants) as an Enabling Team
</div>
<br><br>

With a clear mandate from eMobility leadership to support deep modernization efforts, Eduardo and Nick began several initiatives to become acquainted with the organization's challenges. The sense-making and understanding work done in the previous months provided a great starting point, but now it was time to get even deeper. However, now the question was: "In which domains and capabilities should the modernization efforts start?" There were about 12 candidate areas; however, after a few discussions with people from different functions and perspectives, it became evident that one area was, at the time, a "major blocker" for many of the strategic activities underway, including upcoming important business initiatives related to expansion into other countries. This area concerned platform capabilities to support charging activities. This was clearly a core domain for eMobility, but at the time most capabilities were handled in a suboptimal, cumbersome setup, with many capabilities managed by external platforms and a lot of "compensation logic" across several in-house systems. Given this, it became clear that focusing on this area and its "constraints" would help address several challenges.

> **Focus on starting somewhere, preferably the "big blockers" or "constraints". Understanding where problems are is important, but starting to move is even more important. Do not try to analyze everything until everything seems right; there is always more to analyze, and doing so will slow things down and undermine your ability to improve.** This does not mean we don't "zoom out" to create a "good enough" understanding of the whole organization and how things connect. Those exercises are very important. However, particularly when starting a broad modernization effort, it is essential that we make real progress in specific areas so we can better understand the challenges and help everyone engage with these important modernization developments. People need to be involved and see things moving to truly embrace complex change around them.

To gain that "good enough understanding" of the situation, Eduardo and Nick spent about two weeks conducting 15+ listening sessions with people from all functions and teams involved in the selected area. As the name suggests, these sessions were focused on "listening". Eduardo and Nick, as modernization consultants and facilitators, had opinions, but in these sessions they kept them to themselves and focused on listening to the concerns, ideas, and opinions (and feelings) of the people working to evolve this area. By doing these exercises, they could gain a deeper understanding of the challenges at hand and, with those insights, define effective follow-up activities to address them. These sessions are also important for bringing people together and helping them become aware of upcoming activities in which they will continue to be involved and be affected by different decisions.

The outcome of the listening sessions was a better understanding of several clusters of challenges and topics to explore. With that, Eduardo and Nick began shaping ideas for next steps to explore and address those challenges. However, to effectively kickstart those activities and ensure strong support not just for the next step but throughout the entire modernization efforts ahead, they established an "Architecture Modernization Enabling Team (AMET)" [REF-AMET]. The AMET is an enabling team focused on kickstarting and facilitating complex modernization efforts. The following diagram provides an overview of the introduction given to teams when we kicked off the eMobility AMET.

<br>
<div align="center">
  <a href="/assets/ck-emobility-amet.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-amet.png" alt="Architecture Modernization Enabling Team (AMET)" width="100%" /></a>
  <br>
  Figure - Architecture Modernization Enabling Team (AMET)
</div>
<br><br>

As you can observe from the diagram above, the AMET had a mix of people from different functions. There was the Product & Technology Director (sponsor and connector to the eMobility Management Team), we had Architects (with a lot of understanding of the business and technology contexts in eMobility), a Group Product Manager (who had been pivotal on helping kickstart product management in the organization) and a Software Development Manager (or Engineering Manager, highly involved in setting up the engineering teams and with a deep understanding of their situation and challenges).

This combination of people gave us a lot of knowledge and understanding of the situation, but, very importantly, also gave us a strong leadership position to drive and orchestrate key activities and decisions and to address any challenges related to modernization across all teams and topics in eMobility.

> 💡**Modernization Enabling Teams (and Taskforces) need the mandate and authority to drive the important decisions**. Unfortunately, the following is still a common pattern in many organizations: some good workshops take place, awareness of challenges and possible improvements increases, but no real change happens on the ground. This is why it is fundamental to empower the people who can facilitate the execution of modernization and give them the mandate to drive important changes. This does not mean they are the "dictators of the modernization"; they are still working with everyone affected by the challenges. Still, they should be able to help drive the necessary changes and support people who are blocked along the way, particularly when these occur across multiple teams and areas of the organization, where decision-making boundaries tend to be blurred. That is a rather common situation, and this team should help navigate those situations.

### First Domain Modernization Kickstarter Workshop

With the decision on the domain to kickstart the modernization efforts, the AMET started organizing the first in-person workshop, a "Kickstarter Workshop" [REF]. This is a workshop technique Eduardo & Nick developed to build a deep understanding of the domains to be modernized and to kickstart modernization efforts with high involvement from people with knowledge of those domains, including those building the actual solutions to those domain problems. In this case, this was a group of about 30 people from business, product, engineering, and other important areas, such as network operations (very important for EV Charging).

<br>
<div align="center">
  <a href="/assets/ck-emobility-first-kickstarter-workshop.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-first-kickstarter-workshop.png" alt="First domain modernization kickstawrter workshop" width="100%" /></a>
  <br>
  Figure - First domain modernization kickstarter workshop
</div>
<br><br>

The workshop has several activities, but the core activity focuses on using Event Storming (and other collaborative modeling techniques) to map out the domain, discuss its key journeys, and begin aligning on the different "subdomains" within it. This mapping is done with the whole group and, at times, seems chaotic, particularly as groups map their first flows and important journeys in parallel on a big, empty wall, using Post-its of different colors.

However, after that first "chaotic exploration", Eduardo & Nick brought everyone in front of the wall and started walking through all of the things mapped. This walkthrough of the timeline (wording from Event Storming) helps bring everyone on the same page and to a shared understanding, including necessary discussions and clarifications when things are unclear. This effort can take several hours; in this case, it took more than a day. However, this is worth it, as at this stage there is a good map of the domain, including where the challenges are and some initial ideas for possible improvements and interventions.

<br>
<div align="center">
  <a href="/assets/ck-emobility-first-domain-mapped.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-first-domain-mapped.png" alt="First domain mapped" width="100%" /></a>
  <br>
  Figure - First domain mapped
</div>
<br><br>

Furthermore, this workshop was not just a mapping exercise. It was also a means to bring all the people involved in this area of the organization together, raise awareness of the modernization efforts about to begin, and, in a sense, make clear they were very much in the driver's seat to make them happen. This was challenging for many people, as it was the first time these topics had been discussed in such depth, and by the end of the day, it was clear that quite a few changes were needed. That makes most people feel uncomfortable, as it means that things will be changing around them. However, in this group, there was also considerable excitement, as they faced significant challenges in building and maintaining their systems, and even greater ones in creating the necessary innovations. So, knowing that improvements were coming and that there would be space and support to build things right made most people rather receptive to the changes ahead.

> **💡Involve the people with their hands on the problems from the beginning.** This will not only help you maximize learning and understanding of the problems at hand, but also ensure that the people who will actually be driving the changes "on the ground" are engaged and moving in the same direction. Ideally, they are the ones driving all of these activities. Still, when starting something, they often need a helping hand to get it kickstarted.

### Overview of Domain Modernization Process & Tools

After that first domain, we applied a similar process to other domains. Below is a "one-pager" describing the three-step process we refined to gradually modernize each domain.

<br>
<div align="center">
  <a href="/assets/ck-emobility-modernization-process-tools.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-modernization-process-tools.png" alt="Modernization process and tools" width="100%" /></a>
  <br>
  Figure - Modernization process and tools
</div>
<br><br>

We always started by gaining a deeper understanding of the domain, its capabilities, important challenges, etc. We did that through interviews with different people. Then we would do Event Storming or Value Stream Mapping, typically in person, to map all essential capabilities in the domain and discuss the challenges and opportunities with domain experts and teams working within it.

After that, we typically focused on further "validating the domains", which basically meant exploring further the outcomes of the workshops. In particular, we sought to understand and validate the nature of the capabilities identified, using, for example, Wardley Mapping [REF] or Core Domain Charts [REF], so we could shape our sourcing and approaches to build and evolve those capabilities. This was very important, since many supporting capabilities could be provided by partners without negative implications. However, as discussed in previous sections, a key strategic move here was "owning the core", i.e., we wanted to avoid again outsourcing "core domains" or becoming heavily reliant on external platforms that would not allow us to address our specific challenges and needs.

The last phase of the process, typically the longest, was about establishing or refining the actual domain(s) in question. In practice, this meant ensuring that the identified and validated domains were owned by empowered product teams, who would then own and evolve the capabilities within those domains. It is important to recognize that this process took time and often required refactoring, since those capabilities were previously mixed into the same systems or provided by external platforms. To ensure this longer-term work progressed gradually, the AMET maintained a modernization roadmap and overview that mapped all domains and capabilities and their modernization status. This was a great artifact for guiding and supporting the important discussions that needed to happen.

> **Pattern: The central (Architecture) Modernization Enabling Team (AMET) facilitates the organization's overall modernization, and dedicated Taskforces focus on specific domains' modernization.** In all of these phases, and as we began working with different domains, it became clear that the original AMET could not deep-dive into the detailed activities involved in validating and establishing each domain. These are complex and require significant time and a deep understanding of the domains. To address that, we introduced the idea of "Modernization Taskforces", which, in essence, can be seen as more localized AMETs with the purpose of driving specific domain modernization activities. They would still have support from the central AMET on various topics; for example, Eduardo would help facilitate the Kickstarter Workshops or the first Wardley Mapping sessions. However, the Domain Modernization Taskforce would continue to drive the specific activities within their domain. This proved to be a very effective pattern, having a clear driver for the whole modernization on the central Modernization Enabling Team, and then having more localized and focused Domain Modernization Taskforces to make sure that the execution of the modernization is happening with the right level of knowledge, expertize and capacity in each of the domains.
>
### Pivotal Workshop: Customer Experiences

Even though the initial efforts were focused on specific domains to kickstart learning and modernization, it soon became clear that we needed a more holistic understanding of the landscape and clearer alignment to accelerate modernization. To accomplish that, we organized a workshop.

This was a rather big workshop, and again we did some good pre-workshop preparations. We had more than 30 people in a large room for three days and took our time to create a detailed overview of all the experiences. From that ("outside-in" view), we anchored all the important domains of eMobility.

<br>
<div align="center">
  <a href="/assets/ck-emobility-all-cx-workshop.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-all-cx-workshop.png" alt="All customer experiences workshop" width="100%" /></a>
  <br>
  Figure - All customer experiences workshop
</div>
<br><br>

Furthermore, another key goal of this workshop was to understand the key groupings of domains in eMobility. At this phase of modernization, it became clear that we needed to understand how to decentralize product development activities, given the different concerns, the products being created, and the users leveraging them. By examining these natural boundaries, we were able to determine how to align the teams and domains to work more effectively. As an outcome of this workshop, we identified two main customer-facing "Product Groups" (one aligned with B2C customers and another with B2B customers) and an internal-facing platform (which would implement all the core capabilities used to build the eMobility products for B2C and B2B customers).

<br>
<div align="center">
  <a href="/assets/ck-emobility-all-cx-workshop-outcome.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-all-cx-workshop-outcome.png" alt="Outcome of the all customer experiences workshop" width="100%" /></a>
  <br>
  Figure - Outcome of the all customer experiences workshop
</div>
<br>

### Sustainable Domains Reorganization and Positive Outcomes

The customer experiences workshop and follow-up activities helped accelerate several important modernization steps, evolving the eMobility team topology toward the model shown in the following diagram.

<br>
<div align="center">
  <a href="/assets/ck-emobility-tt-phase5.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-tt-phase5.png" alt="Domains reorganization towards clearer product groups" width="100%" /></a>
  <br>
  Figure - Domains reorganization towards clearer product groups
</div>
<br><br>

As you can see, the main change here is to move towards a model in which teams own and evolve specific domain capabilities, and with that start addressing the challenges of the "Big Ball of Mud" (BBoM) and several other elements that were increasingly slowing down the ability of eMobility to continue scaling and expanding. Still, as you can see in the diagram above, the systems were still crossing teams and product groups. Understanding the natural domain boundaries is not the same as transforming and "refactoring" your systems and teams to align with them. However, taking this step, aligning the leadership of those product groups, and prioritizing the necessary modernization work (which included important cross-product collaboration efforts) were essential to see this evolution through. Effectively, the modernization (and refactoring) work took 2+ years, during which teams gradually evolved the landscape while delivering business value at an ever-increasing pace.

This is hard work and requires "rewiring" the organization's operating model. However, as the following diagram shows, the investment pays off, and we saw significant improvements for Circle K eMobility. For example, there was greater ability to achieve goals due to fewer dependencies, a significant improvement in development speed, and higher-quality work. Overall, this was a big step forward in addressing the blockers highlighted in the previous sections and created a solid foundation to continue scaling and expanding eMobility products into more countries and to support new products.

<br>
<div align="center">
  <a href="/assets/ck-emobility-modernization-improvements-outcomes.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-modernization-improvements-outcomes.png" alt="Modernization improvements outcomes" width="100%" /></a>
  <br>
  Figure - Modernization improvements outcomes
</div>
<br>

## Part 3: Towards Cross-functional Value Streams (2024 - Now)

The improvements and modernization described in the previous sections helped make big steps forward, towards a more sustainable flow of value creation. It helped establish clearer boundaries of understanding across all product and platform domains within the organization and ensured that teams and the organization were properly set up to own and evolve them sustainably. This phase of modernization mostly involved people from "Product and Technology", who are responsible for understanding, prioritizing, building, and evolving the different capabilities and systems in those domains.

This is a strategic move [REF-PRODTECH] that many organizations are increasingly investing in, as it helps address the most common blockers to the fast flow of value creation: having the people who understand, prioritize, build, and evolve the domain and platform capabilities not working together (being the traditional "product" and "technology" silos). Addressing this constraint is crucial to maximizing the ability to learn, design, and decide, and, in turn, to maximizing value creation.

<br>
<div align="center">
  <a href="/assets/prod-tech-silos.png" target="_blank" rel="noopener noreferrer"><img src="/assets/prod-tech-silos.png" alt="The Product and Technology silo" width="100%" /></a>
  <br>
  Figure - The product and technology silo (classic organizational constraint)
</div>
<br>

### Breaking silos beyond Product & Technology

The Product and Technology silo is often the biggest constraint to address and, as such, should be the first focus for most organizations' modernization efforts. However, once that constraint is addressed, there are often still many other aspects organizations can explore to further improve their value-creation effectiveness. This is exactly what we did at Circle K eMobility. Once we improved the product and technology structures and dynamics, we began exploring several other challenges that affect our ability to build and deliver value.

We can understand where those constraints are by exploring the end-to-end value-creation journey. In our case, it was clear that several functions and teams outside Product and Technology played crucial roles in those activities. Those "supporting functions" were crucial; still, they were working very differently and were disconnected from the newly created Product Groups and their teams. The outcome was that activities across these teams and groups were ineffective and inefficient. This was clear in the conversations with people from those different groups and teams: there was quite some frustration on "both sides" due to too many surprises and incidents in their activities. In essence, the interactions and ways of working among the Product and Technology "Product Groups" and the supporting functions were unclear and undefined, as were their boundaries, as shown in the following diagram. So, as the next step of the modernization journey, we focused on exploring how we could improve those boundaries and dynamics.

<br>
<div align="center">
  <a href="/assets/ck-emobility-breaking-silos-outside-prodtech.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-breaking-silos-outside-prodtech.png" alt="Addressing the undefined interactions with supporting functions outside product and technology" width="100%" /></a>
  <br>
  Figure - Addressing the undefined interactions with supporting functions outside product and technology
</div>
<br><br>

 > 💡 **Pattern: Keep on addressing the "biggest constraint" and the "undefined interactions" to achieve more sustainable creation of value.** Modernization work is not a project; it should be a continuous effort of addressing the most impactful constraints. That is the most effective way to continuously improve our (sociotechnical) system, as we know from the Theory of Constraints [REF]. Another important clue for areas for improvement is "undefined interactions" between different teams or groups within the organization (or interactions that occur in a very organic and effective way, without a clear goal or purpose). This type of signal is often a strong indicator of areas for improvement, as seen in the example described above between the newly formed Product Groups and supporting functions in eMobility. Addressing these constraints should help maximize the organization's ability to create value in more sustainable ways.

To facilitate these cross-functional and department improvements, we again leveraged the "Modernization Enabling Team" (or Modernization Taskforce) pattern [REF-AMET]. This became the "New eMobility Operating Model Taskforce" because, from all the discussions we had, it became clear that the challenge we were about to address would require a profound change to the eMobility Operating Model, its structure, dynamics, and ways of working. The taskforce included people from all the different supporting functions and the Product Groups, so we could gain a good understanding of the challenges and support the necessary improvements. This taskforce also had explicit support and a mandate from the eMobility management team, since the changes would affect all teams and functions across the organization.

> **💡 Maximize the ability to change by involving the people affected and those who can facilitate effective improvements**. As you have probably noticed, in the various modernization activities at Circle K eMobility over the years, we have always involved the people affected by the challenges we aim to address. That is essential for understanding the environment and needed changes, and for deciding what needs to be done. However, that alone may not be sufficient. It is also fundamental to create the necessary conditions for those changes to happen. In some organizations and situations, that can happen without the involvement of other people. Still, often, particularly when changes are larger or affect multiple teams, it is important to have explicit support from the organization's leadership. This is why, in the "Modernization Enabling Team" pattern, we make it explicit that the people facilitating the change should not only have the skills but also the support and mandate from leadership to execute the necessary improvements.

We started this initiative by conducting several Value Stream Mapping sessions to understand how the different teams worked together and delivered value and to identify the major challenges and constraints. Those were eye-opening sessions that corroborated the existence of significant waste stemming from poor communication and alignment, as well as unclear boundaries among the different "function groups" (Product, Sales & Marketing, Network Operations, etc.). For example, due to rapidly changing priorities, new products (or features) were often developed without the explicit involvement of Sales and Marketing or Network Operations, both of which were essential to their launch. Still, when people from supporting functions were needed, they often lacked the capacity to do that work, causing considerable delays in the product launch. These and other stories were crucial to bringing everyone (from teams to the leadership of those functions) on board and acknowledging that we needed to do something to address the "blockers" to effective value creation.

### Cross-functional Value Streams Operating Model

Once we identified the major blockers, the undefined interactions and boundaries between the supporting functions and the Product Groups, we began exploring options to address them. We had a few options, such as improving processes and communication to improve the "temporary collaborations", as defined in Team Topologies. We also explored introducing more planning ceremonies and activities at the start of important new product development initiatives to bring everyone on the same page and ensure supporting functions would prepare and reserve time to do the work they needed to support upcoming initiatives.

All those "ceremonies and processes" would for sure help address some of the surprises and challenges we noticed. However, the market and environment in which eMobility operates remain highly dynamic, and plans and developments often shift, requiring more alignment and replanning. The outcome would be coordination overhead and a lot of time taken away from actual work. Furthermore, this solution did not seem to fit the evolution eMobility was undergoing towards decentralizing its product development, with different groups, each with the right people and functions, needed to solve problems across the different product groups within eMobility.

Given this context, we started exploring options to structurally break down the functional silos between Product Groups and Supporting Functions, and to move towards having all necessary functions across the organization's essential value streams work together continuously, rather than relying solely on "coordination processes". The following diagram depicts this change and the actual approach we defined to consolidate that idea in the New eMobility Operating Model.

<br>
<div align="center">
  <a href="/assets/ck-emobility-new-operating-model.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-new-operating-model.png" alt="Cross-functional Value Streams Operating Model" width="100%" /></a>
  <br>
  Figure - Cross-functional Value Streams Operating Model
</div>
<br><br>

As you may have noticed in the diagram, we started using the term "Value Stream" to describe these new groups of functions that needed to work together. By definition, a Value Stream is "the entire set of actions and processes required to design, produce, and deliver a product or service to a customer", and this expressed well what we were trying to address with this structural and operating model change. In essence, we took the existing "Product Groups", where "Product" and "Technology" functions worked on the core products, and incorporated any other essential people and functions needed to own and address the full set of activities required to design, produce, and deliver value to customers. Those became the cross-functional value streams of eMobility.

> **💡 Look beyond process improvements; oftentimes the issue is more structural and adding more processes will only address part of the problem at a high cost/waste.** The "adding process", or "ceremonies", can become an anti-pattern if the underlying challenges are more structural and require changing boundaries of teams or systems, or rearranging those systems to address the actual constraints - as we saw in the case of integrating people from relevant supporting functions into the different value streams of the organization.

In practice, this structural evolution was simplified by the fact that we already had the "Product Groups". Nevertheless, this still required considerable effort to bring people on board and address their concerns. A topic that required extensive clarification was the implications and changes to how supporting functions would operate, budget their work, and stay connected with people within their functions when they were integrated into the value streams. All of these things were discussed extensively (in several workshops and town hall sessions with everyone) and documented so that everyone could express their concerns and have a clear reference for how eMobility wanted to work within this model.

The following Team Topologies diagram illustrates how eMobility teams, value streams, and supporting functions were positioned and worked after these changes.

<br>
<div align="center">
  <a href="/assets/ck-emobility-new-operating-model-tt.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-new-operating-model-tt.png" alt="Team Topology after moving towards cross-functional value streams operating model" width="100%" /></a>
  <br>
  Figure - Team Topology after moving towards cross-functional value streams operating model
</div>
<br><br>

You can see the "Value Streams", with people from the supporting functions incorporated into them, typically working across all of the teams of the value stream, and being part of the value stream leadership group.

It is also important to highlight that the supporting functions teams continue to exist outside of the value streams. This is very important, since there is still a need for people working on topics and areas that fall outside specific value streams. However, we explicitly position them as platforms that own capabilities supporting all essential activities across value streams, so their efforts remain driven by the needs of multiple value streams to create value more effectively. For example, generic Sales & Marketing materials that any value stream can leverage, or Network Operations intelligence and insights relevant to all value streams.

Another point worth mentioning is the explicit leveraging of "Collaboration" between supporting functions and value streams to address needs that cannot be self-serviced from the supporting platforms. For example, a big "Go To Market" campaign that requires extra support or capabilities from Sales & Marketing for a specific value stream. Those are "temporary collaborations" (yes, temporary, as per the definition of Team Topologies Collaboration interaction mode), and the goal is to make sure that there is a group of people to address a specific gap/need, where those people understand what they need to do in their team, and then can proceed working in their team without blocking each other.

These, and many other principles, were discussed and documented in the eMobility Operating Model principles, forming the basic language to enable clearer and more effective ways of working.

This wasn't an easy change, but the impact and improvements became visible within a few months, as you can see in the following testimonies from people leading some of the supporting functions.

<br>
<div align="center">
  <a href="/assets/ck-emobility-testimony-elin.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-testimony-elin.png" alt="Testimony Elin Boe - Cross-functional value streams operating model" width="100%" /></a>
  <br>
  Figure - Testimony Elin Boe - Cross-functional value streams operating model
</div>
<br>
<div align="center">
  <a href="/assets/ck-emobility-testimony-maria.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-testimony-maria.png" alt="Testimony Maria Estenstad Friis - Cross-functional value streams operating model" width="100%" /></a>
  <br>
  Figure - Testimony Maria Estenstad Friis - Cross-functional value streams operating model
</div>
<br><br>

## Closing Remarks

In this article, we provide a deep dive into the evolution of Circle K's eMobility organization, from a small startup in Norway in 2018 to a scale-up operating across Europe and expanding globally.

<br>
<div align="center">
  <a href="/assets/ck-emobility-continuous-modernization.png" target="_blank" rel="noopener noreferrer"><img src="/assets/ck-emobility-continuous-modernization.png" alt="Journey of continuous modernization and improvement based on the environment needs" width="100%" /></a>
  <br>
  Figure - Journey of continuous modernization and improvement based on the environment needs
</div>
<br><br>

As we can see in the diagram above, the organization has changed a lot over time, as a function of its growth and scaling needs, and changes will continue happening; there is no "target state", simply a suitable model to support current needs, and listen to the signals to evolve accordingly. That shows how important it is to continuously listen to signals indicating blockers to value creation and act on them. Those signals and improvement interventions are different in the different phases of the organization's journey - for example, the challenges and improvement interventions are very different in the startup and scaleup phases.

These journeys are also unique to each organization's context, so one can't simply copy and paste them into another context. One needs to embrace the specific context and take the time to understand and act on it. Still, we believe many of the patterns and principles shared in this article can be useful to many. In particular, going beyond the simple "add yet another process" to truly explore what structural changes need to happen and how those can be enabled without big reorgs. For example, allowing teams to "reteam" to work more effectively on a new product; breaking silos; allowing temporary collaborations and enabling work between different teams to address specific needs, among others.

Enabling continuous modernization and improvement [REF-Enabling-Continuous-modernization-training] to address current constraints helps organizations grow and scale more sustainably and, in turn, become better able to respond to their environmental needs (customer, market, technology, etc.).

These improvements don't happen overnight. It takes time, effort, and perseverance not to take the easy path, but to fix the fundamental issues beneath the challenges. This requires a leadership team that has the courage to create space for important improvement and modernization activities to take place, and to help their teams and leaders embrace the same mindset and approach. When leaders show that and create that space, everyone eventually feels comfortable and safe to "go for it". Failing to create those conditions but asking teams to somehow do magic will not work. So, leaders cannot fake it; they must support the journey and ensure they enable people along the way, effectively becoming "Enabling Leaders" [REF-Becoming-Enabling-Leaders-Training].

Nevertheless, the impact of these changes will not only enable better business results, often even in the short term, but it will also create the conditions for more (cost) effective and localized improvements to happen, as opposed to doing expensive "big reorgs" every few years (because there are too many things that need to be changed at once). This continuous modernization capability is increasingly important for organizations to stay relevant and grow, and as AI becomes a major enabler of accelerated growth, these conditions will be even more crucial.
