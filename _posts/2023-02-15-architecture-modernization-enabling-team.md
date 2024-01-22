---
layout: post
title:  "Architecture Modernization Enabling Teams (AMET)"
---

> _I co-authored this article with [Nick Tune](https://nick-tune.me/) ([article on Nick's blog](https://medium.com/nick-tune-tech-strategy-blog/architecture-modernization-enabling-teams-amet-23a7f867b284)) based on our individual experiences and experiences and learnings from working together with clients. It touches on several topics we are actively writing, developing, and [consulting](/consulting) on, in particular: [Architecture Modernization](https://www.empathysoft.co.uk), [Team Topologies - Enabling Teams](/enabling-teams), and [Architecture Topologies](/architecture-topologies) (AMET is an example of an architecture topologies' pattern that we are observing as very effective to help approaching architecture modernization initiatives and architecture practices in an organization). We are going to be exploring this and related topics in future writings._

<br>
<div align="center"><a href="/assets/amet.jg"><img src="/assets/amet.jpg" alt="AMET" width="80%"/></a></div>
<br>

This article describes a pattern we have observed and applied in multi-team-scope architecture modernization initiatives, the *Architecture Modernization Enabling Team* (AMET). An AMET is a type of architecture [enabling team](https://teamtopologies.com/key-concepts) that coordinates and upskills all teams and stakeholders in the modernization initiative.

We observe that effective AMETs have six primary purposes, which address six recurrent modernization challenges:

<br>
<div align="center"><a href="/assets/amet-challenges-purposes.png"><img src="/assets/amet-challenges-purposes.png" alt="AMET Purposes" width="100%"/></a></div>
<br>

> **What is architecture modernization?**
> 
> 
> *When architecture ages without proper care, it becomes more and more of a liability and competitive disadvantage. It is slower and harder to change, increasing costs and time-to-market. It becomes outdated based on older technologies, architectural patterns, and outdated assumptions about the business and its environment. This increases the level of technical debt and makes it more fragile. For example, security concerns and unreliability becoming commonplace, like the recent Southwest Airlines [scheduling crisis](https://www.wsj.com/articles/southwests-december-meltdown-to-cause-quarterly-loss-11673007141?mod=article_inline) caused by a decades-old scheduling system.*
> 
> *Architecture modernization initiatives aim to convert aging architecture into modern architecture, applying the latest tech innovations and architectural patterns. What was a competitive disadvantage becomes a competitive advantage. The architecture becomes easier and cheaper to change, enabling faster flow, and reducing technical debt, fragility and security concerns.*
> 
> *To take full advantage of modernized architecture, it’s also necessary to modernize architectural practices and ways of working. When done right, this essential aspect enables modernization to be a continuous, value-driven activity in the organization, as opposed to complex multi-year initiatives with heavy up-front planning.*
> 

# **When to establish an AMET**

When architecture inhibits strategic business objectives, architecture modernization is necessary. In these scenarios, an AMET is likely to be a vital investment due to the previously outlined challenges. A typical example is large legacy monoliths that have accumulated [cruft](https://martinfowler.com/articles/is-quality-worth-cost.html) and are hard and slow to change, from numerous perspectives and concerns, by the many teams working on them. When the business need arises for faster innovation, e.g., faster-moving competitors, the brittle architecture becomes a bottleneck.

This was the case with a large, historical, North European market leader we worked with. The organization’s top-level strategic objective was to double revenue in five years. Ambitious for a 100+-year-old company in their industry, but not impossible. New innovations, driven by tech and the move to renewables, were opening up the ecosystem to major new revenue streams.

We supported technology leaders and teams in one business area that was seen as having potential for substantial growth. There was enormous potential to address existing user needs more effectively and capitalize on sizeable market opportunities by addressing unmet user needs. But it would be essential to up the tempo of development velocity to exploit the opportunity.

Due to the evolution in their ecosystem, it would also be crucial to externalize individual capabilities locked away in the monolith so that the company’s products could be integrated with industry marketplaces and platforms.

Both of these ambitions unequivocally necessitated the modernization of architecture. The purpose was to create a loosely coupled architecture enabling teams to work independently and collectively with a fast flow of changes. In addition, this would also allow more granular build vs. buy vs. partner decisions (this was highly desirable). Getting there, however, would not be straightforward. There were many strategic questions about where to start, and the teams needed more time to switch instantly from a stable BAU mindset to all-out modernization. Learning, upskilling, and patience was necessary.

In summary, modernization was essential for the company to achieve its strategy in a competitive landscape. Kickstarting the initiative, maintaining momentum, upskilling teams, and laying other foundations for sustainable fast flow over many years were crucial to achieving the vision. These are clear-cut signs that an AMET could be an essential investment.

# **AMET investment and involvement**

An AMET is a temporary team whose existence is a function of the modernization ability in the organization. In particular, improving the architectural capability around the scope that is being modernized to address a particular business problem. The following diagram depicts the typical pattern for an AMET’s investment and involvement in a modernization initiative. In brief: the more an AMET helps to upskill the organization, the less it becomes needed.

<br>
<div align="center"><a href="/assets/amet-investment-involvement.jpg"><img src="/assets/amet-investment-involvement.jpg" alt="AMET investmetn and involvement" width="100%"/></a></div>
<br>

As we can observe, the investment and involvement of the AMET tend to follow a bell curve, where there is increasing investment and involvement of the AMET in the modernization initiative to facilitate the necessary design and upskilling needed to improve the architectural capability. Once the organization, particularly the teams involved, reach a certain architectural capability, they can drive more of the architecture modernization initiative. At that stage, the AMET can start downsizing and shifting its involvement towards different activities and eventually stop (even if the initiative is not yet finished).

# **Modernization initiative phases and typical AMET activities**

This section uses a common architecture modernization scenario we are often asked to support: the modernization of a monolithic legacy application. This example demonstrates the usual phases of an architecture modernization initiative and typical AMET activities.

<br>
<div align="center"><a href="/assets/amet-in-a-nutshell.jpg"><img src="/assets/amet-in-a-nutshell.jpg" alt="AMET in a nutshell" width="100%"/></a></div>
<br>

# **Business Problems**

As discussed earlier, in “When to establish an AMET”, architecture modernization should happen to address a business problem. In the example we share, this would be a monolithic application that does not allow the flexibility and fast flow of innovation the business needs. That becomes a trigger for an architecture modernization initiative.

This is when an initial group of people is identified to kickstart the AMET. The AMET members may change — like any other team “reteaming”, as we learn whether certain skills are needed.

At this stage, the initial AMET members tend to be people with familiarity with the problem at hand and ideally have multiple perspectives and disciplines involved. For example, in our case of the modernization of a monolith, it may be good to have business, product, and technical people involved so that they can help shape the activities necessary for the architecture modernization initiative.

# **Kickstarting Modernization**

During the kickstarting of the modernization initiative, an AMET’s primary focus is understanding the important aspects to be considered in the initiative, like business outcomes and technology challenges, and creating alignment between the people involved. An AMET is also focused on establishing concrete next steps. To achieve these aims, we see two typical activities:

- **AMET meets with different stakeholders** (teams, business, product, etc.) relevant to understanding and scoping the initiative. In particular, to ensure that the initiative is connected with the business value modernization will unlock. These sessions are about learning and maximizing the information available to decide how best to proceed. They are also a vital step toward defining the *Kickstarter workshop*.
- **AMET designs and facilitates the *Kickstarter Workshop***. We recommend this to be a three-or-more-day workshop where the AMET gathers with relevant stakeholders (business, product, technology, etc.). The workshop addresses open questions, like defining a clear North Star and the first steps of modernization. In addition, another essential goal of this workshop is to create trust, excitement, and momentum around this initiative. This is fundamental to having a successful kickstart.

> As consultants, we are often called in at the kickstarting stage because this is where organizations struggle the most. We feel most effective acting as Enabling Team so that organizations don’t become dependent on us and develop the capabilities in-house. For this to work, it’s crucial that the AMET includes employees so that knowledge and skills transfer can occur and they can drive the required change. We advise against AMETs that are fully staffed with external consultants.
> 

In this kickstarting phase, the AMET will look at shaping some first steps that deliver modernization in a short time frame, typically 3–6 months. They will steer the group away from too much up-front design and planning toward delivering and learning in this shorter time frame. The team also ensures that modernization is prioritized sufficiently and focus is given to proceed with the initiative. This is what kickstarting means.

Delivering an initial slice of modernization in the short term is a great way to give a glimpse into the value of modernization and, perhaps more importantly, to show people what is possible and start building momentum. When you deliver even just a small slice of modernization, people start to believe that this is more than just talk and that improvements really are coming. It builds excitement and trust. Leadership has demonstrated they are willing to invest, and product and tech have shown they can deliver.

# **Executing Modernization**

An AMET’s responsibility is to keep modernization high on the agenda. Kickstarting modernization sparks excitement and starts showing what is possible. It’s important that the AMET helps sustain that momentum with whatever activities are necessary for the teams involved. In addition, an AMET will address issues that affect the momentum, like teams getting pulled back into too much BAU work.

In brief, they ensure that teams know their next step and are equipped to take it. Achieving this encompasses different types of activities, for example:

- Facilitating design workshops with the multiple teams involved.
- Assist in staffing existing teams, or take the lead on creating new teams.
- Facilitating the planning and a continuous learning feedback loop informing and prioritizing the initiative’s next steps. These maximize learning across all the involved teams and informs how to best move forward in the initiative.
- Informing leadership of potential changes or needs in terms of budget or maybe complementary initiatives that need to happen.
- Facilitating learning and upskilling of teams involved in the initiative. An AMET will ensure that support is in place to help teams on unfamiliar topics (e.g., create a workshop on a particular technology that teams need to learn). This enables teams to achieve a faster flow of change, accelerating their journey to upskill on that essential skill. The ability to make sure teams can implement the necessary changes and then be able to own their scope of work sustainably is one of the critical purposes of the AMET to enable long-lasting, durable change.
- Communicating progress and learnings from the initiative to the broader organization. The goal is to ensure that progress and learning are shared with the broader organization. By doing so, the modernization initiative addresses its challenges and ensures all those learnings are ingrained in other parts of the organization, which can better respond to similar challenges in the future. This improves the overall modernization architectural capability of the organization.

It is important to acknowledge that an AMET is not responsible for mandating and throwing work to teams. It is about facilitating the overall activities needed by the teams involved in the initiative to be successful. Remember, as shown in the AMET lifecycle, an AMET should eventually decrease their participation by empowering the teams themselves to conduct these activities.

# **Completing Modernization**

A modernization initiative isn’t generally a project with a well-defined end-state. It’s more of a theme until architecture is no longer a major blocker to business objectives. However, an AMET should start to wind down when the AMET’s modernization targets are no longer relevant like sufficient modernization being delivered or long-lasting, durable change has been achieved.

During this phase, an AMET’s main focus will be ensuring that long-lasting, durable change has truly been achieved. For example, attending and observing sessions without organizing or facilitating them, and one-to-one coaching sessions. Furthermore, the AMET may also spend time on making sure that the learnings from the modernization efforts are benefiting other parts of the organization.

# **AMET good practices**

The following is a selection of good practices we have observed for creating effective AMETs.

**Naming** Don’t call it “The AMET”. AMET is the pattern. Call the team with a name that makes sense for the modernization initiative. For example: “XYZ Monolith Modernization Enabling Team”.

**Right people** Make sure the AMET has diverse representation, from skills, disciplines, and domain knowledge. They should be able to facilitate the initiative and understand and help trigger different activities (upskilling, communicating with people involved and the wider organization, discussing challenges with executives, etc.)

**Elastic leadership** An AMET may need to take the lead on some initiative activities. However, as an Enabling Team, their goal is to primarily focus on facilitating so that the people and teams involved have the right conditions to lead and drive change themselves. This means it is essential for the AMET to understand when to step back and focus on facilitating instead of leading.

An anti-pattern is an AMET that does the work and makes the decisions. They have effectively become a centralized architecture team at that point.

**Working with diverse stakeholders** Work with all the different stakeholders and people relevant to make the initiative successful. This may require the AMET to have a diverse toolbox of techniques (e.g., Wardley Mapping, Event Storming, Impact Mapping, C4 Model, Team Topologies, etc.). That should allow for more effective discussions and ensure everyone can contribute and is aware of the initiative’s progress.

**Enabling > Architecture** Although we use the word “Architecture” in the name of the AMET pattern, it is essential to note that this is not a team of architects. We recommend teams primarily focus on “Enabling” aspects. Highlight that on the name of the team.

**Communicate and facilitate organizational learning** AMET should focus on communicating things and facilitating learning in the initiative and the organization. By doing this, the AMET helps the initiative to succeed and supports the broader organization to learn from the initiative. This can be made happen in different forms, for example, Request-For-Comments (RFCs) around significant design changes (where anyone can share input), regular progress meetings (where anyone can join and see the latest developments on the initiative), etc.

**Don’t create an AMET if you don’t need one** In time organizations become more able to cope with continuous architecture modernization. As such, if the organization can handle that modernization, there is no need to create an AMET. Creating an AMET may be counterproductive since teams can self-organize to drive modernization efforts.

<div style="border:1px dotted black; padding:1em; background-color: beige">
    <h3><b>ℹ️ I offer consulting services and products on this topic</b></h3>
    <p>If you are looking for help on these topics feel free to <a href="mailto:eduardo@esilva.net">contacting me</a>, and/or check my <a href="/consulting">consulting</a> and <a href="/products">products</a> pages for more details on how I may be of help.</p>
</div>
<br>
