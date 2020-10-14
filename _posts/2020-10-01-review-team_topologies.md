---
layout: post
title:  "Review & Reflect: Team Topologies"
---

`TL,DR: Review & Reflections on the book “Team Topologies”, by Matthew Skelton and Manuel Pais. A "must read" for anyone involved into organization and software architecture activities. As products grow in complexity these two systems (organization and technical systems) also become more complex. Traditionally we have Software Architects and Engineers with a huge focus on the Technical Architecture of the software products and mandate to work on it. However, organizational systems are seen as second class citizens and are architected organically, and many times by people without a clear understanding of their implication on the technical architecture (a.k.a. Conway's Law). In order to be successful and achieve "high velocity", organization and technical architecture must align and be co-designed. This book provides strong motivation for that co-design and introduces a clear and extremely actionable language to act on it. I highly recommend this book. To me, it is becoming a reference book to help on the design and evolution of organizations and their sociotechnical architecture! #SociotechnicalArchitecture #OrgDesign #OrgEvolution`

<div align="center"><img src="/assets/team-topologies-book.png" alt="Team Topologies" width="250"/><br>
(<a href="https://teamtopologies.com" target="_blank">Link to book</a>)</div><br>

## Review & Reflect

During my career I had the opportunity to work as Software Engineer, Architect and Technical Leader in different types of companies, from startups (1-2 teams) to midsize companies (~10-20 teams) to rather large companies (100+ teams) (teams ~5-8 people). This gave me the opportunity to see how different teams work and build their products in such different contexts. In startups: *everyone works on everything*, you have no clear idea yet what is coming tomorrow and you just want to get things done. This also means that you really don't (read can't) care so much about long-term architecture vision, given that most of the time your don't know yet where you are ending up... so, spending time on that is a waste of time and money (two things startups don't have in general). However, as you grow, learn, validate your product and it becomes established, you start having more clarity. At this pivotal moment you need to start being more strategic about your "architecture". This "architecture" here is seen by most people as the "technical architecture", i.e.: the software systems we are building and how they can support achieving our business goals at *high velocity*.

This sounds good... however, when companies are in this phase (so scale-ups and most mid-large companies) they will grow in size and complexity. This happens because they need to bring more people in, build new teams to own different parts of the product, etc. This is where I see a lot of struggle in our industry! When the complexity of a product grows, we struggle to build teams that can keep that "startup-like" high-velocity of iteration to grow/improve the product. Why is this happening? My experiences and observations tell me that this happens due to a lack of suitable sociotechnical strategy when designing organization and technical architectures, i.e.: these two systems are not explicitly and comprehensively co-designed to keep those "startup traits" we find so appealing (e.g.: *autonomous teams that can clearly own their product and iterate on it at high velocity to improve value exchange with the customer*).

As an industry we overly focus on the technical architecture design and neglect (or downplay) the design of our organizations and teams. However, if we want to maximize our overall impact - i.e.: quickly iterate on delivering improvements to maximize the customer exchange value, we need to have a more holistic approach on how we set up our organization and technical architecture (a.k.a: [Sociotechnical Architecture](https://esilva.net/sociotechnical)). The figure below depicts the different systems at play in Sociotechnical Architecture. Team Topologies book focuses on addressing several challenges in this context.

<div align="center"><img src="/assets/sociotechnical-evolution-loop.png" alt="Team Topologies" width="650"/></div><br>

This book is a breath of fresh air in this topic, and it I consider it will help to "mainstream" and simplify several aspects needed to approach sociotechnical architecture design. The main reason for that is: <ins>it provides a simple and crisp language/lexicon to approach the design of teams, their interactions and the technical systems they build to deliver value to customers.<ins>

The book is divided into 3 main parts:

- 1: Motivating and understanding why we can't ignore organization design when building our software products (Conway's Law). Here they propose a team-first approach, which puts teams as the central element in the design space. It brings several key elements to make sure teams are properly set up to build/own their software. For example: Team Cognitive Load (as the measure of how much capacity teams spend on their different activities, and how much capacity left they have to own new things); Team size (Dunbar's number); team scope and interfaces, etc.
- 2: Provides an overview of patterns for static team topologies. Showing that different organizations with different conditions will need different arrangements of teams. Then it introduces the four fundamental team topologies: Stream Aligned Team; Enabling Teams, Complicated Subsystem Teams and Platform Teams. The main goal is to have Stream Aligned Teams working efficiently and at high-velocity delivering value to customers. All the other topologies exist to support and enable Stream Aligned Teams to maximize their mission. Also presents several insights on how to set teams up and define their boundaries.
- 3: Covers design elements to deal with change and enable a more dynamic evolution of the organization and team interactions. This provides the final piece for proper org design, which is: organizations are continuously evolving, and as such teams and interactions between teams will also change. To cope with this "continuous change", the book proposes three basic team interaction modes: Collaboration, Facilitating and X-as-a-Service. These three modes have particular characteristics and with that we can address the continuous changes needed to sustain the teams velocity. In order to get all of this to work they also present key strategies to "sense" when change is needed and how to go about it.

The main elements presented in the book are:

- Team Topologies
  - **Stream Aligned Teams (SATs)**: the teams building a part of the product that supports a certain value stream to the customer. These are the teams that build the product value for customers.
  - **Enabling Teams**: facilitate SATs on overcoming obstacles and in that way enable them to do better. Also detects missing capabilities.
  - **Complicated Subsystem Teams**: are teams that own complex parts of the landscape, which by being abstracted into such sub-systems that serve SATs enable their applications to be simpler and as such reduce their cognitive load (and in general increase their velocity).
  - **Platform Teams**: focus on building "internal products" that accelerate and simplify how SATs build their own applications (and products). This is done by taking away complexity of SATs, which enables them to have more cognitive load available to work on the business problems.

<div align="center"><img src="/assets/team-topologies-team-types.png" alt="Team Topologies" width="650"/></div><br>

- Team Interaction Modes
  - **Collaboration**: interaction mode where two (or more) teams collaborate for a defined period of time to learn and discover how to proceed on their developments (e.g.: identify boundaries of a legacy system and with that each team can own a clear boundary).
  - **Facilitating**: one team helps and mentors another team.
  - **X-as-a-Service**: one team provides another with something "as a service" (e.g.: an API with a clear contract that the other team can consume without the need of continuous collaboration).

<div align="center">
<img src="/assets/team-topologies-interaction-modes.png" alt="Team Topologies Interactions" width="650"/><br>
<sub>(Image Credits: Team Topologies, Matthew Skelton and Manuel Pais.)</sub></div>

## Conclusion

Team Topologies is one of the most relevant books I have read in recent years. In my opinion it will become a classic and foundational book to help our industry to move from the narrow obsession into the "technical systems" and consolidate proper sociotechnical approaches to architect our systems (organization and teams that own and build the technical systems). This is essential to maximize our impact. Neglecting this is a recipe for problems (i.e.: teams are not set adequately to own/build the technical systems that are provide the business impact intended).

> Note: I have published some further "raw notes" on the book in this [Twitter thread](https://twitter.com/emgsilva/status/1310943371817635840).
