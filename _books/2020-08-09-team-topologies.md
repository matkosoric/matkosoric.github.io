---
title: "Team Topologies: Organizing Business and Technology Teams for Fast Flow"
excerpt_separator: "<!--more-->"
categories:
  - books
tags:
  - team topologies
  - Conway's law
  - DevOps topologies
---


## Matthew Skelton and Manuel Pais


![alt text](/images/book_covers/team-topologies.jpg "Title"){: width="250" }

<!--more-->

> ...we assume that an organization is a sociotechnical system or ecosystem that is shaped by the interaction of
> individuals and the teams within it; in other words, that an organization is the interaction between people 
> and technology. (Skelton & Pais 2019, xxi)

> ... we assume that "the team" is something that behaves differently from a mere collection of individuals...
> (Skelton & Pais 2019, xxi)

> Business can no longer choose between optimizing for stability and optimizing for speed.
> (Skelton & Pais 2019, 4)

> Systems thinking focuses on optimizing for the whole, looking at the overall flow of work, identifying what the
> largest bottleneck is today, and eliminating it.
> (Skelton & Pais 2019, 5)

> Team Topologies provides four fundamental team types - _stream aligned_, _platform_, _enabling_, and 
> _complicated-subsystem_ - and three core team interaction modes - _collaboration_, _X-as-a-service_, and
> _facilitating_.
> (Skelton & Pais 2019, 9)

> The end goal is to help teams produce software that aligns with customer needs and is easier to build, run, and own.
> (Skelton & Pais 2019, 9)

> The key takeaway here is that thinking of software architecture as a standalone concept that can be designed in
> isolation and then implemented by any group of teams in fundamentally wrong.
> (Skelton & Pais 2019, 10)

> When cognitive load isn't considered, teams are spread thin trying to cover an excessive amount of
> responsibilities and domains.
> (Skelton & Pais 2019, 11)

> We need to put the team first, advocating for restricting their cognitive loads.
> (Skelton & Pais 2019, 12)

> Overall, Team Topologies approach advocates for organization design that optimizes for _flow of change_ and feedback
> from running system.
> (Skelton & Pais 2019, 12)

> ... an organization that is arranged in functional silos (where teams specialize in a particular function, 
> such as QA, DBA, or security) is unlikely to ever produce software systems that are well-architected for end-to-end
> flow. 
> (Skelton & Pais 2019, 17)

> Many organzations assume that more communication is always better, but this is not reall the case. What we need is 
> _focused_ communication between specific teams.
> (Skelton & Pais 2019, 24)

> Conway's law suggests that this kind of many-to-many communication will tend to produce monolithic, tangled,
> highly coupled, interdependent systems that do not support fast flow.
> (Skelton & Pais 2019, 26)

> ... having a special "production only" tool that is limited to teams with security access to production should be
> avoided.
> (Skelton & Pais 2019, 27)

> ... regular reorganizations for the sake of managemet convenience or reducing headcount actively destroy the ability
> of organizations to build and operate software systems effectively.
> (Skelton & Pais 2019, 28)

> Relaying on individuals to comprehend and effectively deal with the volume and nature of information required to 
> build and evolve modern software is not sustainable.
> (Skelton & Pais 2019, 31)

> High trust is what enables a team to innovate and experiment.
> (Skelton & Pais 2019, 32)

> ... patterns and rules that worked at a smaller scale will probably fail to work at a larger scale.
> (Skelton & Pais 2019, 33)

> Every part of the software system needs to be owned by exactly one team. This means there should be no shared
> ownership of components, libraries, or code.
> (Skelton & Pais 2019, 37)

> "Minimize cognitive load for others" is one of the most useful heuristics for good software development.
> (Skelton & Pais 2019, 47)

> Older organizational models - with functional silos between different departments, heavy use of outsourcing, 
> and repeated hand-offs between teams - do not provide the safety at speed of the organizational feedback mechanisms 
> necessary for the ongoing evolution of business services needed to respond to customer and market conditions on
> a daily basis.
> (Skelton & Pais 2019, 63)

> The assumption that the software-development process has little or nothing to learn from how the software runs
> in the live environment is fundamentally flawed.
> (Skelton & Pais 2019, 64)

