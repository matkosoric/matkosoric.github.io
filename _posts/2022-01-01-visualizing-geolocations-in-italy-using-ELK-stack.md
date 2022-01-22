---
title: "Visualizing Geolocations in Italy using ELK stack"
date: 2019-04-07T08:08:50-04:00
excerpt_separator: "<!--more-->"
categories:
  - data visualization
tags:
  - data visualization
  - elasticsearch
  - kibana
  - logstash
---

This is a demonstration of ELK stack geo-mapping capabilities.

<!--more-->

### The original Dataset

The presented data are a subset of geo points in a zip file for Europe (https://s3.amazonaws.com/data.openaddresses.io/openaddr-collected-europe.zip) available through the OpenAddresses project. I used only a couple of files related to Italy (ferrara.csv, bologna.csv, statewide.csv, etc.). Circle size and color are not related to any other features in a dataset; they simply indicate a quantity of points in a certain area.

* [OpenAddresses data](http://results.openaddresses.io/)


### Created With

* [ElasticSearch](https://www.elastic.co/) - ElasticSearch NoSQL engine
* [Kibana](https://www.elastic.co/products/kibana) - Kibana visualization tool
* [Logstash](https://www.elastic.co/products/logstash) - Logstash ingestion tool


![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/Elasticsearch/ItalyGeoLocations/1.NorthItaly.png?raw=true "Title"){: width="600" }

![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/Elasticsearch/ItalyGeoLocations/2.BolognaFerrara.png?raw=true "Title"){: width="600" }

![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/Elasticsearch/ItalyGeoLocations/3.PiemonteRegion.png?raw=true "Title"){: width="600" }

![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/Elasticsearch/ItalyGeoLocations/4.Verona.png?raw=true "Title"){: width="600" }



[GitHub repo](https://github.com/matkosoric/Data-Visualizations/tree/master/Elasticsearch/ItalyGeoLocations)

