# Tiktok-Google-Trends-Data-Regression-Analysis-and-Forecasting-using-R

Copyright © 2022, Nazlı Ece Baltepe. Released under the GPL-3.0 License.

** If you find this code useful and would like to use the code or the graphs in this repository in your work, please cite it. You can find the "Cite this repository" widget at the repo sidebar (below the "About" section) for an easy and correct citation in APA and Bibtex formats.

An analysis of Google Trends on the keyword "tiktok". Data is accessed using gtrendsR package in R, a polynomial regression analysis is conducted and forecasting is made with an ARIMA model.

Programming Language: R

Used models: Polynomial regression model, ARIMA

Used packages: forecast, gtrendsR, ggplot2, dplyr, caret, tidyverse, ISLR, broom, lubridate

Tiktok is a short-form video hosting service which started a trend of increasing popularity during the pandemic. I am using Tiktok Google Trends data which was obtained via the gtrendsR package, pulling the Google Search trends for the keyword "tiktok" between 1 January 2019 to 2 October 2022. The analysis shows an  increased popularity of the app during the pandemic and onwards. 

The analysis includes a graph zooming on the dates where the number of the hits increased demonstrating the dates where the increasing trend for the app starts, testing the linearity of the relationship between the variables ("Date" and "Hits"), testing error estimates for polynomials up to 3rd degree using the bootstrapping approach, fitting the best polynomial regression model for the data, and a forecast plot forecasting the interest for the app for the next couple of years based on an ARIMA model created with auto.arima function, fitting the best possible ARIMA model for the data. Before each code chunk, I included short notes describing what I did.
