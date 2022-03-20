---
title: "Questions and answers portal on Spanish - nuestras-preguntas.net"
excerpt_separator: "<!--more-->"
categories:
  - Applications in production
tags:
  - Spring-boot
  - Elasticsearch
  - nginx
  - docker
  - docker-compose
  - digital ocean
  - Jenkins
  - AES
  - Thymeleaf
---

**www.nuestras-preguntas.net** was my demo project for questions and answers platform on Spanish language with full text search capability.
Application was completely configurable, so switch to another language could be easily accomplished by providing translation for existing fields.
It was running in production for nine months, with two million question and answer pairs.
CICD pipeline was built in Jenkins, and application was running in Docker container on Digital Ocean hosting service.
Whole system had four containers: SpringBoot application, ElasticSearch database, LetsEncrypt certbot, and Nginx proxy.
They were orchestrated with Docker compose.
VM instance had 8GB of RAM, and ElasticSearch was by far the largest consumer of resources.
My architectural decisions were mainly guided by cost reduction, and comparable cloud solutions would be orders of magnitude more expensive.

Applications unique feature was anonymous usage,
meaning registration with email was not necessary to submit a question or answer, or vote.
I developed a custom encryption protocol mostly based on AES algorithm so traffic between client and server could not be reverse-engineered and automated.
To defend against abuse, there were also throttling services and honey-pot traps against bots.
Anti-scraping mechanisms included rotating HTML schema (without an effect on user experience or functionality),
in combination with detection of unusually high amount of requests that triggered responses with poisoned content.


![alt text](/images/posts/nuestras-preguntas-1.PNG "Title"){: width="600" }

![alt text](/images/posts/nuestras-preguntas-2.PNG "Title"){: width="600" }

![alt text](/images/posts/nuestras-preguntas-3.PNG "Title"){: width="600" }

![alt text](/images/posts/nuestras-preguntas-4.PNG "Title"){: width="600" }

<!--more-->

### Created With

* [Spring Boot](https://spring.io/projects/spring-boot)
* [ElasticSearch](https://www.elastic.co/)
* [CertBot](https://hub.docker.com/r/certbot/certbot/)
* [Nginx](https://www.nginx.com/)
* [Docker](https://www.docker.com/)
* [Ubuntu](https://ubuntu.com/)


In summary, the main features were:

* Automatically generated sitemap.xml on a daily basis
* Full-text, fuzzy search
* SSL
* Voting feature
* Reporting feature
* Anonymous publishing
* Admin and editor login
* Anti-scrapping service
* Throttling service
* Highly configurable deployment through versioned and modular CICD pipeline
* Code change to live production in 15 minutes 
* Custom monitoring
* Request and response encryption
* JavaScript obfuscation
