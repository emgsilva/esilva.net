---
layout: post
title: "Introduction to Sociotechnical Architecture: Why & What is it"
permalink: /sociotechnical/sociotechnical-architecture_why-and-what.html
---

`TL;DR: this article is the first of a series introducing Societechnical Architecture. In this series I cover why Sociotechnical Architecture is so relevant, what it is and how to start using it. On this first article I show why Sociotechnical Architecture approach (co-design organizational and technical systems) is fundamental to be able to maximize the impact of our products and the teams building & owning them. Furthermore, I will share a definition and typical interactions of the systems within Sociotechnical Architecture. On the following articles I will do a deep dive into several core traits of Sociotechnical Architecture and provide strategies to address them; I will also cover the typical phases of designing with a Sociotechnical approach in mind; finally I will share an overview on the state-of-the-art principles, methods and tools to comprehensively approach Sociotechnical Architecture. Along the way I will give concrete examples and stories to crystalize the different elements presented.`

> In [this series](intro-sociotechnical-arch) I will deliberately go in depth in order to provide a good overview and introduction to Social Architecture and give some directions on how to start doing it. If you are short in time, and want to get a quick gist and intro on many of the elements covered in the articles, you can take a look at the conference video and deck below. This material is still in "beta" (can/will be improved), so if you have comments, suggestions or would like to chat further about this just let me know.

<div style="left: 0; width: 100%; height: 0; position: relative; padding-bottom: 56.1972%;"><iframe src="https://www.youtube.com/embed/ekMPm78KFj0" style="border: 0; top: 0; left: 0; width: 100%; height: 100%; position: absolute;" allowfullscreen scrolling="no" allow="encrypted-media"></iframe></div>

<div style="left: 0; width: 100%; height: 0; position: relative; padding-bottom: 56.1972%;"><iframe src="https://speakerdeck.com/player/33c668f6bd7249a5b237e8d0f4621d2f" style="border: 0; top: 0; left: 0; width: 100%; height: 100%; position: absolute;" allowfullscreen scrolling="no" allow="encrypted-media"></iframe></div><br>

**Index:**

