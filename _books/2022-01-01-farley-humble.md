---
title: "Continuous Delivery"
excerpt_separator: "<!--more-->"
categories:
  - books
tags:
  - DevOps
  - testing
  - CICD
  - git
---


## Jez Humble and David Farley


![alt text](/images/book_covers/continuous_delivery.jpg "Title"){: width="250" }

<!--more-->

> A deployment pipeline is, in essence, an automated implementation of your application's build, deploy, test,
> and release process. (Humble & Farley 2011, 3)

> There should be two tasks for a human being to perform to deploy software into a development, test, or
> production environment: to pick the version and environment and to press the "deploy" button.
> (Humble & Farley 2011, 5-6)

> A production environment should be completely locked down. It should not be possible for *anybody* to
> make a change to it without going through your organization's change management process. 
> (Humble & Farley 2011, 53)

> Unit test should not involve calling the database, using the filesystem, talking to external systems, or,
> in general, interaction between components of a system. (Humble & Farley 2011, 89)

> Software development is a naturally iterative process that thrives on the establishment of effective
> feedback loops, and we deceive ourselves if we perceive it any other way. (Humble & Farley 2011, 89)

> ... a deployment pipeline is an automated manifestation of your process for getting software from 
> version control into the hands of your users. (Humble & Farley 2011, 106)

> The binaries that get deployed into production should be exactly the same as those that went through
> the acceptance test process ... (Humble & Farley 2011, 114)

> Ultimately, you should only need to specify the target environment and the version of the application
> to initiate a successful deployment. (Humble & Farley 2011, 116)

> With automated deployment and release, the process of delivery becomes democratized. (Humble & Farley 2011, 130)

> It should be possible to deploy a single change to production through the deployment pipeline with the
> minimum possible time and ceremony. (Humble & Farley 2011, 131)

> Acceptance tests fall into two types: functional and nonfunctional. (Humble & Farley 2011, 136)

> Your deployment process should always leave the target environment in the same (correct)
> state, regardless of the state it finds it in when starting a deployment. (Humble & Farley 2011, 155) 

> Errors are the easiest to fix if they are detected early, close to the point where they were introduced.
> (Humble & Farley 2011, 171)

> ... running unit tests shouldn't touch the filesystem, databases, libraries, frameworks,
> or external systems. (Humble & Farley 2011, 178)

> This is the essential difference between mocking and stubbing - with stubs, we don't care about how the stub is
> called; with mocks, we can verify that our code interacted with the mocks in the way we expected.
> (Humble & Farley 2011, 181-182)

> The objective of acceptance tests is to prove that our application does what the customer meant it to,
> not that it works the way its programmers think it should. (Humble & Farley 2011, 188)

> The ideal test should be atomic. (Humble & Farley 2011, 205)

> ...*performance* is a measure of the time taken to process a single transaction, and can be measured either in 
> isolation or under load. *Throughput* is the number of transactions a system can process in a given timespan. 
> It is always limited  by some bottleneck in the system. The maximum throughput a system can sustain, for a given
> workload, while maintaining an acceptable response time for each individual request, is its *capacity*. 
> (Humble & Farley 2011, 225)

> ... while in an ideal world everyone wants their systems to be highly secure, very high-performance, massively 
> scalable, massively flexible, extremely scalable, easy to use, easy to support, and simple to develop and 
> maintain, in reality every one of these characteristics comes at a cost. (Humble & Farley 2011, 227)

> For seriously high-capacity and high-performance systems, the highest performance part of the whole system is, 
> necessarily, the test, not the production code. (Humble & Farley 2011, 243)

> In every system, there comes a moment when a critical defect is discovered and has to be fixed as soon as
> possible. In this situation, the most important thing to bear in mind is: Do not, under any circumstances, 
> subvert your process. (Humble & Farley 2011, 265)

> Deployment pipelines are all about creating a repeatable, reliable, automated system for getting changes into
> production as fast as possible. (Humble & Farley 2011, 267)

> Production environments should be completely locked down, so that only your deployment pipeline can make
> changes to it. (Humble & Farley 2011, 273)

> ... development teams are incentivized to deliver software as rapidly as possible, whereas operations teams 
> aim for stability. (Humble & Farley 2011, 279)

> The deployment system forms an integral part of the application - it should be tested and refactored with the same
> care and attention as the rest of the application, and kept in version control. (Humble & Farley 2011, 283)

> ... the success of a project can often turn on its ability to be deployed cleanly and reliably. In our view,
> no technology cann be considered genuinely enterprise-ready unless it is capable of being deployed and configured
> in an automated way (Humble & Farley 2011, 297)

>

[Book link](https://martinfowler.com/books/continuousDelivery.html)

