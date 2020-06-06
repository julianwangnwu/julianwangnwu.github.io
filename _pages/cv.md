---
layout: archive
title: "Julian Wang CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D, Northwestern University, 2020 (expected)
* M.S., Penn State University, 2012-2014

Work experience
======
* Northwestern University (2015- Now): Research and Teaching Assistant
* Penn State University (2012- 2014): Research and Teaching Assistant
* Industry: EQT(2014-2015)/SINOPEC(2010/2011/2012)

Skills
======
* Analytical tools:
  * Isotopes: IRMS (C/O/S/N), TIMS(Sr/Ca/U/Pb), MC-ICP-MS
  * Elements: ICP-MS, ICP-OES, Coulometer
  * Imaging: SEM, TEM, Raman Spectroscopy, Neutron Scattering
* Programming Languages:
  * Object-oriented design using Java
  * Web development using HTML, CSS, JavaScript
  * Machine Learning and statistical analysis using R, Python
* Databases:
  * Relational databases (MySQL)
  * Non-relational database (MongoDB)
  * Graph databases (neo4j)

Publications
======
**Wang, J.**, Jacobson, A.D., Sageman, B.B., Hurtgen, M. T. *(submitted)* Ca and Sr isotopes indicate volcanism-triggered biocalcification crisis during Oceanic Anoxic Event 1a.

**Wang, J.**, Arthur, M. A., *(in revision)* The diagenetic origin and depositional history of the Cherry Valley Member, middle-Devonian Marcellus Formation.

Dong Y., Fu S., Wen L., Chen H., **Wang J.**, Zhu P., Xu S., Cui Y., *(in revision)* Tectonic control of Guadalupian-Lopingian cherts in northwestern Sichuan Basin, South China. Palaeogeography, Palaeoclimatology, Palaeoecology

Chen, Y., **Wang, J.**, Zhou Z., Chen X., Zhao Z, Shi P., Han Y., *(accepted)* Ancient Microorganisms and Carotenoid Preserved in Fluid Inclusion in Halite from Chaka Salt Lake, Western China: Evidence from Micro-observation and in situ Raman Spectroscopy. Acta Geologica Sinica.

**Wang, J.**, Jacobson, A.D., Zhang, H., Ramezani, J., Sageman, B.B., Hurtgen, M.T., Bowring, S.A. and Shen, S.Z., 2019. Coupled δ44/40Ca, δ88/86Sr, and 87Sr/86Sr geochemistry across the end-Permian mass extinction event. Geochimica et Cosmochimica Acta, 262, pp.143-165. https://doi.org/10.1016/j.gca.2019.07.035

Linzmeier, B.J., Jacobson, A.D., Sageman, B.B., Hurtgen, M.T., Ankney, M.E., Petersen, S.V., Tobin, T.S., Kitch, G.D. and **Wang, J.**, 2020. Calcium isotope evidence for environmental variability before and across the Cretaceous-Paleogene mass extinction. Geology. https://doi.org/10.1130/G46431.1

Cui, Y, Zhang, F., **Wang, J.**, Shen S. Z., Marine anoxia and ocean acidification during the end-Permian extinction: an integrated view from δ238U and δ44/40Ca proxies and Earth system modeling. Environmental Change and Large Igneous Province: The Deadly Kiss of LIPs, AGU Book 2020

Dong, Y., Chen, H., **Wang, J.**, Hou, M., Zhu, P., Zhang, C., Cui. Y., 2020, Thermal convection dolomitization induced by the Emeishan Large Igneous Province. Marine and Petroleum Geology.  https://doi.org/10.1016/j.marpetgeo.2020.104308

Zhu, P., Dong, Y., Chen, M., Li, Z., Han, B., **Wang, J.**, and Cui, Y., 2020, Journal of Natural Gas Science and Engineering Quantitative evaluation of pore structure from mineralogical and diagenetic information extracted from well logs in tight sandstone reservoirs: Journal of Natural Gas Science and Engineering, v. 80, p. 103376, doi:10.1016/j.jngse.2020.103376.


Awards and leadership
======
* President of Chinese Student and Scholar Association at Northwestern (2016-2018)
* Medill Science Writing Fellow at Northwestern (2018)
* Northwestern Graduate Fellowship (2015)
* GSA Research Fellowship (2014)
* Imperial Barrel Award, AAPG (2014)
* Cheaspeake Award (2013)
* Shell Energy Research Grant (2013)
* National Scholarship of China (2011/2010)

Programming Projects
======
* Deterministic Security Log Analysis and Visualization System
*(Instrumentation-free user-centric attack investigation system with high level semantics by JAVA)*
  * Helped to design system architecture and algorithms to extract information from system logs
  * Designed data process application, leveraged Longest Common Subsequence (**LCS**) algorithm to extract common patterns from massive log (>100Gb), and generate ready-to-use JSON file
  * Developed a website for users to upload collected logs (**Java Spring MVC**) and to visualize those logs and their semantics interactively (**Google Catapult Trace-View JavaScript frontend**)
  * Implemented Google Catapult Trace-View to visualize recorded events and their semantics
  * Built graph databases (**neo4j**) to store the graphical dependency of system events and optimized the data import time by >100 times

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
