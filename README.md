# Global-Life-Expectancy

This is an EDA project completed for a Data Visualization course using a Kaggle dataset. The goal is to analyze life expectancy trends across countries from 1960 to present day using World Bank Data. 
The challenge/goal was to create meaningful visualizations that can convey information to an audience from, what is subjectively, an untidy dataset.

The line chart tracks life expectancy over time for the top 10 countries by historical average. Narrowing down the country pool size made it easier to spot long-term trends and compare trajectories between nations though it did come at the cost of a 'bigger picture' per se.
The heatmap shows life expectancy across 30 countries from 1960 to present day and is useful for identifying regional patterns and decades where progress stalled or accelerated. 
External research helped establish a correlation between global health events and fluctuations in populations, two of the most notable being the HIV/AIDs pandemic's effect in Sub-Saharan Africa and the SARs outbreak's effect in East Asia. 

Tools used in RL
- ggplot2, dplyr, tidyr, readr

Data Source:
- LifeExpData is provided in the repository, unfortunately I could not trace the source back to Kaggle.

How to run:
- Download data csv file 
- Open Rmd file in R and knit to HTML
- ! Dataset must be in same directory as R file !
