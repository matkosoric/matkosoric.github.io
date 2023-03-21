---
title: "The DevOps Handbook"
excerpt_separator: "<!--more-->"
categories:
  - books
tags:
  - DevOps
  - Agile
  - 
---


## Gene Kim, Jez Humble, Patrick Debois, John Willis & Nicole Forsgren

![alt text](/images/book_covers/devops_handbook.jpg "Title"){: width="250" }

<!--more-->

Concentrated DevOps culture guidebook.

> Analogous to financial debt, technical debt describes how decisions we make lead to problems that get increasingly
> more difficult to fix over time, continually reducing our available options in the future - even when taken on
> judiciously, we still incur interest. (Kim, Humble, Debois & Willis 2021, xxxii-xxxiii)

> Our goal is to decrease the amount of time required for changes to be deployed into production and to increase the
> reliability and quality of those services. (Kim, Humble, Debois & Willis 2021, 19)

> Even under the best circumstances, some knowledge is inevitably lost with each handoff.
> (Kim, Humble, Debois & Willis 2021, 25)

> ... our goal is to create fast feedback and feedforward loops whereever work is performed, at all stages of the
> technology value stream, encompassing Product Management, Development, QA, Infosec, and Operations. This includes
> the creation of automated build, integration, and test processes so that we can immediately detect when a change
> has been introduced that takes us out of a correctly functioning and deployable state.
> (Kim, Humble, Debois & Willis 2021, 35)

> When we work within a complex system, by definition it is impossible for us to perfectly predict all the outcomes
> for any action we take. (Kim, Humble, Debois & Willis 2021, 46)

> Organizations that struggle with financial debt only make interest payments and never reduce the loan principal,
> and they may eventually find themselves in situations where they can no longer service the interes payments. Similarly,
> organizations that don't pay down technical debt can find themselves so burdened with daily workarounds for problems
> left unfixed that they can no longer complete new work. In other words, they are now only making the interest
> payment on their technical debt. (Kim, Humble, Debois & Willis 2021, 89)

> ... how we organize our teams has a powerful effect on the software we produce, as well as our resulting
> architectural and production outcomes. (Kim, Humble, Debois & Willis 2021, 97)

> When every team expedites their work, the net result is that every project ends up moving at the same slow crawl.
> (Kim, Humble, Debois & Willis 2021, 101)

> In high-performance organizations, everyone within team shares a common goal - quality, availability, and security
> aren't the responsibility of individual departments but are part of everyone's job every day.
> (Kim, Humble, Debois & Willis 2021, 104)

> Continuous delivery includes creating the foundations of our automated deployment pipeline, ensuring that we have 
> automated tests that constantly validate that we are in a deployable state, having developers integrate their code
> into trunk daily, and architecturing our environment and code to enable low-risk releases.
> (Kim, Humble, Debois & Willis 2021, 133)

> ... we will only accept development work as done when it can be successfully built, deployed, and confirmed that it
> runs as expected in a production-like environment, instead of merely when a developer believes it to be done.
> (Kim, Humble, Debois & Willis 2021, 145)

> Our goal is to find as many code errors through our automated test suites, reducing our reliance on manual testing.
> (Kim, Humble, Debois & Willis 2021, 160)

> Our goal is to write and run automated performance tests that validate our performance across the entire application
> stack (code, database, storage, network, virtualization, etc.) as part of the deployment pipeline, so we detect
> problems early, when the fixes are cheapest and fastest. (Kim, Humble, Debois & Willis 2021, 162)

> ... significant problems result when developers work in long-lived private branches (also known as 'feature branches'),
> only merging back into trunk sporadically, resulting in a large batch-size of changes.
> (Kim, Humble, Debois & Willis 2021, 170)

> By keeping our code in a deployable state, we are able to eliminate the common practice of having a separate test and
> stabilization phase at the end of the project. (Kim, Humble, Debois & Willis 2021, 172)

> Developers' ability to self-deploy code into production, to quickly see happy customers when their feature works,
> and to quickly fix any issues without having to open up a ticket with Operations has deminished over the last decade - 
> in part as result od a need for control and oversight, perhaps driven by security and compliance requirements. The
> resulting common practice is for Operations to perform code deployments because this is a common implementation of 
> separation of duties, a widely accepted practice to reduce the risk of production outages and fraud, which requires 
> that no one person has end-to-end control over a process, such as software delivery.
> (Kim, Humble, Debois & Willis 2021, 184)

> To better enable fast flow, we want a code promotion process that can be performed by either Development or
> Operations, ideally without any manual steps or handoffs. (Kim, Humble, Debois & Willis 2021, 183)

> The primary way we enable application-based release patterns is by implementing feature toggles (also called feature
> flags), which provide us with the mechanism to selectively enable and disable  features without requiring a production
> code deployment. Feature toggles can also control which features are visible and available to specific user segments
> (e.g., internal employees, segments of customers). (Kim, Humble, Debois & Willis 2021, 195-196)

> The strangler fig application pattern is especially useful for helping migrate portions of a monolithic application
> or tightly coupled services to one that is more loosely coupled. (Kim, Humble, Debois & Willis 2021, 208)

