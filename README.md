# Predictive Modeling for Tanzanian Wells 

![](images/cropMount-Kilimanjaro.jpg)

## Overview

Our group has been hired by Tanzania's Ministry of Water to develop a classification model that will assist the Ministry in predicting the status of the waterpoints they oversee. Although the waterpoint statuses could be described in a number of ways - e.g. whether it is functional but needs repair - our model will perform a binary classification to determine if the waterpoint is functioning as exepected or not.

## Business and Data Understanding Explain your stakeholder audience and dataset choice here

While the country of Tanzania has abundant water resources including Lake Victoria, the largest lake in Africa, nearly 50% of the waterpoints overseen by the Ministry of Water are non-functional, leaving large segments of the population without a reliable or potable source of water. The Ministry has decided to address this issue by having a predicitve model created that will allow them to identify the functionality of waterpoints. The model needed to take into consideration the fact that if wells were incorrectly identified as being functional then communities would be left without water, and conversely if the model identified working wells as broken the Ministry would not be able to allocate their resources effectively.

![](notebooks/Alex/GIS/anzania_pumps.png)

We used the a dataset compiled by the [Ministry of Water](https://www.maji.go.tz/) and [TAARIFA](https://taarifa.org/) and available at [DataDriven.org](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/).  The dataset describes over 59,000 waterpoints and includes features for each point such as location, water quality, funding agency, etc. The majority of the dataset's 40 features contain categorical data while only 10 contained numeric data.  Two significent issues with the data set were the high number of redundant columns and missing data points. As part of our EDA process we addressed these issues by cutting the dataset down to 20 features and filled in the missing data points with appropriate filler - "Unknown" for categorical columns, NaN for numeric.  We also converted the pump status data by combinging two of it's three categories, "non functioning" and "functioning in n


## Modeling


## Evaluation
## Conclusion


