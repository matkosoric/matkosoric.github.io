---
title: "Data Governance: The Definitive Guide"
excerpt_separator: "<!--more-->"
categories:
  - books
tags:
  - data governance
---


##  Evren Eryurek, Uri Gilad, Valliappa Lakshmanan, Anita Kibunguchy-Grant, Jessi Ashdown


![alt text](/images/book_covers/data-governance.jpg "Title"){: width="250" }

<!--more-->

> Holistic or "centralized" data governance may have existed within some organizations, but the majority of companies 
> viewed data governance as departmental concern.
> (Eryurek et al. 2021, 9)

> ...attackers who steal admin credentials from on-premises systems will usually cover  their tracks by modifying 
> the system access logs. On the public cloud, though, these access logs are not modifiable because the attacker
> doesn't have access to them.
> (Eryurek et al. 2021, 18)

> When implemented cohesively, data governance addresses the strategic need to get knowledge workers the insights they 
> require with a clear process to "shop for data". This makes possible the extraction od insights from multiple sources 
> that were previously siloed off within different business units.
> (Eryurek et al. 2021, 23)

> A useful way to share data without exposing too much is to tokenize (encrypt) the data with symmetric (reversible) 
> encryption such that key data values (for example, a person's ID) preserve uniqueness (and thus you can count how
> many distinct persons you have in your dataset) without being exposed to the specific details of a person's ID.
> (Eryurek et al. 2021, 27)

> Gone are the days of simple access controls - i.e., these users/roles get access and these users/roles do not.
> (Eryurek et al. 2021, 75)

> One of the main components of GDPR is the "right to be forgotten", or the ability for a person to request that all 
> their data collected by a company be deleted. If the company does not have its data set up to _find_ all the 
> permutations of a person's individual data, it will struggle to be compliant.
> (Eryurek et al. 2021, 76)

> The first strategy is to keep all uncurated data in an on-prem storage system and to push curated data that can be
> used for analytics to the cloud. ...
> The second strategy is similar to the first in that there is a separation between curated and uncurated data, 
> but this is done within the same cloud environment. Companies will create different layers or zones ... within their 
> cloud environment and base access on these; the bottom, uncurated zone may be accessed by only a few users, while 
> the uppermost zone, curated and cleaned (of sensitive data), may be accessed by any user.
> (Eryurek et al. 2021, 78-79)

> ... segregating data by line of business encourages the siloing of data and can, depending on how it's set up,
> inhibit cross-company analytics.
> (Eryurek et al. 2021, 81)

> When new data is created, that is referred to as data creation, and when existing data is funeled into a system,
> it is referred to as data capture.
> (Eryurek et al. 2021, 87)

> There are probably contracts and agreements that outline how the enterprise is allowed to use this data and for
> what purpose. There might also be limitations as to who can access that specific data.
> (Eryurek et al. 2021, 87)

> ... data becomes truly useful and empowers the organization to make informed business decisions when it can be viewed,
> analyzed, and/or visualized for insights.
> (Eryurek et al. 2021, 88)

> It's important to point out that implementing governance is complicated; there#s no easy way to simply apply 
> everything and consider the job done. Most technologies need to be stiched together, and as you can imagine, they're
> all coming from different vendors with different implementations. You would need to integrate the best-in-class
> suite of products and services to make things work.
> (Eryurek et al. 2021, 92)

> ... metadata management should be considered from the point of data creation - where enterprises need to discover and 
> curate the data as it's ingested (especially sensitive data) - to when data is stored and discovered in the 
> applicable storage system.
> (Eryurek et al. 2021, 93)

> Metadata describes the data, while the lineage describes the _where_ of the data and how it will flow and be 
> transformed and used donwstream.
> (Eryurek et al. 2021, 95)

> A data governance policy allows you to have all the important elements of operationalizing governance documented 
> according to your organization's needs and objectives.
> (Eryurek et al. 2021, 102)

> The success of a data governance program depends on the combination of people, processes, and tools all working
> together to make governance a reality.
> (Eryurek et al. 2021, 106)

> In most cases, metadata does not obey the same policies and controls as the underlying data itself, and a lack 
> of standardized metadata specifications means that the different products and processes will have different
> ways of presenting this information.
> (Eryurek et al. 2021, 109)

