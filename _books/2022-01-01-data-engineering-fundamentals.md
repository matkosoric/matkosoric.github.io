---
title: "Fundamentals of Data Engineering"
excerpt_separator: "<!--more-->"
categories:
  - books
tags:
  - data engineering
  - data modeling
  - MLOps
  - OLTP
  - OLAP
  - ETL
  - ELT
  - Reverse ETL
  - Data Mesh
  - Data Ops
---


## Joe Reis & Matt Housley

![alt text](/images/book_covers/data_engineering_fundamentals.jpg "Title"){: width="250" }

<!--more-->

Overview of Data engineering field covering typically used skills, activities, workflows, lifecycles,
organizations, and architecture, while abstracting away concrete tools and technologies that might become obsolete soon
and striving for durability.


> Data engineers must know what consumer data they retain and must have procedures to destroy data in response to 
> requests and compliance requirements. (Reis & Housley 2022, 61).

> A data engineer must understand both the technical aspects of building software products and the business logic, 
> quality, and metrics that will create excellent data products. (Reis & Housley 2022, 62).

> Observability, monitoring, logging, alerting, and tracing are all critical to getting ahead of any problems along
> the data engineering lifecycle. (Reis & Housley 2022, 64).

> _Incident response_ is about using the automation and observability capabilities mentioned previously to rapidly
> identify root causes of an incident and resolve it as reliably and quickly as possible. (Reis & Housley 2022, 65).

> A _data warehouse_ is a central data hub used for reporting and analysis. Data in a data warehouse is typically
> highly formatted and structured for analytics use cases. It's among the oldest and most well-established 
> data architectures. (Reis & Housley 2022, 100).

> A _data mart_ is a more refined subset of a warehouse designed to serve analytics and reporting, focused on a single
> suborganization, department, or line of business; every department has its own data mart, specific to its needs. 
> This is in contrast to the full data warehouse that serves the broader organization or business.
> (Reis & Housley 2022, 103).

> The lakehouse incorporates the controls, data management, and data structures found in a data warehouse while still
> housing data in object storage and supporting a variety of query and transformation engines. (Reis & Housley 2022, 105).

> Storing your data in object storage is a wise chice. (Reis & Housley 2022, 125).

> ...we suggest investing in building and customizing _when doing so will provide a competitive advantage_ for
> your business. Otherwise, stand on the shoulders of giants and _use what's already available_ in the market. 
> Given the number of open source and paid services - both of which may have communities of volunteers 
> or highly paid teams of amazing engineers - you're foolish to build everything yourself. (Reis & Housley 2022, 137).

> Whenever possible, lean toward type A behavior; avoid undifferentiated heavy lifting and embrace abstraction. Use 
> open source frameworks, or if this is too much trouble, look at buying a suitable managed or proprietary solution. 
> (Reis & Housley 2022, 137).

> At virtually any large company, data engineers will need to deal with the problem of writing and maintaining 
> custom code to pull data from APIs, which requires understanding the structure of the data as provided, developing 
> appropriate data-extraction code, and determining a suitable data synchronization strategy. (Reis & Housley 2022, 179).

> Whenever possible, work with software engineers to fix data-quality issues at the source. (Reis & Housley 2022, 271).

> Data engineers should take advantage of the best available tools - primarily, managed tools and services that
> do a lot of the heavy lifting for you - and develop high software development competency in areas where it matters.
> (Reis & Housley 2022, 272).

> A common technique for improving query performance is to _prejoin_ data. If you find that analytics queries are
> joining the same data repeatedly, it often makes sense to join the data in advance and have queries read from prejoined 
> version of the data so that you're not repeating computationally intensive work. This may mean changing the schema 
> and relaxing normalization conditions to widen tables and utilize newer data structures (such as arrays or structs) 
> for replacing frequently joined entity relationships. Another strategy is maintaining a more normalized schema but 
> prejoining tables for the most common analytics and data science use cases. (Reis & Housley 2022, 280).

> The goal of normalization is to remove the redundancy of data within a database and ensure referential integrity. 
> Basically, it's _don't repeat yourself_(DRY) applied to data in a database. (Reis & Housley 2022, 294).

