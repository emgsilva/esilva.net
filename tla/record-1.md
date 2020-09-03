---
layout: default
title: TLA_insights record \#1
permalink: /tla_insights/record-1
---

Welcome to the record #1 of my "Technical Leadership and Architecture insights" (or TLA_insights for short).

![light](/assets/tla_insights-text.png)

**What is this?** TLA_insights is compilation of insights (![light](/assets/light-bulb.png) "*deeper understanding*") I develop in the topics of Technical Leadership and Architecture (in context of Building Software products). This is a rather broad area, which means one needs to develop all sorts of skills and knowledge to be able to "develop & make things better". To accomplish this I tend to study different resources, from which I take notes to distill the most interesting insights. With TLA_insights I want to curate those insights further and give some of my own views and interpretations. Hopefully these curated insights are useful for other people interested in these topics.

> I will be publishing TLA_insights at least once a month. This also may look like a newsletter, but it really is about sharing curated insights, which may not be "news" all the time, so I am calling it an "Insights-letter".

**Why am I doing this?** Two reasons:

- 1: curate and consolidate the insights I develop, as I will further process and organize them in my mind while writing them down, and with that I improve my knowledge and command of these topics
- 2: to share these insights with others, who can also benefit from that

**How is this organized?** It is basically a collection of summaries & insights from resources I find interesting. I will be organizing these into sections, which represent areas I am really interested and actively developing/researching in the wider topic of Technical Leadership and Architecture. Currently these are the areas:

- Sociotechnical Architecture & Systems Design
- Technical Leadership
- Software {Architecture, Engineering & Tech}
- Personal Productivity

I hope you have fun and find some interesting insights here. Don't hesitate to [contact](mailto:emgsilva@gmail.com) me if you have questions or want to chat about these topics.

![light](/assets/light-bulb.png) **TLA_insights record #1:**

