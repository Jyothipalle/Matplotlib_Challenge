## Week5 - Matplot Lib -Homework: Author - Jyothi Palle

# Objective:

I've just  joined Pymaceuticals Inc., a new pharmaceutical company that specializes in anti-cancer pharmaceuticals. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, I've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated with a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

The executive team has tasked me with generating all of the tables and figures needed for the technical report of the study. They have also asked for a top-level summary of the study results.

# Output

As part of the analysis performed below activities -

* Verify the data for duplicates and create clean data excluding duplicates

* Generated summary statistics for Tumor volume for each Drug Regimen

* Created bar charts for total number of timepoints for all mice tested for each drug regimen using Pandas Dataframe.plot() and Matplotlib's plot

* Created pie charts for female vs male mice using Pandas Dataframe.plot() and Matplotlib's plot

* Calculated quartiles for four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 

* Using Quartiles, upper and lower bound values found outliers for the four drug regimen. Created box plot for final tumor volume for four drug regimen

* Create a line plot for tumor volume vs. time point for one mouse

* Created scatter plot between mouse weight and average tumor volume for the Capomulin treatment

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. The corrlation cofficient is 0.84

# Analysis -

1. Based on the bar chart  Campomulin and Ramicane has maximum time points and propriva has low time points. Also by gender almost equaly distributed 
2. Based on Box plot Campomulin Ramicane showed better results and low tumor volume without any outliers
3. The correlation coeeficient between Mouse weight and Tumor volume is 0.84. It's a strong postive correlation, which means with mouse weight increases the tumor volume also increases.