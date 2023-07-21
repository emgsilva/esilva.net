---
layout: post
title:  "Evolving Tech-enabled Orgs Using Sociotechnical Architecture (DevOps Lisbon Meetup)"
categories: [conference]
---

On March 15th (2021) I was at [DevOps Lisbon Meetup](https://www.meetup.com/DevOps-Lisbon/events/275916783/) giving a talk on Evolving Tech-enabled Orgs Using Sociotechnical Architecture and Systems Thinking. This was a great event where I had the opportunity to share and discuss some new ideas I have been exploring on my journey of learning and "consolidating" the use of systems and sociotechnical thinking as a way to support how we evolve our tech-enabled organizations. This is a new talk on this topic and I am also preparing an article to articulate the ideas shared in this presentation (which will become part of my [Introduction to Sociotechnical Architecture Series](https://esilva.net/sociotechnical)). However, I want to share the main aspects I touched, as this was the first time I combined all these points into a single talk.

The presentation had three main parts:

* Part I: Introducing and Motivations of Systems Thinking
* Part II: Sociotechnical Architecture as a Way to Support Org Evolution & How to Approach it
* Part III: Examples Org Evolution and how to Approach it using Sociotechnical Architecture

In the following I will elaborate on each of the parts. You can also find the video and deck of the presentation below.

<div style="left: 0; width: 100%; height: 0; position: relative; padding-bottom: 56.1972%;"><iframe src="https://www.youtube.com/embed/f57wd_GeXhI?controls=0" style="border: 0; top: 0; left: 0; width: 100%; height: 100%; position: absolute;" allowfullscreen scrolling="no" allow="encrypted-media"></iframe></div>

<div style="left: 0; width: 100%; height: 0; position: relative; padding-bottom: 56.1972%;">deck: <iframe
      src="https://speakerdeck.com/player/e6dd7add01084d4593fa1a53e4226e00"
      style="border: 0; top: 0; left: 0; width: 100%; height: 100%; position: absolute;" allowfullscreen scrolling="no"
      allow="encrypted-media"></iframe></div><br>

## Part I: Introducing & Motivations of Systems Thinking

I start the presentation by looking at the main ideas of Product Thinking, which I summarize as the activities of "maximizing the value exchange with the customer". If we want to truly achieve that goal we need to stop looking at all the systems at play in isolation, since understanding comes from looking at the parts and their interactions (core premise of systems thinking). I motivated this using my "Traits to build great Restaurant" metaphor, which I introduced in this [article](https://esilva.net/sociotechnical/sociotechnical-architecture_why-and-what.html) of my "Intro to Sociotechnical Architecture" series. On this running example I gradually show traits that motivate the core aspects of systems thinking, namely: taking a holistically perspective to truly understand the system and from there its parts; consider the relationships of the different parts of the systems; and furthermore the need to embrace change as a normal part of the system evolution and coping with its environment.

<div align="center"><img src="/assets/need-holistic-view.png" alt="Holistic View" width="80%"/><br></div>

Based on this, and if we want to truly achieve the goal of product thinking, we should not purely focus on "understanding What the customer wants"; we also need to make sure the org that is building the product is setup adequately (the "Who" system, or Teams), as also the technical architecture of the product (the "How" system) is aligned with the organization. I emphasize that local optimizations approaches (being Product Thinking as a way to understand the customer and build a better product; DevOps as being a better way for "development" and "operations" to work more effectively together; or Microservices to build a technical architecture) without being positioned in the involving system they are part of, will most likely lead to partial optimizations, or even worse: may lead to degrading the overall system performance.

This is why a systems thinking approach is so important. It provides ways for us to truly understand the whole system and from that perspective its parts (and not the other way around). This is a very important realization of systems thinking.

<div align="center"><img src="/assets/devops_lisbon-improve_parts_and_whole.png" alt="Holistic View" width="80%"/><br></div>

These ideas may be somehow counter-intuitive, as we tend (and are trained in modern education systems) to focus on breaking systems into parts of focus on making those parts better in isolation, without always having clear what the other parts are doing or how the overall system is doing. However, at the end of the day if all the isolated improvements don't lead to better results for the overall systems (e.g.: our company and end product), or may even degrade the overall results, why are we doing them? This is why it is so important to understand (the "Why" behind) the improvements in our part in the context of the system (whole) that surrounds it. For example, in the running example I had: the restaurant was the system to look at if we want to look at how to improve our dishes. I refer to a great visualization and tweet from Ruth Malan [<a href="#systems-understanding-malan">Systems-Understanding-Malan</a>] to describe the main points elements to understand Systems. The image below shows that slide of the presentation. In a nutshell: we focus on understanding the structure and the dynamics of the system; and furthermore we also look at properties that emerge from the interactions of structure and dynamics (as in the right hand rule from physics) — and also with context.

<div align="center"><img src="/assets/devops_lisbon-systems_understanding_malan.png" alt="Systems Understanding" width="100%"/><br></div>

## Part II: Sociotechnical Architecture as a Way to Support Org Evolution & How to Approach it

After motivating the need for systems thinking, I share my current mental model to describe the system ("whole") of tech-enabled organizations. I see it as a Sociotechnical System [<a href="#sociotech-arch-silva">Sociotech-Arch-Silva</a>], where you have a customer/market, raising demands to the organization/teams, who then build/evolve the product that the customer will use. Figure below shows a representation of the parts and their core interactions.

<div align="center"><img src="/assets/sociotechnical-evolution-loop.png" alt="Sociotechnical Architecture" width="100%"/><br></div>

This mental model motivates the need for Sociotechnical Architecture, which I define as "the holistic co-design approach to technical and organizational systems, given the inherent impact they have on each other".

Given this, and in order to evolve our system with a clear understanding and clear strategy, we must approach it from a holistic understanding, and from there zoom-in to the different systems with an aligned hypothesis for action. I had the following slide on the presentation depicting this idea (credits to [Trond Hjorteland](https://twitter.com/trondhjort) for pointing out to this great visualization - originally on [<a href="#systems-thinking-barton_haslett">Systems-Thinking-Barton_Haslett</a>]).

<div align="center"><img src="/assets/sociotechnical-architecture-appraoch.png" alt="Approaching Sociotechnical Architecture" width="80%"/><br></div>

In a nutshell we see that we can approach Sociotechnical Architecture by being on a continuous loop of understanding from the holistic perspective, given the input (data) we gather from all the parts (feedback loops). This is called "synthesis", and it is done from the holistic ("emphasis on the hole") perspective. This is key to understand and from there generate "hypothesis" to drive action on the different parts of the system. The hypothesis then drives action on each part of the system. This leads to iteration and as time advances more learnings (data, via feedback loops), which may be used in other iterations of evolution. I have formulated this loop with the following "algorithm".

<div align="center"><img src="/assets/sociotechnical-architecture-appraoch-algorithm.png" alt="Sociotechnical Architecture Approach Algorithm" width="80%"/><br></div>

I have also shared another interesting visualization to depict this evolution of the sociotechnical architecture (which I also use in some use cases - shared in the next section). This can be seen in the following figure.

<div align="center"><img src="/assets/sociotechnical-architecture-evolution-diagram.png" alt="Sociotechnical Architecture Evolution Diagram" width="100%"/><br></div>

With this diagram I am trying to depict a way to express the evolution, and elements that trigger evolution iterations. This is still an idea being shaped, but the goal is to make it explicit on the state of the sociotechnical architecture, the triggers we observe and the sort of hypothesis we define from the synthesis of all the data we gathered. I will be sharing more on this on a coming article on my [intro to sociotechnical series](https://esilva.net/sociotechnical).

## Part III: Examples Org Evolution and how to Approach it using Sociotechnical Architecture

WIP - (will be sharing some notes on the examples soon)

## References

- [Systems-Understanding-Malan] [Systems Understanding](https://twitter.com/ruthmalan/status/1093294478641823744), Ruth Malan<a name="systems-understanding-malan"></a>
- [Sociotech-Arch-Silva] [Sociotechnical Architecture](https://esilva.net/sociotechnical), Eduardo da Silva<a name="sociotech-arch-silva"></a>
- [Systems-Thinking-Barton_Haslett] [Analysis, synthesis, systems thinking and the scientific method: Rediscovering the importance of open systems](https://www.researchgate.net/publication/229729730_Analysis_synthesis_systems_thinking_and_the_scientific_method_Rediscovering_the_importance_of_open_systems), John Barton, Tim Haslett<a name="systems-thinking-barton_haslett"></a>

<div style="border:1px dotted black; padding:1em; background-color: beige">
    <h3><b>ℹ️ I offer consulting services and products on this topic</b></h3>
    <p>If you are looking for help on these topics feel free to <a href="mailto:eduardo@esilva.net">contacting me</a>, and/or check my <a href="/consulting">consulting</a> and <a href="/products">products</a> pages for more details on how I may be of help.</p>
</div>
<br>