> By repeatedly decoupling functionality from our existing tightly coupled system, we move our work into a safe and 
> vibrant ecosystem where developers can be far more productive, resulting in the legacy application shrinking in
> functionality. It might even disappear entirely as all the needed functionality migrates to our new architecture.
> (Kim, Humble, Debois & Willis 2021, 214)

> High performers used disciplined approach to solving problems, using production telemetry to understand possible
> contributing factors to focus their problem solving, as opposed to lower performers who would blindly reboot
> servers. (Kim, Humble, Debois & Willis 2021, 225)

> In order to see all problems as they occur, we must design and develop our applications and environments so that they
> generate sufficient telemetry, allowing us to understand how our system is behaving as a whole. When all levels of
> our application stack have monitoring and logging, we enable other important capabilities, such as graphing and 
> visualizing our metrics, anomaly detection, proactive alerting and escalation, etc.
> (Kim, Humble, Debois & Willis 2021, 228)

> By making telemetry fast, easy to get, and sufficiently centralized, everyone in the value stream can share a common
> view of reality. (Kim, Humble, Debois & Willis 2021, 236)

> More exotic filtering techniques exist, such as fast Fourier transforms, which has been widely used in image
> processing, and the Kolmogorov-Smirnov test (found in Graphite and Grafana), which is often used to find similarities
> or differences in periodic/seasonal metric data. (Kim, Humble, Debois & Willis 2021, 254)

> ... we should never consider our code deployment or production change to be done until it is operating as designed in 
> the production environment. (Kim, Humble, Debois & Willis 2021, 261)

> Traditionally, when we review changes for deployment, we tend to rely heavily on reviews, inspections, and approvals
> just prior to deployment. Frequently, those approvals are given by external teams who are often too far removed from
> the work to make informed decisions on whether a change is risky or not, and the time required to get all the
> necessary approvals also lengthens our change lead times. (Kim, Humble, Debois & Willis 2021, 281)

> Creating the conditions that enable change implementations to fully own the quality of their changes is an 
> essential part of the high-trust, generative culture we are striving to build. 
> (Kim, Humble, Debois & Willis 2021, 298)

> ... it is not acceptable to have countermeasures to merely "be more careful" or "be less stupid" - instead, we must
> design real countermeasures to prevent there errors from happening again.
> (Kim, Humble, Debois & Willis 2021, 310)

> When we work within complex systems, this need to amplify weak failure signals is critical to averting 
> catastrophic failures. (Kim, Humble, Debois & Willis 2021, 313)

> Our goal for game day is to help teams simulate and rehears accidents to give them the ability to practice. First,
> we schedule a catastrophic event, such as the simulated destruction of an entire data center, to happen at some
> point in the future. We then give teams time to prepare, to eliminate all the single points of failure, and to
> create the necessary monitoring procedures, failover procedures, etc. (Kim, Humble, Debois & Willis 2021, 317)

> Implementing these non-functional requirements will enable our services to be easy to deploy and keep running in
> production, where we can quickly detect and correct problems and ensure they degrade gracefully when components
> fail. Examples of non-functional requirements include ensuring that we have:
> 
> \* sufficient production telemetry in our applications and environments
> \* the ability to accurately track dependencies
> \* services that are resilient and degrade gracefully
> \* forward and backward compatibility between versions
> \* the ability to archive data to manage the size of the production data set
> \* the ability to easily search and understand log messages across services
> \* the ability to trace requests from users through multiple services
> \* simple, centralized runtime configuration using feature flags, etc.
> (Kim, Humble, Debois & Willis 2021, 328)

> ... we schedule rituals that help enforce the practice of reserving Dev and Ops time for improvement work, such as
> non-functional requirements, automation, etc. One of the easiest ways to do this is to schedule and conduct day- or
> week-long improvement blitzes, where everyone on a team (or in the entire organization) self-organizes to fix 
> problems they care about - no feature work is allowed. (Kim, Humble, Debois & Willis 2021, 336)

> Instead of injecting security into our product at the end of the process, we will create and integrate security
> controls into the daily work of Development and Operations, so that security is part of everyone's job every day.
> (Kim, Humble, Debois & Willis 2021, 351)

> ... unit tests may contain malicious code that allows or enables unauthorized access. 
> (Kim, Humble, Debois & Willis 2021, 375)

> The traditional approach to implementing separation of duty can often impede this by slowing down and reducing the
> feedback engineers receive on their work. THis prevents engineers from taking full responsibility for the quality of
> their work and reduces a firm's ability to create organizational learning.
> (Kim, Humble, Debois & Willis 2021, 385)

> ... DevOps is not just a technology imperative but an organizational imperative.
> (Kim, Humble, Debois & Willis 2021, 398)

> Lean principles focus on creating value for the customer - thinking systematically, creating constancy of purpose,
> embracing scientific thinking, creating flow and pull (versus push), assuring quality at the source, leading with
> humility, and respecting every individual. (Kim, Humble, Debois & Willis 2021, 409)


[ITRevolution](https://itrevolution.com/product/the-devops-handbook-second-edition/)

