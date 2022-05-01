---
title: "Compass and MongoDB with the Zagreb Surveillance Cameras dataset"
date: 2019-04-07T08:08:50-04:00
excerpt_separator: "<!--more-->"
categories:
  - data visualization
tags:
  - data visualization
  - mongoDB
  - compass
---

This is a demonstration of MongoDB's Compass visualization capabilities with geographical data. The repository contains an original csv, a preprocessed csv, a gawk script for transforming csv to json, and finally json prepared for importing in MongoDB. The list is not updated, and new cameras have been installed after the publication of the dataset in 2016. The first image is a classical, 'neutral' view, encompassing all geolocations. Other images are zooming into particular part of the city while shifting angle.

![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/MongoDB/Zagreb-Surveillance-Cameras/1.zg-cameras-all.png?raw=true "Title"){: width="600" }

![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/MongoDB/Zagreb-Surveillance-Cameras/2.zg-cameras.png?raw=true "Title"){: width="600" }

<!--more-->

### Original DataSet

I downloaded the dataset from the official Open Data Portal of the Republic of Croatia. It is a publicly available list of surveillance cameras with precise latitude and longitude data for each camera.

* [Nadzorne kamere na području grada Zagreba](https://data.gov.hr/dataset/popis-nadzornih-kamera-na-podru-ju-grada-zagreba/resource/5bc67300-8d88-4fa2-bc79-299dc41180b7)


### Created With

* [MongoDB 4.0.5](https://www.mongodb.com/download-center/community/) - Database
* [Compass 1.15.1](https://www.mongodb.com/products/compass/) - GUI




![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/MongoDB/Zagreb-Surveillance-Cameras/3.zg-cameras.png?raw=true "Title"){: width="600" }

![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/MongoDB/Zagreb-Surveillance-Cameras/4.zg-cameras.png?raw=true "Title"){: width="600" }

![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/MongoDB/Zagreb-Surveillance-Cameras/5.zg-cameras.png?raw=true "Title"){: width="600" }
    
![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/MongoDB/Zagreb-Surveillance-Cameras/6.zg-cameras.png?raw=true "Title"){: width="600" }


[GitHub repo](https://github.com/matkosoric/Data-Visualizations/tree/master/MongoDB/Zagreb-Surveillance-Cameras)

