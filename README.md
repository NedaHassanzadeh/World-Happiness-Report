# Expanatory Data Analysis on World Happiness Report 2021

## Introduction

* This notebook is an exploratory data analysis on world happiness reports data and to explore what makes a country happy. 
* The World Happiness Report is a landmark survey of the state of global happiness. 
* The report continues to gain global recognition as governments, organizations and civil society increasingly use happiness indicators to inform their policy-making decisions. 
* Leading experts across fields – economics, psychology, survey analysis, national statistics, health, public policy and more – describe how measurements of well-being can be used effectively to assess the progress of nations. 
* The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness.
* This analsys was created based on [Kaggle](https://www.kaggle.com) datasets. The Following sources have been used in this notebook: 
    
    * [World Happiness Report 2021](https://www.kaggle.com/ajaypalsinghlo/world-happiness-report-2021)
    * [World Happiness Report 2021](https://happiness-report.s3.amazonaws.com/2021/Appendix1WHR2021C2.pdf)



## Data Content

* The happiness scores and rankings use data from the Gallup World Poll. 

* The columns following the happiness score estimate the extent to which each of six factors – economic production, social support, life expectancy, freedom, absence of corruption, and generosity – contribute to making life evaluations higher in each country than they are in Dystopia, a hypothetical country that has values equal to the world’s lowest national averages for each of the six factors. 

* They have no impact on the total score reported for each country, but they do explain why some countries rank higher than others.

## Features

* **Ladder score:** the national average response to the question of life evaluations. The English wording of the question is “Please imagine a ladder, with steps numbered from 0 at the bottom to 10 at the top. The top of the ladder represents the best possible life for you and the bottom of the ladder represents the worst possible life for you. On which step of the ladder would you say you personally feel you stand at this time?” This measure is also referred to as Cantril life ladder, or just life ladder in our analysis.

* **Logged GDP per capita:**  iThe GDP-per-capita time series from 2019 to 2020 using countryspecific forecasts of real GDP growth in 2020.

* **Healthy Life Expectancy (HLE):** Healthy life expectancies at birth are based on the data extracted from the World Health Organization’s (WHO) Global Health Observatory data repository 

* **Social support:**  the national average of the binary responses (either 0 or 1) to the GWP question “If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?”

* **Freedom to make life choices:**  the national average of responses to the GWP question “Are you satisfied or dissatisfied with your freedom to choose what you do with your life?”

* **Generosity:** is the residual of regressing national average of response to the GWP question “Have you donated money to a charity in the past month?” on GDP per capita.

* **Corruption Perception:** The measure is the national average of the survey responses to two questions in the GWP: “Is corruption widespread throughout the government or not” and “Is corruption widespread within businesses or not?” The overall perception is just the average of the two 0-or-1 responses. The corruption perception at the national level is just the average response of the overall perception at the individual level.





