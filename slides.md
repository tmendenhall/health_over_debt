---
theme: default
class: text-center
layout: center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: fade-out
title: Tech radar 2023
mdc: true
---

# Tracking Health over Debt

Tech Radar 2023

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->
---
class: text-left
---


# What is it?
Tracking Health over Debt

<v-clicks>

- code test coverage. complexity, paths, lines (shudder) 
- Measurable concerns like SLI (Service level indicators) and (SLO) Service level objectives
- DORA "Devops Research and Assessment"
- Deployment frequency, Lead time for changes, Change failure rate, Time to restore service, Reliability
- Product status <span color="Green">Green</span> <span color="yellow">Yellow</span> <span color="red">Red</span> 


</v-clicks>
<!--
How is a project going? How is the team doing?
-->
---
layout: center
class: text-center
---

# Where did Thoughtworks rank it?

<div v-click class="text-xl">

Trial
 
</div>
 

<!--
New to the radar following the older blip of Platform Engineering.
-->
---
layout: center
class: text-center
---

# Why do we care?

<div v-click class="text-xl">

Development Team Experience!
 
</div>
 

<!--
A deployed capability starts with code but also includes how it is built, tested, deployed, observed, and eventually retired. Tracking the health of the complete capability via a defined rubric would be a welcome counterbalance against the “project” mentality. 
Being able to communicate the long term health of a system including the people responsible for maintaining the capability is important to see that it remains a priority.

-->
---
layout: center
---
# How do we do this?

<v-clicks>

- They didn't actually say... how

</v-clicks>
---
class: text-center
layout: center
---

# Are there competing ways to solve the problem?

<span color="red">Rant</span>

<v-clicks>

Project

Deploy

HYPERCARE

Ignore

Degrade (the world changes around deployed capabilities)

Complain

Patch

Complain

SERIOUS ISSUE

Project

</v-clicks>

<!--


-->
---
layout: center
---
# What was the single referenced article's recommendations

[article](https://www.rea-group.com/about-us/news-and-insights/blog/what-good-software-looks-like-at-rea/)
---
---
# Risks, pitfalls, downsides, and anti-patterns?

<v-clicks>

- Insufficent trust or communication with managment or capability owners to bring up these concerns

- Lack of acknowledgement or resources for ongoing incrementatal change to deliver value and mitigate the eventual SERIOUS ISSUE

 
</v-clicks>
 

<!--

--> 
--- 
layout: center
class: text-center
---

# My Ranking

<v-clicks class="text-xl">

<ul>
<li> Trial </li>
</ul> 
</v-clicks>
 

<!--
Try early and often to build empath and understanding in communicating 
-->
---
---
# Learn More
[Tech Radar for this entry](https://www.thoughtworks.com/radar/techniques/summary/tracking-health-over-debt) ·
[Documentation](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev)