> ... there needs to be a split between the responsibility of designing the cloud infrastructure process
> (by the cloud team) and the actual provisioning and updates to application resources (by the product teams).
> (Skelton & Pais 2019, 70)

> A stream aligned team is a team aligned to a single, valuable stream of work; this might be a single product or 
> service, a single set of features, a single user journey, or a single user persona. Furhter, the team is empowered
> to build and deliver customer or user value as quickly, safely, and independently as possible, without requiring 
> hand-offs to other teams to perform parts of the work.
> (Skelton & Pais 2019, 81)

> The Amazon two-pizza-team model is an example of stream-aligned teams: the teams are substantially independent, 
> have ownership over their services, and have responsibility for the runtime success of the software they write.
> (Skelton & Pais 2019, 83)

> ...there should not be a permanent dependency on an enabling team.
> (Skelton & Pais 2019, 87)

> A good test for DevEx is how easy it is to onboard a new Developer to the platform.
> (Skelton & Pais 2019, 102)

> A good platform will also serve to reduce the need for security and audit teams to spend time with the Dev team.
> (Skelton & Pais 2019, 104)

> The most effective pattern for an architecture team is as a part-time enabling team (if one is needed at all).
> (Skelton & Pais 2019, 109)

> ...the common belief that open-plan offices increase collaboration has been disputed by a field study...
> (Skelton & Pais 2019, 114)

> A _fracture plane_ is a natural seam in the software system that allows the system to be split easily into
> two or more parts.
> (Skelton & Pais 2019, 115)

> Most of our fracture plane (software responsibility boundaries) should map to business-domain bounded contexts.
> (Skelton & Pais 2019, 115)

> Splitting along the regulatory-compliance fracture plane simplifies auditing and compliance, as well as reduces 
> the blast radius of regulatory oversight.
> (Skelton & Pais 2019, 117)

> Formalizing the ways in which teams should interact when building software systems help to more easily assess the 
> effectiveness of many aspects of software delivery by more explicitly defining interfaces between teams; in turn, 
> it is expected (from Conway's law) that these interfaces will be reflected in the software systems being built.
> (Skelton & Pais 2019, 134)

> Short-term or light-touch occasional collaboration to establish or refine the interfaces is fine, but a need 
> for ongoing colaboration suggests incorrect domain boundaries and/or team responsibilities, or the incorrect
> mix of skills within a team.
> (Skelton & Pais 2019, 137)

> ... platform teams will need strong product- and service-management expertise, whereas enabling teams will need 
> people with strong mentoring and facilitating experience.
> (Skelton & Pais 2019, 145)

> ... collaborate closely to establish viable "as a service" boundaries and then continue with lightweight
> collaboration to validate that the boundaries are effective.
> (Skelton & Pais 2019, 149)

> Simply defining a set of teams with responsibility boundaries is not enough to produce an effective sociotechnical 
> system; it is also necessary to define sensible and effective interactions between teams.
> (Skelton & Pais 2019, 151)

> Organizations should aim to move from discovery activities to establish predictable delivery over time as new 
> commodity services and platforms become available.
> (Skelton & Pais 2019, 162)

> Because the interaction modes are clear and explicit, and because these are mapped to well-defined purposes, 
> people on different teams within the organization understand why they interact in different ways with other teams.
> (Skelton & Pais 2019, 165)

> This reinforcing cycle of specialization is a local optimization ("get this request delivered quickly") that can 
> negatively affect the team's overall flow of work when planning get dictated by "who knows what" rather than
> "that's the highest priority work we need to do now."
> (Skelton & Pais 2019, 166)
 
> Historically, many organizations have treated "develop" and "operate" as two distinct phases of software delivery,
> with very little interaction and certainly almost no feedback from operate to develop. Moders software delivery must
> take a completely different approach: the operation of the software should act as and provide valuable signals to
> the development activities.
> (Skelton & Pais 2019, 170)

> Increasingly, software is less of a "product for" and more of an "ongoing eonversation with" users.
> (Skelton & Pais 2019, 173)

> To generate and receive high-fidelity information from frontline, opeartional systems,
> highly skilled, highly aware people are needed.
> (Skelton & Pais 2019, 174)
 

[Book link](https://www.amazon.de/-/en/Alex-Xu/dp/B08CMF2CQF)
