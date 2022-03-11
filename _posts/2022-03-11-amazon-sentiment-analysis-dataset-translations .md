---
title: "Amazon review dataset translations for sentiment analysis "
excerpt_separator: "<!--more-->"
categories:
  - datasets
tags:
  - Amazon
  - sentiment analysis
  - Azure translate
---


This repository contains translations of a 150 000 randomly selected entries from Amazon dataset originally created by Julian McAuley and Jianmo Ni, containing over 20GB of data.
The goal is to create smaller datasets for sentiment analysis on languages other than English, for which there are many publicly available datasets already.
Translation is performed with Microsoft Azure's [Translator](https://azure.microsoft.com/en-us/services/cognitive-services/translator/) cloud service.

![AWS Spanish Translation](https://raw.githubusercontent.com/matkosoric/amazon-sentiment-analysis-dataset-translations/master/aws_spanish.PNG?raw=true "Title"){: width="600" }

<!--more-->

Original text values have been sanitized from double quotes characters.
English original with 150k entries is in **aws_sentiment_input.zip**.
Column **sentiment_score** indicates review attitude for particular item on a scale from negative (1) to positive (5).
Two columns that can be used for model training are **summary** and **reviewtext**.
Original column **overall** is renamed to **sentiment_score**.
In order to join translations with original, you can use **original_id** column in translation dataset.
Data is probably skewed in terms of Amazon's shopping category, for which there is no indicator, but it is not skewed regarding sentiment score distribution.
Each sentiment category on a scale from one to five contains slightly more than 30k entries.


[Repo link](https://github.com/matkosoric/amazon-sentiment-analysis-dataset-translations)




