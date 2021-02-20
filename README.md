# project-1-group-7
Project exploring data from the World Happiness Report & Internet Usage
Group Members: Rebecca Tricker, Steven Gaetz, Mason Totall, Daniel Bernal

Our group's research questions were:
• Is there a correlation between a country’s level of happiness and percentage of internet users? Does a country's happiness decrease as the percentage of internet users increase?
• Looking at the six factors analyzed in a country’s happiness score, is there a relationship between a country's scores and percentage of internet users? The six factors include economic production, social support, life expectancy, freedom, absence of corruption, and generosity. 


This repository contains two Jupyter Notebooks, one that cleans and explores the country-level data from the World Happiness Report (found on Kaggle) and the percentage of population that uses the internet (found on The World Bank), and one that analyzes the data to help us answer the research questions above.

The cleaning process involved merging data from several CSVs. The main challenge in this process was that the data sources all had slightly different column titles between different years, and we needed a way to easily distinguish data from different years.

The analysis process involved looking at scatterplots and linear regression/correlation of countries' happiness scores vs. internet user percentage. We also used line graphs and ANOVA testing to look at the mean Happiness Score and Internet User Percentage by year, and displayed a box-and-whisker plot for all the years. Finally we looked at a few interesting patterns (dividing the data by percentage of users in a country either below or above 50%).

A discussion of how our data helped us address our research questions is provided at the end of the analysis notebook. Images are also saved as PNG files in an output folder.
