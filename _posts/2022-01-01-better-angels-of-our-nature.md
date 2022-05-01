---
title: "Figures from Steven Pinker's book The Better Angels of Our Nature"
date: 2019-04-07T08:08:50-04:00
excerpt_separator: "<!--more-->"
categories:
  - data visualization
tags:
  - data visualization
  - RStudio
  - ggplot2
---

Here are several visualizations about violence rates created with R.

Several percentages in a figure about a share of violent deaths are referencing only male population; to simplify, I neglected that information.

Third figure illustrates the 'Recivilization of the 1990s' thesis, a period of violence decline. Pinker claims it is due to the increased incarceration: "The most effective was also the crudest: putting more men behind bars for longer stretches of time."; and increase in the police force: "In a stroke of political genius, President Bill Clinton undercut his conservative opponents in 1994 by supporting legislation that promised to add 100,000 officers to the nation’s police forces.", among other things.

Fourth figure is adopted to the time scale of century instead of mid year, and the conflicts are ordered.

![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/ggplot2/TheBetterAngelsofOurNature/1.Rate_of_Violent_Deaths.png?raw=true "Title"){: width="600" }

Steven Pinker's book:
[The Better Angels of Our Nature](https://en.wikipedia.org/wiki/The_Better_Angels_of_Our_Nature)

<!--more-->

### The original Dataset

I copied the data for worldwide rate and share of violent deaths, and for rates of homicides in Western European countries from Max Roser's articles, where he was recreating numerical data used in Steven Pinker's figures. Data for the fourth figure is from Matthew White's book 'Atrocities: The 100 Deadliest Episodes in Human History', slighty preprocessed for the century time scale, and therefore different from Pinker's figure.

* [Ethnographic and Archaeological Evidence on Violent Deaths](https://ourworldindata.org/ethnographic-and-archaeological-evidence-on-violent-deaths)
* [Homicides](https://ourworldindata.org/homicides)
* [Matthew White - Atrocities](https://www.amazon.com/Atrocities-Deadliest-Episodes-Human-History/dp/0393345238)


### Created With

* [RStudio 1.1.463](https://www.rstudio.com/)
* [ggplot2 3.1.0](https://ggplot2.tidyverse.org/)





![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/ggplot2/TheBetterAngelsofOurNature/2.Share_of_Violent_Deaths.png?raw=true "Title"){: width="600" }

![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/ggplot2/TheBetterAngelsofOurNature/3.Homicide_Rates_in_Western_Europe.png?raw=true "Title"){: width="600" }

![alt text](https://raw.githubusercontent.com/matkosoric/Data-Visualizations/master/ggplot2/TheBetterAngelsofOurNature/4.100_Worst_Wars_and_Atrocities_in_Human_History.png?raw=true "Title"){: width="600" }



[GitHub repo](https://github.com/matkosoric/Data-Visualizations/tree/master/ggplot2/TheBetterAngelsofOurNature)

