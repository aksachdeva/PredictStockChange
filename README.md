
#Introduction

PredictStockChange predicts the changes in stock prices of a company by monitoring financial news articiles related to it. It scraps news articles, and perfroms sentiment analysis of the articles using MapReduce, Hive and Pig. Finally, the prices are plotted using R.

#Requirements

 - Python 2.7 : To extract news headlines and Articles
 - newspaper  : Python library to download news articles
 - beautifulsoup : Python library to scrap webpages
 - MapReduce, Hive and Pig : To perform ETL of the articles, and sentiment analysis.
 - R           : To graphically respresent sentiment analysis output

#Installation
 - Cloudera Quickstart VM with Hive and Pig installed.
 - Install libraries mentioned in Requirements from pypi or pip, and place the project files in working directory.
