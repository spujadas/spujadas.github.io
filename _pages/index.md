---
layout: defaults/page
permalink: index.html
narrow: true
---

{% include components/intro.md %}

Here are a few personal projects I've been working on.

### Data science

I'm a huge data science enthusiast, and have completed a number of courses on data-science-related topics (including machine learning, deep learning, big data, and process mining) on the [Coursera](https://www.coursera.org/) and [Udemy](https://www.udemy.com/) online learning platforms.

Here are the deliverables of some of the projects that I've worked on during these courses:

- [Assessment of the effects of severe weather effects on US population health and economy](http://rpubs.com/sebp/storm-analysis-us) between 1996 and 2011, based on storm data from the National Oceanographic and Atmospheric Administration’s (NOAA) National Weather Service (NWS). *Keywords: exploratory data analysis, data cleaning, data visualisation, R, ggplot2, dplyr, tidyr.* 

- [Detecting the language of a text](https://sebp.shinyapps.io/language-detection/), a web application that determines the language(s) that a text is written in and provides information on word frequencies. A [web-based presentation](http://rpubs.com/sebp/language-detection) provides additional explanations. *Keywords: data product, language, Zipf, data visualisation, R, Shiny, ggplot2.*

- [Passenger Traffic on the Paris RATP Railway Network in 2015](https://spujadas.github.io/coursera-ddp-leaflet/ratp-railroad-passenger-traffic-2015.html), an interactive map created using the [Leaflet](http://leafletjs.com/) library, representing the number of incoming passengers per station on the Parisian RATP railroad network. *Keywords: data product, data cleaning, cartography, Leaflet, R.*

- [Predicting the quality of weight lifting exercises](https://spujadas.github.io/coursera-pml/predicting-exercise-quality), which combines a random forest model and a boosted trees model to predict how well weights are lifted, based on measurements made by on-body sensors and a labelled training data set. *Keywords: machine learning, random forest, boosted trees, R.*

- [Road Accidents in Great Britain from 2005 to 2015](https://spujadas.github.io/coursera-ddp-plotly/road-accidents-gb-2005-2015), a web page presentation that showcases an interactive plot created using [Plotly](https://plot.ly/). *Keywords: data product, data visualisation, R, Plotly.*

### Elasticsearch Logstash Kibana Docker image

I've created [_sebp/elk_](https://hub.docker.com/r/sebp/elk/), a Docker image that provides a convenient centralised log server and log management web interface, by packaging Elasticsearch, Logstash, and Kibana, collectively known as ELK.

I've also created the [_sepb/elkx_](https://hub.docker.com/r/sebp/elk/) Docker image. This image extends the ELK stack from the previous image with X-Pack, which bundles security, alerting, monitoring, reporting, and graph capabilities.

### Writing

[_Travaux pratiques de confiance électronique_](http://tp-confiance.pujadas.net) is a free e-book that I wrote on applied cryptography and electronic trust services (in French).

<hr/>

[About]({{ site.baseurl}}{% link _pages/about.md %})

