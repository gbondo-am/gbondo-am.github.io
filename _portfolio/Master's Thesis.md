---
title: "Master's Thesis"
excerpt: "This folder is a documentation of my Master's thesis titled: <em>Geogenic radonpotential (GRP)<em/> mapping of Hessen using Machine Learning Technique <br/><br /><a href='' target='_blank'><img src='/images/thesis.png'></a>"
collection: portfolio
---

# Thesis Title: [Geogenic radon mapping of Hessen using Machine Learning Techniques](https://github.com/Madaar49/Masters_Thesis/tree/main)

## Overview

This research focused on spatial modelling of *Geogenic radonpotential (GRP)* in Hessen District using machine learning techniques, and environmental covariables. 

*Geogenic radonpotential (GRP)* is defined as the portion of radon emanation, that is predominantly associated with natural factors.

**Hypothesis :** The spatial variability of GRP is affected by environmental parameters related to soil, geology, meterology etc. Therefore, by modelling a relationship between known sampling points and their environmental co-variables, we can predict the radon potential in areas where the environmental co-variables are present but radon is unknown.


## Data and Method
- *Radon-222* and *Soil gas permeability* per measuring location are used to calculate the  *Geogenic radonpotential (GRP)* using the ***(Neznal et al. 2004)*** equation.

- 38 covariates related to geology, soil, and climate, and DEM etc.

- Use *spatial cross validation* for feature selection.

-  Develop models such as *Random Forest Regressor*, *xGBoost/Gradient Boosting Regressor*, *Suport Vector Regressor*, *Multi-Layer-Perceptron Regressor*

- Choose the best performing models for *spatial prediction.*

## Deliverables

The code and workflow [will be available here after publication of the research](https://github.com/Madaar49/Masters_Thesis/tree/main)