- [Introduction](#introduction)
- [Setting up a Restaurant for Success ⇦](#setting-up-a-restaurant-for-success-)
  - [Trait 1: your staff defines your cooking and experiences ⇦](#trait-1-your-staff-defines-your-cooking-and-experiences-)
  - [Trait 2: Chefs cannot cook, serve and do the dishes at the same time ⇦](#trait-2-chefs-cannot-cook-serve-and-do-the-dishes-at-the-same-time-)
  - [Trait 3: Restaurant value/experience is the sum of several streams of activities... it is not only the food in a plate ⇦](#trait-3-restaurant-valueexperience-is-the-sum-of-several-streams-of-activities-it-is-not-only-the-food-in-a-plate-)
  - [Trait 4: don't hand recipes to your chefs, empower them to discover new recipes! ⇦](#trait-4-dont-hand-recipes-to-your-chefs-empower-them-to-discover-new-recipes-)
  - [Trait 5: because #1 restaurant does something it does not mean it will work for you and your crew ⇦](#trait-5-because-1-restaurant-does-something-it-does-not-mean-it-will-work-for-you-and-your-crew-)
- [Definition: Sociotechnical Architecture ⇦](#definition-sociotechnical-architecture-)
- [The Sociotechnical Evolution (Loop) ⇦](#the-sociotechnical-evolution-loop-)
- [Summary](#summary)
- [References](#references)
- [Changelog](#changelog)

<a name="introduction"></a>
## Introduction

When designing and building software products we have a tendency to focus most of our attention on the "technical systems architecture" and pay little to no attention to the "organization system" (teams) building it. This tends to lead to all sorts of issues and waste. In this article I give an intro to Sociotechnical Architecture, and showcase how it is so relevant to address those issues and enable us to maximize our impact. The foundation of Sociotechnical Architecture is to have a co-design approach to architecture, where we don't just look at the technical systems architecture of the product, but also to the organization system (teams) building and owning it. Why? Because they have a lot of influence on each other and neglecting is not allowing for a proper design and developments.

To start showcasing this, I will talk about Restaurants...

<a name="restaurant-traits"></a>
## Setting up a Restaurant for Success <a href="#restaurant-traits">⇦</a>

Restaurants are very interesting sociotechnical systems. They have customers who come and pay for food and nice experiences - these elements form the "value" we provide as a restaurant to our customers, and this is what we (as Restaurant, and people working on it) want to optimize for (based on the customer feedback). For example: we want to make sure we get the maximum financial earnings, have happy customers who return to the restaurant. In order to achieve that we have quite a few elements to consider in our "design space", namely: the dishes we serve, the decoration and the wine, but also the crew we put together and what they can collectively do.

![Restaurant Overview](/assets/restaurant-overview.png)

In the following I will look into several traits to consider when setting up a restaurant for success*. (Disclaimer: by no means consider this as a recipe to open up your restaurant! 😄).

> \* <sub>Success can mean many different things. However, in order for us to design a system (such as a Restaurant, or a software product) there must be clarity and vision on "what is success" (especially from a business and product perspectives). This is a precondition to design. If this does not exist you cannot design, because you don't know where you want to go - what is your design space. This does not mean you may not start if you do not have a clear vision. Sometimes you don't know in advance how to fully design your system (especially on "complex" or "chaotic" problems domains - check [<a href="#cynefin">Cynefin</a>] for more info on this). However, you do need to be explicit on this and setup experiments to learn and sharpen your strategy and vision. Do not "blindly do it", you will most likely struggle (or simply fail).</sub>

<a name="trait1"></a>
### Trait 1: your staff defines your cooking and experiences <a href="#trait1">⇦</a>

Whatever mission you have and product you envision, make sure you bring together a team that can properly implement it. For example, if you want to open a restaurant that provides amazing French food and drink experiences, you need to get chefs and wine experts on those. They need to excel in their discipline, but they also need to be able collaborate and bring together their different parts, for example: make sure the dish and wine match perfectly and provide a great experience to the customer.

<a name="trait2"></a>
### Trait 2: Chefs cannot cook, serve and do the dishes at the same time <a href="#trait2">⇦</a>

To be able to have a restaurant that operates smoothly and for a long time you need to make sure you have enough people, capacity and skill. You don't want to continuously stretch your crew. They will not be able to do their best work if they have more work than what they can actually do. If this happens you will be sub-optimal and your people will most likely "burn out" and / or leave.

<a name="trait3"></a>
### Trait 3: Restaurant value/experience is the sum of several streams of activities... it is not only the food in a plate <a href="#trait3">⇦</a>

Your restaurant has different parts and "streams of value" that should operate as independent as possible (in order to maximize their outcomes), however they must align and come together in a coherent product to the customer. Our goal is to maximize the value exchange with the customer. For example, we want to have a good combination of dish, wine and the actual serving in order to make sure the customer is happy to pay for it, and furthermore increase the chances of coming back (maybe even recommend our restaurant to friends).

<a name="trait4"></a>
### Trait 4: don't hand recipes to your chefs, empower them to discover new recipes! <a href="#trait4">⇦</a>

Do you want to provide unique experiences to your customer, so that we you can maximize your value exchange, by for example, regularly having them coming back? Then you better allow your crew (experts on their crafts) to do their best job, experiment and continuously discover how to improve your restaurant (product).

<a name="trait5"></a>
### Trait 5: because #1 restaurant does something it does not mean it will work for you and your crew <a href="#trait5">⇦</a>

Just because the #1 restaurant in the world was successful with a given model, do not blindly copy it. Your restaurant will have a specific context, mission and constraints around it. Break those down to understand your real design space. Then build your solution from there. This does not mean you should get inspiration and learn from others. However, don't blindly apply them on your restaurant.

![Traits of Successful Restaurant](/assets/traits-successful-restaurant.png)

When we look into all these traits, which address "core design decisions", we see that many of them focus on "social" (people) and "organizational" aspects. There is not much on "how the restaurant should be painted and which dishes to serve". This also shows a focus on having an holistic design approach looking at many different aspects. The goal is to set up a robust/enabling "system of systems" in the restaurant, where people are empowered to drive the best product development from their "stream of value" to the end product.

This holistic design strategy is foundational of "Sociotechnical systems" [<a href="#sociotechnical-systems">Sociotechnical-Systems</a>], and in the context of building software products "Sociotechnical Architecture".

<a name="socio-tech-arch-definition"></a>
## Definition: Sociotechnical Architecture <a href="#socio-tech-arch-definition">⇦</a>

What is Sociotechnical Architecture? From my research I did not find a reference definition. My current definition is the following:

> *"Sociotechnical Architecture is about taking an holistic co-design approach to technical and organizational systems, given the inherent impact they have on each other."*

[Nick Tune](https://ntcoding.co.uk) (a prominent promotor of Sociotechnical Architecture thinking) states that Sociotechnical Architecture concerns with the fact that [<a href="#sociotechnical-architecture">Sociotechnical-Architecture</a>]:

> *"when we are architecting a software system, we must consider the impact on the teams in the organisation and vice-versa."*

So, it really concerns with approaching design with an holistic view that can capture the inter-relations of the different systems involved, instead of purely focus into just one (classically the technical systems).

<a name="socio-tech-evolution-loop"></a>
## The Sociotechnical Evolution (Loop) <a href="#socio-tech-evolution-loop">⇦</a>

By having a sociotechnical approach to architecture, we consider teams (or "system of work") and how these drive the build and evolution of the software architecture/product (or "system of software"). Teams discover, capture and interpret the input and signals from the customer (or "market"). This is the input to understand how they can maximize the value provided and exchanged (by the product) with the customer. Figure below shows this "sociotechnical evolution" loop [<a href="#sociotechnical-evolution">Sociotechnical-Evolution</a>].

![Sociotechnical Evolution Loop](/assets/sociotechnical-evolution-loop.png)

Sociotechnical Architecture aims at co-design the system of work and the system of software in order to design these two systems for success. In general this means enabling the teams to iterate on this loop at high velocity (i.e.: high speed and clear direction), so that they can improve and provide the best product to the customer. This is the way to maximize value exchange with the customer. This speed of iteration and cadence of delivering new features are two of the four top metrics that the book Accelerate [<a href="#accelerate">Accelerate</a>] has identified when researching and profiling high-performing technology organizations. To maximize these metrics, it is clear that we will get sub-optimal results if we purely focus on the Software Architecture elements (or "system of software"). We must take an holistic approach and optimize the different systems at play → this is why Sociotechnical Architecture thinking is so important and enabling to step towards being a "high performing organization".

<a name="summary"></a>
## Summary

In this first article I gave context and motivation on why it is so important to have a sociotechnical approach to architecture (i.e.: co-design your organization & technical systems). If we look at how the different systems involved when building a product for a customer interact we see that organizational" (or "social") elements are core to understand the customer and then build or evolve the product to maximize the value exchanged with customer. It is very much like getting the right crew and give them the necessary conditions when we are setting up a restaurant for success. This why Sociotechnical Architecture is so relevant: it provides a base to consider the different elements that contribute to the overall performance in this system of systems.

<a name="references"></a>
## References

* [Cynefin] [https://en.wikipedia.org/wiki/Cynefin_framework](https://en.wikipedia.org/wiki/Cynefin_framework); [The Cynefin Framework (Video)](https://www.youtube.com/watch?v=N7oz366X0-8), Dave Snowden <a name="cynefin"></a>
* [Sociotechnical-Systems] [https://en.wikipedia.org/wiki/Sociotechnical_system](https://en.wikipedia.org/wiki/Sociotechnical_system) <a name="sociotechnical-systems"></a>
* [Sociotechnical-Architecture] [Twitter Thread: Sociotechnical Architecture Definition](https://twitter.com/emgsilva/status/1260953999093706752?s=20) <a name="sociotechnical-architecture"></a>
* [Sociotechnical-Evolution] [Primary Sociotechnical Design Heuristics](https://medium.com/nick-tune-tech-strategy-blog/primary-sociotechnical-design-heuristics-5aa164b3e876), Nick Tune <a name="sociotechnical-evolution"></a>
* [Accelerate] [Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations](https://itrevolution.com/book/accelerate/), Nicole Forsgren, Jez Humble, Gene Kim <a name="accelerate"></a>

<a name="changelog"></a>
## Changelog

* 01/07/2020: "Beta/RFC", first public version of the article published (open "Request For Comments" - RFC)

<div style="border:1px dotted black; padding:1em; background-color: beige">
    <h3><b>ℹ️ I offer consulting services and products on this topic</b></h3>
    <p>If you are looking for help on these topics feel free to <a href="mailto:eduardo@esilva.net">contacting me</a>, and/or check my <a href="/consulting">consulting</a> and <a href="/products">products</a> pages for more details on how I may be of help.</p>
</div>
<br>
