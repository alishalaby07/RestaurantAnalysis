# RestaurantAnalysis

## Description
According to specific assumptions made in microeconomics, fast food is an inferior good; meaning as an individual's income increases the rate of purchases that are made on fast food will decrease. This relationship is otherwise known as the income effect. In the case of inferior goods, the income effect is negative. Many factors can determine the natural behaviour of a good. For example, an inferior good is usually cheap in price and low quality. It is important to explore other causal factors that can act as predictors for income, allowing for future implications regarding future predictions made on income per capita. Restaurant density is the proportion of restaurants to population. This shows the concentration of restaurants in a given area.

After some data cleaning, manipulation, and visualization, the data showed that restaurant density seemed to have a moderate correlation with disposable income per capita. To analyze this relationship more specifically, burger restaurant density was found and an even stronger negative relationship was observed.  Thus, economic implications seemed to have some responsibility for the correlation between fast food restaurant density(independant variable) and income per capita(outcome). Through API scraping from the Bureau of Economic Analysis, I was able to import data on takeouts per capita, non durable consumption per capita and durable consumption per capita. All used as predictors for disposable income per capita. After analyzing the seperate correlation each IV had with income per capita, it was evident that all three relationships were positively correlated, however, the relationships were either moderate or weak. Exploring these relationships further using machine learning techniques and multiple regression open more discussions on the accuracy of such relationships.

## Overview
- Discovered a strong negative correlation between disposable income per capita and restaurant density in the US
- Used pandas and sklearn to develop machine learning models including multi-linear regression and regression trees
- Visualized finding on maps using geopandas and matplotlib
- Used micro and macroeconomic theories including Personal Income Hypotheses and elasticity to explain data trends

