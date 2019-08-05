---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S., Penn State University, 2015
* Ph.D, Northwestern University, 2020 (expected)

Projects
======
* Deterministic Security Log Analysis and Visualization System

*(Instrumentation-free user-centric attack investigation system with high level semantics by JAVA)*
  * Helped to design system architecture and algorithms to extract information from system logs
  * Designed data process application, leveraged Longest Common Subsequence (**LCS**) algorithm to extract common patterns from massive log (>100Gb), and generate ready-to-use JSON file
  * Developed a website for users to upload collected logs (**Java Spring MVC**) and to visualize those logs and their semantics interactively (**Google Catapult Trace-View JavaScript frontend**)
  * Implemented Google Catapult Trace-View to visualize recorded events and their semantics
  * Built graph databases (**neo4j**) to store the graphical dependency of system events and optimized the data import time by >100 times

* Collaborative Online Editor for Programming Challenges

*(Code editor that supports multi-users to collaborate on algorithms and designs using Angular)*
  * Developed web application with Angular framework and Node.js to handle HTTP requests 
  * Built NoSQL database (**MongoDB**) to store the programming challenges and edited code scripts
  * Implemented collaborative feature with **Socket.io** for code synchronization and **Redis** for fast access
  * Deployed Python backend server in **Docker** container to execute and validate code finished by users
  * Optimized and refactored the code execution throughput with load-balancer (**Ngix**)


* Spring Based Web Application: Real-time Earthquake Visualization

*(Real-time earthquake monitoring system using Java Spring framework)*
  * Designed and developed a full-stack web application with **Spring MVC** framework to monitor and visualize real-time USGS global earthquake distribution
  * Built data ingestion micro-service with **JSON Schema** to validate and parse raw JSON real-time data from USGS datacenter
  * Created real-time Earthquake web map with **GeoLocation** and **Google Map** APIs, built event dashboard to display earthquake information, such as magnitude, depth, and coordinate
  * Utilized **ElasticSearch** to provide location based search functions for users to search and sort events
  * Implemented asynchronous system using producer-consumer pattern with RabbitMQ as message broker to decouple multiple requests simultaneously

* Production Target Area Forecast, EQT Corporation

*(Applied scientist Intern – Pattern recognition and machine learning using R)*
  * Implemented principle component analysis, multiclass classification, and regression in R to analyze multi-dimensional Giga-bytes-data (1000+ wells) for shale-gas production
  * Optimized the multivariable statistical model for exploration area prediction, reduced error by 72%
  * Trained supervised machine learning models including Logistic Regression, Random Forest and KNearest Neighbors, and applied regularization with measured parameters to overcome overfitting
  * Delivered 6 maps for production decision. Presented directly to the CEO and management team

Work experience
======
* Northwestern University 2015- Now: Research Assistant
* EQT Summer 2014: Applied scientist intern

Skills
======
* Programming Languages: 
  * Object-oriented design using Java
  * Web development using HTML, CSS, JavaScript 
  * Machine Learning and statistical analysis using R, Python 
* Databases: 
  * Relational databases (MySQL)
  * Non-relational database (MongoDB)
  * Graph databases (neo4j) 

Awards and leadership
======
* President of Chinese Student and Scholar Association at Northwestern (2016-2017)
* Medill Science Writing Fellow at Northwestern (2018)
* Northwestern Graduate Fellowship (2015)
* GSA Research Fellowship (2014)
* Imperial Barrel Award (2014)
* Cheaspeake Award (2013)
* Shell Energy Research Grant (2013)
* National Scholarship of China (2011/2010)
