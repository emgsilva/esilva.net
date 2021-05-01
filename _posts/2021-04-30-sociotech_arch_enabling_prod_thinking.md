---
layout: post
title:  "Sociotechnical Architecture as Enabler of Product Thinking"
categories: [product-thinking, sociotechnical-architecture]
---

`TL;DR: This article provides an overview on several ideas I have been exploring on how Sociotechnical Architecture and Systems Thinking are key to enabling achieving the goals of Product thinking: "maximize the value exchange with the customer, continuously and at high-velocity". The core elements of the article were initially presented on my DDD_EU 2021 talk [DDD_EU-Silva], but this article explores them forward. In this article I do not go into “how to implement these ideas”, “who should do this”, etc. Those aspects are explored in other articles and material, which you will be able to find on my Sociotechnical Architecture & Systems page [Sociotech-Arch-Silva].`

## Product Thinking

Product thinking [<a href="#escaping-build-trap-perri">Escaping-Build-Trap-Perri</a>, <a href="#product-thinking-101-katakam">Product-Thinking-101-Katakam</a>] has been gaining traction as  a customer-centric approach to product development, i.e.: customer becomes the main driving force for product development. This is my one sentence summary of Product Thinking: *it is about customer-centric product discovery, delivery and evolution (while still taking into account the business goals).* Figure below depicts its main elements.

<div align="center"><img src="/assets/product-thinking.png" alt="Product Thinking" width="50%"/></div><br>

As it can be seen, the goal of Product Thinking is to build the product based on a "continuous learning loop" with the customer. This is the key differentiation from classical "sales-driven" and "tech-driven" product development models (which tend to prioritize other elements, not the real problems of the customer, and consequently becoming not be able to maximize the value exchange with the customer). Melissa Perri [<a href="#escaping-build-trap-perri">Escaping-Build-Trap-Perri</a>] summarizes Product Thinking priorities rather well in the following remark: "our highest priority is to satisfy the customer through early and continuous delivery of valuable software". "Valuable" software can mean different things, but it is key that our efforts as organization must be tuned into "maximize the value exchange with customer", i.e.: we deliver and evolve the product to satisfy the customer problems (i.e.: build a product driven by the customer "problem space"), so that the customer is happy with it and consequently also happy to pay for the value the product brings.

<div align="center"><img src="/assets/product-thinking-goal.png" alt="Product Thinking Goal" width="80%"/></div><br>

With this mental model and goal, the next question we can ask ourselves is: "how can we achieve that", i.e.: maximize the value exchange with the customer? Furthermore, we can also question ourselves on how to do that continuously and at high-velocity? There are quite a few factors that contribute to that. One important remark is: we are talking about products, not projects. This is a key distinction, as a project is an iteration on development of something and in general has a clear end goal and scope. On the other hand products tend to continuously evolve and be improved based on the learnings and needs we discover with the customer.