> Reconciliation of data meaning can be done by making sure that when a new data source is added, the accuracy, 
> completeness, and timeliness of the data source is examined - sometimes manually - and either described in a way
> that the data analysts using the resource can use or directly normalized according to the rules in the 
> central repository.
> (Eryurek et al. 2021, 114)

> At a minimum, you should prioritize the quality of all sources of critical decision-supporting outputs.
> (Eryurek et al. 2021, 128)

> ... for data quality, handle it early, as close to the data source as possible, and monitor resultant
> products of your data.
> (Eryurek et al. 2021, 131)

> Data governance should not introduce labor by forcing users to register and annotate new data container as they 
> work to reshape and collect data for their needs.
> (Eryurek et al. 2021, 133)

> The metadata information of the data sources ... can support decisions about whether or not to allow certain
> data products to mix, whether or not to allow access to that data and to whom, and so on. When mixing data products,
> you will need to keep track of where the data came from.
> (Eryurek et al. 2021, 135)

> If there is a good job audit log, you can use it to create a lineage graph.
> (Eryurek et al. 2021, 136)

> ... we should strive to present the many technical details (e.g., intermediate procesing tables) to analysts
> while at the same time serving a simplified "business view" to the business users.
> (Eryurek et al. 2021, 142)

> Data protection has to be carried out at multiple levels to provide defense in depth.
> (Eryurek et al. 2021, 143)

> Once the classification is determined and the protection level chosen by cost analysis, the protection level is 
> implemented through two aspects. The first aspect is the provisioning of access to available assets. This can include
> determining the data services what will allow data consumers to access the data. The second aspect is prevention of
> unauthorized access. This is done by defining identities, groups, and roles and assigning access rights to each.
> (Eryurek et al. 2021, 146)

> Clients  within a perimeter that have private access to resources do not have access to unauthorized 
> (potentially public) resources outside the perimeter - this is what limits the data exfiltration risk. Data cannot
> be copied to unauthoried resources outside the perimeter.
> (Eryurek et al. 2021, 156)

> The zero-trust model assumes that an internal network is untrustworthy and builds enterprise applications based
> on the assumption that all network traffic emanates from a zero-trust network, i.e., the public internet.
> (Eryurek et al. 2021, 157)

> Access control encompasses _authentication_, _authorization_, and _auditing_. Authentication determines who you are,
> authorization determines what you can do, and auditing logs record what you did.
> (Eryurek et al. 2021, 158)

> ... if people change jobs, you'll just need to update their membership in the appropriate groups instead of updating
> their access to datasets and projects one dataset or project at a time.
> (Eryurek et al. 2021, 159)

> Where possible, define policies hierarchically.
> (Eryurek et al. 2021, 160)

> A common use of encryption is to delete all records associated with a specific user, often in response to a 
> legal request.
> (Eryurek et al. 2021, 163)

> Monitoring systems need to run independently from production services, and they should not put a burden on a 
> system they are tracking.
> (Eryurek et al. 2021, 188)

> The data culture is the set of values, goals, attitudes, and practices around data, data collection, and data
> handling within a company or organization.
> (Eryurek et al. 2021, 193)

> An efficient data culture aids in ensuring reliable, high-quality data that not only produces better analytics 
> but also reduces compliance violations and penalties.
> (Eryurek et al. 2021, 194)

> All companies are driven by a desire to increase their profitability, whether by increasing revenue and/or 
> by decreasing waste or expenditure. The entire push to data-driven decision making has at its heart the 
> hope and promise of driving revenue.
> (Eryurek et al. 2021, 195)

> Two common facets of focus are _top down_ eommunication of the governance program itself and its practices, 
> standards, and expectations, and _bottom up_ communication encompassing breaches and problems in governance 
> being bubbled up for resolution.
> (Eryurek et al. 2021, 199)

> Without C-level support for a governance program, it's highly likely that the program would fall short due to
> lack of budgetary support and the absence of an ongoing advocacy of a data culture.
> (Eryurek et al. 2021, 200)

> ... there needs to be constant communication back to the decision-making body about what regulations might be 
> coming up and/or whether there are any changes that need to be made to current data handling practices in order
> to be in compliance.
> (Eryurek et al. 2021, 204)


[Data Governance: The Definitive Guide](https://www.oreilly.com/library/view/data-governance-the/9781492063483/)
