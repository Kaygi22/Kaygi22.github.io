---
layout: project
type: project
image: images/f-analyzer.png
title: Moroccan Social Media Analyzer
permalink: projects/MSM-Analyser
# All dates must be YYYY-MM-DD format!
date: 2019-06-23
labels:
  - NLP
  - Sentimental Analysis
  - Data Scrapping
  - Java
  - Python
  - MongoDB
  - Selenium
  - Spring Rest
  - ReactJS
  - Data Visualization
summary: A web engine for scrapping Moroccan social media public data, analyzing, classifying and displaying results.
---

<img class="ui image" src="../images/pfa_architecture.jpg">

This project is our final year project in our 4th year in school (2nd year of engineering cycle). In fact, open darija was founded because of this project, since we wanted to be creative in our project,we chose to work on Moroccan's Dialect NLP since the project was the first of its kind in Morocco.

The project was about creating a web application that helps you to scrape a social media public profile, analyse it and classify its content and finally display it to the user. The project was not commercial, it was an academic project, so we displayed the results of the project in a defense in front of school's jury.

<img class="ui image" src="../images/f-analyzer.png">

The project was split to 5 main parts:

* <h4>Scrapper engine</h4>: This scrapper was open sourced, so we modified it to adapt it to our needs. We wanted to scrap a facebook profile public data. It was based on selenium. 

* <h4>Open Darija</h4>: this was a previous presented project in my portfolio. It's the dictionary that we developed, it helped us to provide a sentimental analysis for the analysed data.

* <h4>BackEnd Core</h4>: this was the core of the application, it contains the TADM (traitement automatique du dialecte marocaine) / NLP algorithms for Moroccan dialect that we developed using JAVA, Scrapping engine that scrape social media data, DB engine that executes queries from/to mongoDB and save/get data and SpringRest engine that ensure the communication with the front website data visualizor.

* <h4>Front website for data visualizaton</h4>: The front website was developed using ReactJS and ChartJS for visualising data. The front was connected to the back end with a Rest API that was developed using Rest API.