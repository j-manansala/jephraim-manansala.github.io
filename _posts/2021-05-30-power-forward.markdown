---
layout: post
title:  "Power Forward: Day-Ahead Electricity Demand Forecasting Using Gradient Boosting Regressors"
categories: machine_learning regressor
list_title: "Machine Learning"
date:   2021-05-30 
---
by:  [Jephraim Manansala](https://www.linkedin.com/in/jephraim-manansala/), [Michael Dorosan](https://www.linkedin.com/in/michaeldorosan/), [Tonichi Edeza](https://www.linkedin.com/in/joseantonioedeza/), [James Gonzales](https://www.linkedin.com/in/jamescgonzales/), [Claudine Licong](https://www.linkedin.com/in/claudinelicong/), [Rommel Marquez](https://www.linkedin.com/in/rommelrmarquez/)

Asian Institute of Management

Reliable forecasting of electricity demand is key to ensuring sustainable supply-demand systems in the energy sector. Various approaches to improve reliability of forecasts range from the classical time series approaches to more data-driven machine learning approaches. Our approach used the latter in forecasting day-ahead electricity demand in the Luzon, Philippines power grid by developing gradient boosted regression trees (GBRT) models. Gradient boosting improves regression performance by optimizing prediction capabilities of weak learners—in this case, shallow depth decision trees. By turning an originally univariate forecasting into a supervised machine learning problem, our approached allowed inclusion of multivariate predictors of electricity demand. Specifically, weather variables, holiday and weekend indicator variables, and actual electricity demand data were used as predictors. We found that GBRT models outperformed the forecasts of seasonal naïve baseline models as measured by mean absolute and mean absolute percentage errors. Additionally, GBRT model performance improved upon addition of holiday, month, and day-of-week indicator variables as predictors—resulting to our best model with MAE of 236.642 and MAPE of 2.937 %. Contrary to related studies, the addition of hourly weather data as features resulted to lower performance than our best model, a result which may be attributed to the integrity of weather data used.

Keywords: Electricity Demand, Forecasting, Machine Learning

<i>Full text article and source codes can be provided upon request. </i>