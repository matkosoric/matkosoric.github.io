---
title: "The Data Warehouse Toolkit"
excerpt_separator: "<!--more-->"
categories:
  - books
tags:
  - data warehouse
  - dimensional modeling
  - ETL
---


## Ralph Kimball & Margy Ross

Classical book on dimensional modeling with detailed case studies in areas such as retail, inventory,
procurement, order management, accounting, customer relationship management, human resources management,
financial services, telecommunications, transportation, education, healthcare, electronic commerce,
and insurance.

![alt text](/images/book_covers/data_warehouse_toolkit.jpg "Title"){: width="250" }

<!--more-->

> Simplicity is the fundamental key that allows users to easily understand databases and software to efficiently
> navigate databases. In many ways, dimensional modeling amounts to holding the fort against assaults on simplicity.
> (Kimball & Ross 2013, xxvii)

> ...the key difference between 3NF and dimensional models is the degree of normalization.
> (Kimball & Ross 2013, 8)

> Instead of third normal form, dimension tables typically are highly denormalized with flattened many-to-one
> relationships within a single dimension table. Because dimension tables typically are geometrically smaller than
> fact tables, improving storage efficiency by normalizing or snowflaking has virtually no impact on the overall
> database size. (Kimball & Ross 2013, 15)

> We insist that the data be presented, stored, and accessed in dimensional schemas, either relational star schemas
> or OLAP cubes. (Kimball & Ross 2013, 21)

> Cryptic abbreviations, true/false flags, and operational indicators should be supplemented in dimensional tables
> with full text words that have meaning when independently viewed. (Kimball & Ross 2013, 48)

> ... you should avoid snowflakes because it is difficult for business users to understand and navigate snowflakes.
> They can also negatively impact query performance. (Kimball & Ross 2013, 50)

> Data integration usually takes the form of conforming dimensions and conforming factrs in the data warehouse.
> (Kimball & Ross 2013, 446)

> We recommend staging the data (writing it to disk) after each major activity of the ETL pipeline.
> (Kimball & Ross 2013, 447)

> Loading records based purely on time is a common mistake made by inexperienced ETL developers. This process
> is horribly unreliable. (Kimball & Ross 2013, 452)

> Referential integrity (RI) means that for each foreign key in the fact table, an entry exists in the corresponding
> dimension table. (Kimball & Ross 2013, 476)

> If there is one lesson we have learned in the data warehouse world, it is not to anchor major entities such as
> customer, product, and time with the natural keys defined by a specific application. (Kimball & Ross 2013, 539)

> ...augment the natural key coming from a source with an enterprise durable surogate key. (Kimball & Ross 2013, 539)


[Kimball Group](https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/books/data-warehouse-dw-toolkit/)

