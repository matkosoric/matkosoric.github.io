---
title: "Genomics ETL"
excerpt_separator: "<!--more-->"
categories:
  - DevOps & Data engineering demo
tags:
  - Azure
  - Databricks
  - Terraform
  - DevOps
  - CICD
  - Infrastructure as code
---

This is a demo data engineering project built on Azure cloud. ETL pipeline implemented in Azure Data Factory is
ingesting and transforming  [Illumina Platinum Genomes dataset](https://learn.microsoft.com/en-us/azure/open-datasets/dataset-illumina-platinum-genomes?tabs=azure-storage).
Terraform is used for provisioning infrastructure.
Deployment pipelines are implemented in GitHub actions in accordance with
[official Microsoft guidelines](https://learn.microsoft.com/en-us/azure/data-factory/continuous-integration-delivery),
with working CICD process between DEV and PROD environments. DEV ADF is connected to git repository, and ARM templates
are propagated to PROD environment through GitHub action.


![alt text](/images/posts/genomics-etl-1.PNG "Title"){: width="600" }

<!--more-->

![alt text](/images/posts/genomics-etl-2.PNG "Title"){: width="600" }

![alt text](/images/posts/genomics-etl-3.PNG "Title"){: width="600" }

![alt text](/images/posts/genomics-etl-4.PNG "Title"){: width="600" }

![alt text](/images/posts/genomics-etl-5.PNG "Title"){: width="600" }


### Created With

* [Terraform](https://www.terraform.io/) - Infrastructure automation tool
* [Databricks](https://databricks.com/) - Web-based processing platform for Spark
* [GitHub Actions](https://docs.github.com/en/actions) - CICD tool
* [Azure](https://portal.azure.com/) - Cloud computing service owned by Microsoft