In the following I go over a few system traits that need attention when addressing product development and evolution. I will use my "Restaurant Product" running example to showcase the different traits (you can find a more detailed intro to this example and traits in [this article](https://esilva.net/sociotechnical/sociotechnical-architecture_why-and-what.html) of [intro to sociotechnical architecture series](https://esilva.net/sociotechnical/intro-sociotechnical-arch)).

## (Some System) Traits for Great Tech-enabled Products

### Trait 1 - your teams and org shape your product

Whatever product we are building, we need to make sure the team (and its setup, organizational architecture and communication structures) is aligned with the ambitions we have for the product being designed (the actual "technical architecture" of the product). This is basically Conway's Law [<a href="#conways-law">Conways-Law</a>], i.e.: *"Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization's communication structure."*

**Restaurant example:** if we want to build a great French food and drinking experience restaurant, we need to have good French chefs and wine experts who are setup to work together on building a product that brings those parts together as a great experience to the customer.

### Trait 2 - your teams must have the right conditions to build the product for your customer

This basically means that your teams should have the right scope and capacity to build the product for the customer. So, when shaping the product to be built, we must explicitly consider the teams (and their topology and setup) in order to actually be able to make it to work. This is where the work of Team Topologies [<a href="#team-topologies">Team-Topologies</a>] - and their "team-first approach" can help a lot. Neglecting teams on the process of architecting the systems - and purely focus on the desired product (and its Technical Architecture) will (almost certainly) lead to surprises on the actual building, delivering and evolving of the product.

**Restaurant example:** in order to have a restaurant running smoothly and continuously creating the best customer experiences, we need to have enough people cooking, serving and doing all the different activities of the restaurant. We cannot expect Chefs to cook, serve the food and do the dishes at the same time.

### Trait 3 - Your product is a combination of value streams owned by different teams but aligned to maximize value exchange with customer

A product can be seen as a system with different parts that together (and with their interactions) define and deliver the value the customer seeks. We want those different value streams to come together in a harmonious way for our customer. We do not want local “siloed” optimizations done without the product (whole system) context and goals in consideration. Such approaches (almost) never lead to the goal we have: maximizing the overall value exchange with the customer. This holistic understanding approach is a core property of Systems Thinking [<a href="#systems-thinking-ackoff">System-Thinking-Ackoff</a>], which still tends to be very much ignored by many modern approaches to product development - which tend to focus on "reductionism" [<a href="#good-fences-hjorteland">Good-Fences-Hjorteland</a>] and breaking the system into independent parts developed in isolation.

**Restaurant example**: in our restaurant we don't want to simply serve the "best dish cooks can cook" combined with the "best wine we have". That combination of what is the possibly best in each part does not necessarily lead to the best end product for our customers. The best outcome results from a contextual combination of parts, which requires interaction and understanding while designing the experience (i.e.: let's cook this dish and combine it with that wine because these are great fresh ingredients and that wine is really good and their combination will be an amazing experience).

### Trait 4 - Your teams should be empowered to discover (with the customer) what are the best things to build in the product

A cornerstone of Product Thinking is the enablement of teams to listen, discover and understand the customer's problems, and be empowered to map that into product developments to solve/address those problems. In order to achieve this teams need to be on the driving seat of "discovery" activities with the customer. Failing to do that - and having teams owning and evolving the product far from the customer, by having "layers of other teams/people" between them and customers, will lead to poorer understanding of the customer. Furthermore, it will also lead to a much slower product development life cycle (and lead time to implement developments - which is a well known metric to measure high-performance, as described on Accelerate Metrics [<a href="#accelerate">Accelerate</a>]). Even when teams do discovery, it is also important to make sure that the whole team is enabled to do product discovery. This is not a job for just a few people (e.g.: UX). Teams are one of the main drivers of great product development ideas [<a href="#pm-research-alpha">PM-Research-Alpha</a>] , so making sure this happens is crucial.

**Restaurant example:** we want the people working on the kitchen to understand how customers are reacting to their dishes, so they can tweak and evolve them. For example, they may need to understand if the produce they use is working fine. If not, they may need to look for alternative sources. Cooks and kitchen staff will be the most equipped to reason on these discovery activities. Note: again, those discovery activities are done with a wider understanding, e.g.: how are we combining the dish with wines or how are we plating and serving the dish to customers.

## Not just "What", but also "Who" + "How" Systems... Holistically!

If we analyse the traits presented in the previous section, we start seeing that in order to achieve the goal of Product Thinking we cannot purely focus on the "What enables maximum value exchange" (the "What" system). We also must cater for other important interrelated systems, namely: "Who" is listening to the customer and building/evolving the product; and "How" is the product being built to deliver the value maximization the "What" defines. Figure below depicts a visualization of these three parts.

<div align="center"><img src="/assets/need-holistic-view.png" alt="Holistic View" width=80%/></div><br>

So, these (What, Who and How) are all relevant systems on the overall goal equation of Product Thinking. It is fundamental to embrace that they must be understood from an holistic perspective in order to define strategies to improve our overall system goal. For example: when we are about improving our Restaurant, we consider the offerings we have ("What" system), but also the crew we have and how they are organized ("Who" system) and how they build the dishes and different experiences for the customers ("How" system).

These ideas build on the core pillars of Systems Thinking [<a href="#systems-thinking-ackoff">System-Thinking-Ackoff</a>], which defines that in order to truly understand what a given system should do to improve, it must be contextualized and understood from the perspective of the system they are in. We don't want it to be evolved in isolation, that would mean local optimizations with no context of the involved system (i.e.: we don’t want to be cooking whatever dishes we think would make sense without understanding what is happening on the rest of the Restaurant and the experiences we want to optimize for our customers). Such local optimizations tend to lead to sub-optimal results, and in many cases even having different systems “arming” each others' improvements. Russel Ackoff has a great quote on this, namely: "...understanding proceeds from the whole to its parts, not from the parts to the whole as knowledge does".

Now the challenge is: how can we apply these ideas to build Tech-enabled products? In the next section I share some ideas on this.

## Sociotechnical Architecture - holistic positioning of What, Who and How systems

Building on the Systems Thinking perspective, the figure below depicts the mental model I am using to define the "involving system" to define an holistic approach to understand and evolve the systems at play when building tech-enabled products.

<div align="center"><img src="/assets/sociotechnical-evolution-loop.png" alt="Sociotechnical Architecture" width=100%/></div><br>

This model depicts the parts of this sociotechnical system and also their interactions. The goal is to allow for an holistic understanding and from there approach the design and evolution of the different parts with context. This activity is what I call "Sociotechnical Architecture" [<a href="#sociotech-arch-silva">Sociotech-Arch-Silva</a>]:

...*taking an holistic co-design approach to technical and organizational systems, given the inherent impact they have on each other.*

Important to note that technical and organizational systems tend to be driven by context of the market and customers the product is targeting.

There are many further considerations to take on this, which I elaborate in other articles [<a href="#sociotech-arch-silva">Sociotech-Arch-Silva</a>]. The bottom-line however is: by starting developments from a holistic understanding we have a solid evolution framework for approaching Product Thinking implementation and scaling in organizations. It makes explicit the different elements that need to be considered and also their relations.

It is key to understand that the system parts depicted encapsulate other systems inside and a similar approach for understanding and evolution can be applied to those systems (e.g.: product teams working on a specific value stream consolidate understanding from the holistic value stream perspective, not per team, which then provides clearer context for each team contributing to a particular value stream). Last but not the least: all of these (encapsulated systems) are interrelated.

**Important:** this framework of thinking does not mean we must have up-front design of all the different parts together and "compromise" the autonomy of execution of the different parts. It simply means that we must have feedback loops from all the parts coming together and enabling understanding from the holistic system perspective. That understanding and context provide well grounded data to drive decisions on product, organization and technical architecture design and evolution. To make sure this happens it is key that teams building the product have mechanisms to capture and act on those signals.

## What's next?

First things first: stop silo-based thinking. This is not trivial and may mean very different things per organization. In general the steps to take have to do with acknowledging that we need to enable teams to be properly set up and aligned with the product we want to build. For that you should start by assessing where you are and what next steps you need to take.

However, that is just the start: the ideas shared on the previous section target "continuous evolution" of systems, i.e.: don't see this as yet another transformation project with an end result. See Sociotechnical Architecture as an iterative evolution approach to keep your sociotechnical systems effective on building the product and delivering value to customers at high-velocity.

I am writing more on this, namely: how to approach this and who you may need to have in place to make sure that this system evolution is catered for (these articles will be published on my [Sociotechnical Architecture and Systems](https://esilva.net/sociotechnical) page - [follow me on twitter](https://twitter.com/emgsilva) to be notified of updates).

## References

- [DDD_EU-Silva] [Sociotechnical Architecture as Enabler of Product Thinking](https://esilva.net/talks/#sociotechnical-dddeu_2021), Talk on Domain-Driven Design Europe 2021, Eduardo da Silva<a name="ddd_eu-silva"></a>
- [Sociotech-Arch-Silva] [Sociotechnical Architecture](https://esilva.net/sociotechnical), Eduardo da Silva<a name="sociotech-arch-silva"></a>
- [Escaping-Build-Trap-Perri] [Escaping the Build Trap](https://www.oreilly.com/library/view/escaping-the-build/9781491973783/), Melissa Perri<a name="escaping-build-trap-perri"></a>
- [Product-Thinking-101-Katakam] [https://uxplanet.org/product-thinking-101-1d71a0784f60](https://uxplanet.org/product-thinking-101-1d71a0784f60), 2020, Naren Katakam <a name="product-thinking-101-katakam"></a>
- [Conways-Law] [http://www.melconway.com/Home/Conways_Law.html](http://www.melconway.com/Home/Conways_Law.html), Melvin Conway <a name="conways-law"></a>
- [Team-Topologies] [https://teamtopologies.com/](https://teamtopologies.com/), Matthew Skelton and Manuel Pais <a name="team-topologies"></a>
- [System-Thinking-Ackoff] [TLA_insights: On Systems Thinking, Russel Ackoff](https://esilva.net/tla_insights/on_systems_thinking-ackoff), Russel Ackoff <a name="systems-thinking-ackoff"></a>
- [Good-Fences-Hjorteland] [TLA_insights: Good Fences, Trond Hjorteland](https://esilva.net/tla_insights/good_fences_make_good_neighbours-hjorteland), Trond Hjorteland <a name="good-fences-hjorteland"></a>
- [Accelerate] [Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations](https://itrevolution.com/book/accelerate/), Nicole Forsgren, Jez Humble, Gene Kim <a name="accelerate"></a>
- [PM-Research-Alpha] [https://alphahq.com/blog/how-product-management-is-evolving-findings-from-the-2020-pm-insights-report/](https://alphahq.com/blog/how-product-management-is-evolving-findings-from-the-2020-pm-insights-report/), Alpha <a name="pm-research-alpha"></a>