- 1: Sociotechnical Architecture & Systems Design
  - [Visualizing Sociotechnical Architecture with DDD and Team Topologies, Nick Tune](#visualize-sociotech-arch-tune)
  - [Recurrent misuse of API-first pattern/strategy, Stefan Tilkov](#api-first-misuse-tilkov)
- 2: Technical Leadership
  - [Maker VS Multiplier, Patrick Kua](#maker-multiplier-kua)
  - [First Principles: The Power of Thinking for Yourself, James Clear](#first-principles-clear)
- 3: Software {Architecture, Engineering & Tech}
  - ["Good Enough" Architecture, Stefan Tilkov](#good-engough-arch-tilkov)
  - [5 Things Every Developer Should Know about Software Architecture, Simon Brown](#5-things-brown)
- 4: Personal Productivity
  - [Pillars, Pipelines and Volts (PPV), August Bradley](#ppv-bradley)

## 1: Sociotechnical Architecture & Systems Design

<a name="visualize-sociotech-arch-tune"></a>

### Visualizing Sociotechnical Architecture with DDD and Team Topologies [[article](https://medium.com/nick-tune-tech-strategy-blog/visualising-sociotechnical-architecture-with-ddd-and-team-topologies-48c6be036c40)], Nick Tune <a href="#visualize-sociotech-arch-tune">⇦</a>

On this first record of insights on Sociotechnical Architecture I am covering a resource from [Nick Tune](https://twitter.com/ntcoding). Nick is very active in Sociotechnical Architecture and Domain-Driven Design (DDD) communities. He has a keen interest in defining ways that can include everyone (even non-experts) in the process of finding better strategies to approach the build of software. In his work he looks into aspects from software architecture but also the organizational and team aspects. This particular article is a good example of that. It presents a visualization Nick has developed called "[Core Domain Chart](https://github.com/ddd-crew/core-domain-charts)" (see image below), which enables visualizing the core "elements/capabilities" of a business and with that strategize on different things.

![Core Domain Chart](/assets/core-domain-chart.jpg)

(source & credits: [https://github.com/ddd-crew/core-domain-charts](https://github.com/ddd-crew/core-domain-charts))

This chart distinguishes the nature of capabilities, namely "core", "supporting" or "generic" (as in DDD subdomain types); and furthermore shows how complex and differentiating they are. With this we can have an aligned discussion on the capabilities within our Product(s) in terms of investment, strategy for development, team/org design strategy (e.g.: these two capabilities have a lot of relationships, maybe they can be owned by a single team), among other things. This discussion is supported by this simple visualization, which enables anyone relevant to the discussion to understand and actively participate (it is not a tool for technical people only, anyone can start using it in a matter of minutes).

This chart can be used for different purposes, e.g.: capability portfolio overview (what type of focus we want to give to our difference "capabilities"); Optimizing Investments (example: create a map of the number of people per capability); Analyzing relationship between capabilities (using [Team Topologies](https://teamtopologies.com/) "interaction types" - which enables to identify and strategize how teams interrelations should evolve, e.g.: move from a collaboration to as-a-Service relation, after discovering a clear focus for each capability); Optimize capabilities ownership overview (i.e.: given the type of relationships between capabilities, have a better strategy of what would be the most interesting team setups - also called "Super Context" on Nick's examples). Full documentation on the Core Domain Chart can be found [here](https://github.com/ddd-crew/core-domain-charts).

> ![light](/assets/light-bulb.png) Nick manages to combine a set of (complex) elements together into a simple chart that enables anyone to provide input and be part of the discussion, and with that identify, align and shape how to move forward. To me this is a go-to tool to have a proper and informed discussion about the "business capabilities" (components, products, etc.), their relation, "ownership" and especially how do we want to invest and move forward with that whole picture in mind (i.e.: a clear direction).

<a name="api-first-misuse-tilkov"></a>

### "Recurrent misuse of API-first pattern/strategy" [[Tweet thread](https://twitter.com/stilkov/status/1250355396864176132?s=20%20)], Stefan Tilkov <a href="#api-first-misuse-tilkov">⇦</a>

This Twitter thread by [Stefan Tilkov](https://twitter.com/stilkov) raised a very interesting discussion on the rather common misuse of the “API-first“ strategy. In classic Stefan style, he comprehensively shows several interesting points and patterns where such misuse happens. Most prominently the overuse of this technique for "encapsulation" of technical capabilities within the "enterprise". This tends to be part of the mission of many Enterprise Architects, as a way to have a good governance model over the different "parts of the enterprise". However, if APIs are purely built "inside-out" (just as a way to encapsulate and expose business capabilities) and are not built as a product, i.e.: based on the needs of the customers/clients using it (and what they are looking for), it tends to lead to a mismatch of expectations.

At a given moment of the thread Simon Wardley shared a nice visualization of "types of developments" where APIs are strategic and how to start such initiatives using [his famous Wardley maps](https://twitter.com/swardley/status/1251479895479386114?s=19).

> ![light](/assets/light-bulb.png) This is a really good thread to freshen up strategies, patterns and best practices to drive the building of API-based products. Although APIs provide "encapsulation" and a way to expose capabilities of a business, they should (I would say must) be built based on the customer(s) that will use them, in true "product development" style. They are not "just a technical artifact for integration", even though this can also be a consequence. However, we should not be the sole driving factor, even if the goal is to enable integration.

## 2: Technical Leadership

<a name="maker-multiplier-kua"></a>

### Maker VS Multiplier [[article](https://www.patkua.com/blog/maker-vs-multiplier)], Patrick Kua <a href="#maker-multiplier-kua">⇦</a>

First entry on the Technical Leadership section of this first record and who else should be here if not one of my top references when it comes to the topic of Technical Leadership: [Patrick Kua](https://www.patkua.com/). I am sure I am going to cover many other entries in this section from Patrick as he does not stop creating top notch content and insights on how to be a better Technical Leader and manage all the many dimensions of such a role.

In this particular article he explores something extremely important: the Maker and Multiplier operating modes that people working on Software Development have. Maker is the predominant operating mode of Engineers and Individual Contributors: *solve the problem at hand*, applying the best approach and spending the time needed to make it happen. This mode tends to mostly be about "the self" making the work. When transitioning to a leadership role, the maker mode (that makes engineers / individual contributors successful) becomes one of the top sources of issues, especially because it tends to focus on "self" instead of the team they work with. This focus on "self" as a leader means less time/space to support the team and to a continuous struggle to keep up with the work on the team (and the work that needs to happen outside the team). When transitioning to a leadership role it is important to adapt the operating mode, and focus on being a "multiplier" of the teams you are leading and "enabling". If you do it well, you multiply your impact.

Patrick has written and provided a lot of resources on this topic, make sure to check his articles, [courses](https://techlead.academy), [newsletter](http://levelup.patkua.com/) and also his book "Talking with Tech Leads" (find my review of the book [here](https://esilva.net/articles/talking_with_tech_leads)).

> ![light](/assets/light-bulb.png) When you transition from Individual Contributor (IC) to a Leadership role, make it explicit that you cannot be a full-time maker. This is one of the most common (if not the most common) and recurrent "mistakes" I see people making: continue working on a team as a full-time member/engineer, while having a full-time Leadership role. It is also important for managers to explicitly discuss this with people starting in these Leadership roles (e.g.: Tech Leads) and make it clear that they should work in a "partial mode" on a team or teams, and mostly focus on helping to bring clarity to those teams, and with that become a "multiplier of makers".

<a name="first-principles-clear"></a>

### First Principles: The Power of Thinking for Yourself [[article](https://jamesclear.com/first-principles)], James Clear <a href="#first-principles-clear">⇦</a>

Taking decisions by analogy is the prevalent way of thinking in present times (*others did this, we should probably too*). The Tech world is no exception, for example: organizations blindly adopting Microservices because Netflix did so; or copying the "Spotify Model" (snapshot) because it seemed to have worked great for Spotify. This way of thinking is dangerous and in most cases leads to undesired or sub-optimal situations. Why? Because we force ourselves to follow the approach for the problem of someone else. Such approach was designed for their particular problem and as such it shouldn't be a surprise when most of the times this leads to a sub-optimal results on our particular problems.

What is an alternative way to approach this? Using "First Principles thinking". This article by [James Clear](https://twitter.com/JamesClear) gives a nice intro to what First Principles thinking is. In a nutshell First Principles thinking is about breaking things/problems down to the atomic pieces/knowledge/truths and from there build up strategies that use those atomic elements so we can best address our particular problem. The article talks about some specific situations and examples, namely how Elon Musk continuously applies this way of thinking to completely revolutionize several industries.

> ![light](/assets/light-bulb.png) Be very careful when copy-paste models that work for certain people and organizations (e.g.: the Spotify Model). These models tend to be designed for complex system of systems, which most likely are different from yours. Get inspiration from those models and cases, but don't just force it into your situation. Instead, focus on understanding your problems (e.g.: organization situation), its challenges and "DNA" and from there build up strategies to address your particular problems and reach your own goals, from your own atomic elements.

## 3: Software {Architecture, Engineering & Tech}

<a name="good-engough-arch-tilkov"></a>

### "Good Enough" Architecture [[video](https://youtu.be/PzEox3szeRc), [slides](https://gotober.com/2019/sessions/846/slides)] Stefan Tilkov <a href="#good-engough-arch-tilkov">⇦</a>

[Stefan Tilkov](https://twitter.com/stilkov) showcases six different real world architectures where something "went wrong" and "lessons learned" from that (on technical but also organizational aspects). This is a condensed show of wisdom, where we can learn a lot about several patterns and practices to consider or avoid when architecting systems. Many of the remarks/lessons could be framed and placed on the walls of offices of people building software systems - e.g.: "If your design attempts to satisfy everyone, you’ll likely end up satisfying no one".

Stefan concludes with some interesting remarks, namely: don't be afraid of architecture, and don't ignore it: it will always be there, so you better think of it explicitly instead of just "letting it organically & accidentally grow", that is a recipe for disaster. Keep it simple but make sure that if you need to cope with different conditions its structures are evolvable; plus architecting does not mean "full upfront architecture", it can be (and should be) an incremental process.

> ![light](/assets/light-bulb.png) Architecture is a misunderstood discipline and there is a lot of push back from many, and especially people that adopted "partial views" of Agile: Agile manifesto never said "don't do Architecture"! The fact is: there is always an architecture and as such we better make it explicitly part of our ways of working. By focusing on "good enough" architecture, as Stefan shares, we can make great steps to modernize how we do Architecture and make it an important part of the journey of building software products. As Grady Booch said: "Architecture represents the significant design decisions" and I am sure no one doubts we need to properly address those. It may mean take a few moments now, but that will enable us to go at much higher velocity for much longer!

<a name="5-things-brown"></a>

### 5 Things Every Developer Should Know about Software Architecture [[article series](https://dev.to/simonbrown/series/7666)], Simon Brown <a href="#5-things-brown">⇦</a>

[Simon Brown](https://twitter.com/simonbrown) is undoubtedly one of the major contributors to modernize and "democratize" how we approach Software Architecture. He has been a major inspiration for me for 10+ years and this article series is a good "gist" of the core dimensions of Simon Brown views Software Architecture.

The series starts with "Software Architecture isn't about big upfront design", where Simon dissects the basic elements to look for when approaching software architecture. This is the "bare minimum" to set us on a good path, and from there iteratively address new elements as you learn more things (with this we can make more informed decisions).

Then he goes to a point very dear to me: "Every software team needs technical leadership", i.e: teams need to have technical leadership in order to continuously stay aligned, look for and address the important decisions (= architecture), mitigate risks and consistently grow the technical vision of their product(s). This can be owned by a single person or by the whole team, but must be explicitly set.

In the third article Simon touches on the fact that "Software Architecture role is about coding, coaching and collaboration", i.e.: make sure to not focus just in one of these dimensions. This is one of the most classic mistake of first time Software Architects - continue over-focusing on the code and forget about the coaching and collaboration dimensions.

The fourth article focuses on the fact that Architecture documentation does not necessarily mean UML and complex documentation. Here Simon shares his [C4 Model](https://c4model.com), and how we can use it to document architecture by addressing different perspectives, which represent different levels of detail (like a map, and zooming into a map). This approach enables a pragmatic and simple approach where the people relevant for the discussion can be easily involved.

The last article titled: "A good software architecture enables agility" is in my view one of the major realizations that a lot of people in the industry need to develop: architecture is not a blocker for agility, i.e.: do not panic if you need to spend some hours or days investing on understanding and creating a clear alignment and strategy on how to proceed on building your product. That is in fact a crucial exercise to enable your agility and move forward at high-velocity (clear direction and high speed).

> ![light](/assets/light-bulb.png) Architecture is not just about technical design (or dictating top-down a design for teams to build), it is much more. As an industry we need to embrace it and make it clear so that we can benefit from the power it brings to our developments: set clear direction for our developments, make sure our teams are equipped and are capable of owning the envisioned architecture and be enabled to improve their product(s) continuously. If we don't do that, we are losing a great opportunity of bringing clarity and alignment to our developments.

## 4: Personal Productivity

<a name="ppv-bradley"></a>

### Pillars, Pipelines and Volts (PPV) [[video series](http://notionproductivity.com)] August Bradley <a href="#ppv-bradley">⇦</a>

[August Bradley](https://twitter.com/augustbradley) has developed a very interesting and powerful personal productivity methodology called "Pillars, Pipelines and Volts" or PPV in short. This methodology is carefully crafted and is grounded in the idea of creating systems that support us on "aligning on what is important" to grow into the areas we want to grow. With that clarity on "where we want to go" we can more easily focus on execution.

This is a short overview of PPV:

- "Pillars" are the elements that sustain and define our life, the things that are important for us and to move towards our "north star". We define those to make it explicit and to connect and drive all other parts of the system to develop our Pillars. If we are working on something that is not contributing to a Pillar, most likely it is not relevant for us (or we need to make a new Pillar explicit).
- "Pipelines" define the systems that enable connecting all the necessary elements to develop our Pillars. They consist of higher level "Value Goals", which define aspirational things we want to develop on our Pillars (think: publish more interesting content on my blog). We define these yearly and review them quarterly. They help sharpen the "direction" for our developments. To make them more actionable we define "Goal Outcomes" (which are rather similar to OKRs). Here we define a very clear and measurable outcome (think: Write 2 articles per month on my blog). "Goal Outcomes" are reviewed regularly, in general quarterly & monthly to make sure we are progressing and still work on the most important things. To actually accomplish the "Goal Outcomes" we create "Projects" (think: write an article about agile architecture). These define the iterations we will make to move things forward and achieve the desired outcomes. Projects are reviewed Weekly, to make sure we advance and work on the right things. Within Projects we have "Actions" (or Tasks), which are concrete steps we will work on daily to execute and reach our ambitions. On a day-to-day basis we focus on getting tasks done (which should emerge on our todo list as a consequence of our regular reviews and prioritization).
- "Vaults" are basically places where we collect information and knowledge, which will support us in executing our ambitions.

I have tried many different methodologies and in time developed my own, and to be fair I think PPV formalizes many of the elements I came to develop in time, plus it adds quite a sound structure to it with a clear philosophy: "Focus & Alignment" (i.e.: create clarity where to go, review it often to make sure you are in the right path, as this will enable you to focus on execution on your "day to day"). 

August presents PPV through an excellent and thorough [video series](http://notionproductivity.com/) (and is preparing supplementary material and training) so people can more easily implement this approach. Implementing this will take some effort but the outcome really pays off (if you want to shape and customize your personal productivity system to your needs). To implement PPV August uses a very flexible tool called [Notion](https://www.notion.so/), which is an app that merges several features: note taking, wiki but also enables to create flexible databases, which can be visualized in different manners. This flexibility is key to implementing PPV and variations of it (which is what most people will most likely do - to adapt and support their specific preferences and way of working). Most productivity tools tend to prescribe a way of working that does not capture all the dimensions of PPV (or customized elements we want to have), namely enabling the creation of a system of systems that operate and connect with each other to address the different needs we have to organize our lives. August states that PPV is a way to implement a "Life Operating System (OS)" and after adapting most of it on my own setup I fully agree with him.

> ![light](/assets/light-bulb.png) I am continuously sharpening my way of working and how to have a system that enables me to focus on executing on the important and relevant things. Over time I noticed that the trick is not about "planning things", but about "making sure I continuously check what are the important things to work on". I do this by reviewing my north star yearly, my Goals (and OKRs) quarterly, and then monthly and weekly make sure I am working on projects that help me to achieve those. This framing facilitates the "emergence" of clear and relevant things to work on my day to day without the "stress" of having to make the plan and deliver the plan (that is continuously changing). This is greatly supported by the PPV: systems that capture your ambitions and goals, and have routines to make sure I am progressing towards them, and based on that I have my "execution plan" emerging automatically.

<form style="border:1px solid #ccc;padding:3px;text-align:center;" action="https://tinyletter.com/tla_insights"
    method="post" target="popupwindow"
    onsubmit="window.open('https://tinyletter.com/tla_insights', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true">
    <p><label for="tlemail">Enter your email to be notified of future TLA_insights records</label></p>
    <p><input type="text" style="width:140px" name="email" id="tlemail" /></p><input type="hidden" value="1"
      name="embed" /><input type="submit" value="Subscribe" />
</form>