> The goal of the data warehouse was to separate the source system from the analytical system. (Reis & Housley 2022, 299).

> Data from key business source systems is ingested and integrated into highly normalized (3NF) data warehouse that
> often closely resembles the normalization structure of the source system. (Reis & Housley 2022, 300). - Inmon warehouse

> In Kimball's approach, data is modeled with two general types of tables: facts and dimensions. (Reis & Housley 2022, 301).

> The first type of table in a star schema is the fact table, which contains _factual_, quantitative, and event-related 
> data. The data in a fact table is immuatable because facts relate to events. Therefore, fact tables don't change 
> and are append-only. Fact tables are typically narrow and long, meaning they have not a lot of columns but a lot of 
> rows that represent events. Fact tables should be at the lowest grain possible. (Reis & Housley 2022, 302).

> Dimensions are denormalized, with the possibility of duplicate data. This is OK in the Kimball data model. (Reis & Housley 2022, 303).

> A dimension that is reused across multiple star schemas, thus sharing the same fields, is called a 
> _conformed dimension_. (Reis & Housley 2022, 305).

> ... in a Data Vault, the business logic is created and interpreted when the data from these tables is queried.
> (Reis & Housley 2022, 309).

> Analytics queries on wide tables often run faster than equivalent queries on highly normalized data requireing many
> joins. Removing joins can have a huge impact on scan performance. (Reis & Housley 2022, 310).

> One of top priorities in query optimizers is join reordering. (Reis & Housley 2022, 315).

> A few top-level things to keep in mind when coding in native Spark:
> 1. Filter early and oftern.
> 2. Rely heavily on the core Spark API, and learn to understand the Spark native way of doing things. Try to rely on well-maintained public libraries if the native Spark API doesn't support your use case. Good Spark code is substantially declarative.
> 3. Be careful with UDFs.
> 4. Consider intermixing SQL. 
> (Reis & Housley 2022, 318).

> _Federated queries_ are a database feature that allows an OLAP database to select from an external data source, such 
> as object storage or RDBMS. (Reis & Housley 2022, 328).

> Transformation inherently creates new datasets that need to be managed. (Reis & Housley 2022, 335).

> As we transform data, _data lineage_ tools become invaluable. Data lineage tools help both data engineers, who must 
> understand previous transformation step as they create new transformations, and analysts, who need to understand where 
> data came from as they run queries and build reports. (Reis & Housley 2022, 335).

> You should run data-quality tests on the input datasets and the transformed dataset, which will ensure that the data 
> meets the expectations of upstream and downstream users. If there#s a data-quality issue in the transformation,
> you should have the abbility to flag the issue, roll back the changes, and investigate the root cause.
> (Reis & Housley 2022, 336)

> Blindly assuming that the tool is generating performant code is a mistake. (Reis & Housley 2022, 338)

> ... a good data engineer will seek to fully understand outcomes for direct users such as data analysts and data 
> scientists or customers external to the company. (Reis & Housley 2022, 344)

> A classic engineering mistake is simply building without understanding the requirements, needs of the end user, or
> product/market fit. (Reis & Housley 2022, 345)

> Serving data from a database carries a varety of benefits. A database imposes order and structure on the data through 
> schema; databases can offer fine-grained permission controls at the table, column, and row level, allowing database 
> administrators to craft complex access policies for various roles; and databases can offer high serving performance
> for large, computationally intensive queries and high query concurrency. (Reis & Housley 2022, 356-356)

> If federated queries touch live production source systems, you must ensure that the federated query won't consume 
> excessive resources in the source. (Reis & Housley 2022, 358)

> Productionized notebooks allow data scientists to get their work into production much faster, but they are also 
> inherently a substandard form of production. (Reis & Housley 2022, 362)

> The best way to protect private and sensitive data is to avoid ingesting this data in the first place.
> (Reis & Housley 2022, 374)

> The _principle of least privilege_ means that a person or system should be given only the privileges and data they need
> to complete the task at hand and nothing more. (Reis & Housley 2022, 376)


[O'Reilly](https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/)

