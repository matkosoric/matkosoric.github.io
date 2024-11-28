---
title: "Functional Data Engineering"
hidden: true
categories:
  - blogs
tags:
  - Functional data engineering
  - Reproducibility
  - ETL
  - partition
---


Maxime Beauchemin, creator of Airflow, advocating application of functional programming principles to data engineering.


> To put it simply, immutable data along with versioned logic are key to reproducibility.

> A pure task should always fully overwrite a partition as its output.

> Now that storage and compute are dirt cheap compared to engineering time, snapshoting dimensions make sense in most
> cases. While the traditional type-2 slowly changing dimension approach is conceptually sound and may be more
> computationally efficient overall, it’s cumbersome to manage. The processes around this approach, like managing
> surrogate keys on dimensions and performing surrogate key lookup when loading facts, are error-prone,
> full of mutations and hardly reproducible.

> ... we move away from individual rows or cells being the “atomic state” that can be mutated to a place where
> partitions are the smallest unit that can be changed by tasks.

> ... it’s a good practice to avoid modeling using past-dependencies whenever possible.

> Data is larger, read-optimized stores are typically built on top of immutable blocks,
> we’ve seen the rise of distributed systems, and the number and proportion of people
> partaking in the “analytics process” has exploded.

[Functional Data Engineering](https://maximebeauchemin.medium.com/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a)




