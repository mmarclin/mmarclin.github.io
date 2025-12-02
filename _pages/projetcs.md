---
permalink: '/projects/'
layout: single
# classes: wide
author_profile: true
title: ''
toc: false
toc_label: 'Projects'
toc_sticky: true
---

<!-- See also https://github.com/inukshuk/jekyll-scholar to customize your references -->

<!--Projects -->

## Projects

#### Project: Île-de-France Accident Severity Prediction API

[Link to Project](https://github.com/mmarclin/car_crash_project)

This is an end-to-end data science project that builds a complete web application to predict road accident severity in the Île-de-France region.

The final product is a **Dockerized Flask API** that serves a machine learning model through an interactive web interface. Users can click on a map of Paris, fill in details about an accident (like the time, weather, and vehicle type), and receive a real-time prediction for the probability of the outcome being **'Severe'** (Killed or Hospitalized) or **'Light'**.

* **Technology Stack:** Python, Flask, Docker, Pandas, Scikit-learn, Leaflet.js
* **Key Techniques:**
    * Data Engineering : merging and cleaning files.
    * Geospatial Analysis of accidents
    * Web development using Flask

#### Project: Exoplanet identification project

[Link to Project](https://github.com/mmarclin/Exoplanets_AS)

This is an applied statistics and machine learning project in **R** aiming to build a classification model that can distinguish between true exoplanets and false positives using data from the NASA Exoplanet Archive.

* **Technology Stack:** R, MASS
* **Key Techniques:**
    * Data exploration and visualization of transit data (light flux over time).
    * Feature engineering to extract statistical properties from the flux time series.
    * Training and evaluation of multiple classification models (e.g., Random Forest, SVM) to identify the most effective classifier.

#### Project: Hospital Beds Scheduling 

[Link to Project](https://github.com/mmarclin/H-optimal)

This is an optimization project, developed as part of an academic challenge, to schedule hospital bed occupations. The goal was to maximize bed usage while respecting complex real-world constraints, such as reduced patient admissions on weekends and varying lengths of stay.

* **Technology Stack:** Python
* **Key Techniques:**
    * Solved a complex scheduling problem using a **Genetic Algorithm (GA)**.
    * Designed a custom "fitness function" (scoring) to rank potential schedules based on their efficiency and adherence to all constraints.
    * Tuned the algorithm's hyperparameters (e.g., mutation rate, population size) to find an optimal solution.
