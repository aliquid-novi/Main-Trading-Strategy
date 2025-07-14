# Main-Trading-Strategy

Jupyer notebook base_R&D is my working research notebook for a trading strategy based on the Generalized Factor Model with Conditional covariance forecasting (GFM-C). This project explores the relationship between multiple explanatory factors and FX currency pairs.

The core idea is to forecast the next-step covariance matrix of asset returns by estimating factor loadings and leveraging their conditional structure. This forward-looking risk estimate is then used to construct a portfolio via Global Minimum Variance (GMV) optimisation.

The primary focus of this project is not alpha generation, but optimal risk management — aiming to achieve a desirable risk-adjusted return by dynamically allocating based on forecasted covariance structures.
