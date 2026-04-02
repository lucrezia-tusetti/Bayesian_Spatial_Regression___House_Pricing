# Bayesian_Spatial_Regression___House_Pricing
This study focuses on predicting the price per square meter of residential properties in Milan using Bayesian spatial regression models

## 🛠️ Keywords & Skills

**Skills Applied:**  
`Bayesian spatial models` `Visualization` `R programming` `Kriging` `Spike-and-Slab selection` `Feature Engineering`


## 🏠 Introduction

This research focuses on predicting house prices per square meter in Milan using Bayesian spatial models. The study compares different methods to see how both property features and geographic location influence market value.

The findings indicate that the most effective models are those that combine specific characteristics of a home with its precise location, as where a house is situated is a key driver of its price.

Additionally, the analysis reveals that smaller apartments, such as studios, tend to have higher prices per square meter and show more price variation compared to larger properties.

Overall, these statistical tools offer a reliable way to understand and navigate the complex real estate market in Milan.

## ⚙️ Methods

The study applies several advanced statistical methods, primarily within a Bayesian framework, to predict house prices in Milan. 
Three different models are developed for "point-referenced" data:
- A model focusing only on the **spatial structure** (location).
- A model focusing only on **covariates** (house features).
- A combined model that integrates both **location and house features**, which proved to be the most accurate.

To avoid making the model too complex, **Spike-and-Slab Variable Selection** was used to select only the most relevant house features (such as the presence of an elevator or the type of heating) for the price predictions.

**Universal Kriging** is a traditional frequentist statistical method used as a benchmark to compare and evaluate the performance of the Bayesian models.

Beyond looking at specific house points, the study analyzed average prices by neighborhood. It used **Conditional Autoregressive** (CAR) **models** to look at price trends for different types of apartments across various city zones.


