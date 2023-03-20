---
title: "Lessons Netflix Learned from the AWS Outage"
hidden: true
categories:
  - blogs
tags:
  - Netflix
  - best practice
  - AWS
  - resilience
  - graceful degradation
  - disaster recovery
---


Article by Adrian Cockroft, Cory Hicks, and Greg Orzell from Netflix and its resiliency.
Here are a couple of important points:

> Our systems are designed for failure. With that in mind we have put a lot of thought into what we do when (not if)
> a component fails. The general principles are:
> 
> Fail Fast: Set aggressive timeouts such that failing components don’t make the entire system crawl to a halt.
> 
> Fallbacks: Each feature is designed to degrade or fall back to a lower quality representation. For example if we
> cannot generate personalized rows of movies for a user we will fall back to cached (stale) or un-personalized results.
> 
> Feature Removal: If a feature is non-critical then if it’s slow we may remove the feature from any given page to
> prevent it from impacting the member experience.


> When provisioning capacity, we use AWS reserved instances in every zone, and reserve more than we actually use, so
> that we will have guaranteed capacity to allocate if any one zone fails. As a result we have higher confidence that
> the other zones are able to grow to pick up the excess load from a zone that is not functioning properly. This does
> cost money (reservations are for one to three years with an advance payment) however, this is money well spent since 
> it makes our systems more resilient to failures.

> Services should automatically recover without any manual intervention.



[Lessons Netflix Learned from the AWS Outage](https://netflixtechblog.com/lessons-netflix-learned-from-the-aws-outage-deefe5fd0c04/)
