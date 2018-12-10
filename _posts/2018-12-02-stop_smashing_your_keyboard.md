---
layout: post
title:  "Stop Smashing your Keyboard! Zoom out! Think!"
permalink: /everyone-architects/stop-smashing-zoom-out-think.html
---
<!-- part of the Everyone Architect essays series -->

```TL;DR: post about my presentation at spaces summit 2018 (bol.com internal technical conference). I talked about the need to stop smashing our keyboards and "blindly" focus on "speed", and start thinking about "what" we are doing, "why" and "how" should we be doing it. By "zooming out and thinking" we take architecture and design into consideration. This basically means that we give "direction" to our "speed", which results in achieving "higher velocity". This is the first article I am writing on a topic I call "Everyone Architects". #EveryoneArchitects #Architecture #Agility
```

Few months ago we have the second internal <a href="https://careers.bol.com/stories/spaces-summit-2018/" target="_blank">technical conference at bol.com</a>. This is a great moment for sharing interesting things with each other and build a stronger technical community within the company. This year I made a presentation that focused on the importance of "design and architecture" when building software products - you can watch it bellow. In the following I provide an overview and some extra details on the main points of the presentation.

<div align="center"><iframe align="middle" width="500" height="315" src="https://www.youtube.com/embed/FCqn9iHU9xo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div><br>

# Going Fast!

As professional software builders we empower digital businesses on implementing their products and services. In order to keep up these businesses increasingly relevant and ahead of competition we experience a constant urge to "go fast". "Going fast" is one of the most used terms on today's digital businesses. To keep with this "need for speed", these organizations are adopting different philosophies: agile, lean, etc., all in the name of "delivering things fast". The search for ways to be faster and more efficient is certainly a good thing. However, the way many teams are applying these approaches is leading to counter-productive results (i.e.: "go slowly").

# Blind Agile and Go Fast

