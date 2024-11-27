**Election Forecasting Model: 2024 U.S. Presidential Election**

This repository contains a Bayesian hierarchical model designed to forecast the outcome of the 2024 U.S. Presidential Election. The model integrates both fundamental economic and political indicators and real-time polling data to provide an Election Day forecast.


**Data Sources**

1. Polls: Nationwide and statewide trial-heat results collected from various pollsters.
2. Economic and Social Data: Data such as economic growth rates, presidential approval, geographical features, and demographic statistics.

Polls data is sourced from FiveThirtyEight.

**Methods**

The model uses a Bayesian dynamic hierarchical structure to synthesize two primary data sources:
1. Fundamentals: Economic growth, presidential approval, and incumbency status.
2. Polls: Trial-heat data from state and national polls.

The model uses Hamiltonian Monte Carlo (HMC) sampling for efficient Bayesian inference with Stan. This method improves sampling efficiency and is suited for high-dimensional models.

**Key Model Features**

- State-level trends: Modeled as a correlated random walk to capture evolving public opinion across states.
- Bias Adjustments: Corrects for house, population, and mode effects in polling data, as well as partisan nonresponse.
- Covariance Structures: Takes into account the spatial correlation of demographic and electoral features.

[Click here to access the folder with data and other documents used for the project](https://mega.nz/folder/uAN1URIK#bXOq06WCxmGEIYvnQ-shvw)