The emergence of agile methodologies has been transformative on modern companies that build software. However, a vast majority of teams are over-focusing on "speed" (from physics: <a href="https://en.wikipedia.org/wiki/Speed" target="_blank">"rate of motion"</a>. In their haste to move fast towards their final goal, these teams put their heads down and "smash their keyboards", without properly understanding where are they going. Given this, you may go very fast (in absolute terms - e.g.: write a lot of code), however, is your team aware of the direction your project is moving? Are you taking good steps towards delivering the end goals you want to achieve? What are those end goals? More often than not, there are no clear answers to those questions... and teams end up following sub-optimal "random moves" towards an unclear end goal.

![StackOverflow](/assets/blind-agile.png)

_I like to think about these situations using the metaphor of driving a very powerful car blindfolded. So, we drive this powerful car very fast until you bump into something. Then, we just try to steer the car into another direction where we can move and just press the gas again until you face another bump. You repeat this until eventually you reach your end goal. However, this is a really poor use of your powerful machine, right?_

# From High-speed to High-velocity!

We must stop moving "instinctively" (and randomly) and define "direction" for our developments. In a nutshell, we must strive for "high-velocity" (speed with direction) not "high-speed".

What does that mean? It means that when we are implementing our products we must consider design and architecture to better understand and define the direction of our developments.

# Stop smashing your keyboard! Zoom out and think!

When starting a new project, don't immediately jump into your keyboard and start implementing (following your gut). Take a moment and together with your team ask a few questions: What are we doing? Why are we doing it? How are we going to do it? Let’s dive into these questions separately.

**What are we doing?**

We must understand what is your goal; what you want to build; what users you will have; what ...

**Why are we doing it?**

We must understand the motivation, and even be critical and consider whether it is worth doing it (an underused question).

**How are we going to do it?**

We must understand and define a common perspective and direction for your efforts. Build a plan for your developments.

__Important__: don't build a start-to-finish "step by step plan" (A.K.A.: "big up-front design"). We, as industry, have learned over the last decades that it is a complete waste to do that: you will face many "design decisions" along the way that you cannot fully anticipate at the beginning of the project. We must accept that and be more reactive and iterative on our design (<a href="https://www.thoughtworks.com/books/building-evolutionary-architectures" target="_blank">evolutionary architecture</a>). However, "have a plan" to follow after at each "design decision" you face, and use that to refine the direction where you will apply your speed.

# Framework for Incremental Architecture Design

As engineers & architects of our products, we can define a basic framework to address this "incremental architecture design" approach, namely:

* ```1) always start the project with design considerations on the “important decisions” that need to be addressed (and cannot be delayed). Simply ask the the “why”, “what” and “how” of the project. Use that input to define your direction.__```
* ```2) if you face an “important decision”: “zoom-out and think” (ask the “why”, “what” and “how” of the design decision).```
* ```3) repeat 2) until you reached the “end goal” of your project (which again may vary as the project progresses - i.e.: being capable to redefining your direction along the way becomes a major factor to cope with such variations on the end goal of the project).```

The approach is very simple. Don’t start a project blindly, look into the “important decisions” that need to be made. “Important decisions” is my favorite definition of architecture. It represents the things that are difficult to change on a later stage.

Given this, whenever we face a design decision, we should properly consider it. For example: choosing project programming languages; buy or build; cloud or on-premises; architecture model (MVC, REST API + client side JS, etc.).

However, don’t try to foresee all the possible design decisions at the beginning of the project (a.k.a.: “big upfront design”, I also like to call it “fallacy of complete design”). If something is not clearly important to be addressed at the beginning of the project (or whatever stage of the project you are), it should not be addressed. This is normally a clear sign that it does not yet need to be addressed.

Use the “latest moment possible to take a decision”. Why? Because (most probably) a decision is not required before; and when you actually need to take the decision, you have already progressed on your project and have more knowledge and experience to take a “better decision” than when you try to foresee all the decisions at the beginning of the project.

![StackOverflow](/assets/incremental-architecture.png)

_Resuming the powerful car driving metaphor: if you use this framework to assist you on your journey towards your end goal you will basically get a map, and have a clear view of your drive. You will bump into unanticipated obstacles (e.g.: unannounced road blocked), however, with a map and clear view of the ways you can move, you can redefine in a very informed manner, what direction you will apply your speed. In this way, you will be able to properly make use of your powerful machine and don't just go blindly fast!_

Although this all sounds logical, it is rather common to go on the freestyle mode and just focus on "speed", leading to many surprises and also uncertainty. By following these simple steps one can bring a lot of clarity and predictability to our developments.

Keep in mind: I am not saying that you "must do this" on all your projects. If you are doing something very small and undoubtedly clear, you probably (especially if you are rather experienced on the project) can "just do it". However, I would still argue that having a basic roadmap is always a way to keep you on the safe side and avoid unnecessary surprises when implementing your project.

# Some Tools

To make the above way of working operational and successful, you can make use a few interesting tools and ideas, namely:

* Visualization of problems and solutions
* Architecture Decision Records

Visualization of problems and solutions is nothing more than "going offline" to "zoom-out and think". The main goal here is to step away from your keyboard and sketch/draw the design decision you have at hand. Use that as a mechanism to provide a clear perspective of the problem you are dealing with or the solution you are trying to build. Furthermore, bring your team together around those exercises, so that you all create a common perspective of the problem/solution, and based on that define your direction to go and start working on it. You don't need to use UML or formal architecture languages. Stick with simple sketches on a whiteboard or piece of paper - as long as it is understandable and useful for the people participating in the discussion. Simon Brown has written extensively about this and proposes many interesting ways to do this in very simple ways. Look <a href="https://leanpub.com/visualising-software-architecture" target="_blank">here</a> for some inspiration.

![StackOverflow](/assets/visualization.png)

<a href="http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions" target="_blank">Architecture decisions Records</a> (by Michael Nygard) are a very interesting framework to systematically document the "important decisions" that you face on your project. It provides a set of questions that cover the "what", "why" and "how" of a design decision. Each record entered on the ADR is immutable, i.e.: it stores how we dealt with a given design decision. If later we need to do something that changes such a decision, that is per se another ADR (which basically reverts a previous decision). This is a great way to have a systematic set of questions to address when faced with a design decision. Furthermore, it also enables us to keep track of the main design decisions taken on a project. Another interesting trait of this approach is that you can keep it on your project code base, and in this way maintain your documentation and code close to each other.

# Best Architecture emerges from self-organized teams and in a truly Agile Organization "Everyone Architects"

I hope this post inspires you to start doing some more serious thinking on the design and architecture of your projects. Although lately "blind agile" (or "anti-architecture" agile) has been dominating on our scene, the agile manifesto does not state that "teams should forget about design and architecture and just go fast". In fact, it states a very interesting remark: the "best architectures and designs emerge from self organized teams". This is a very interesting topic, namely: Architecture on today's agile and modern software building organizations is not done by "Ivory tower Architects", but by everyone building the products (the teams). I call this "<a href="https://esilva.net/everyone-architects" target="_blank">Everyone Architects</a>" and it basically emphasizes the need to have teams doing design and architecture as they are the ones building the products and being faced with the "important decisions".