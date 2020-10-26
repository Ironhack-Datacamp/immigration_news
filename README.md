<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Immigration in the News

*Final project*  
*Imogen Rickert*

*August 2020 cohort, Berlin, 09.10.20*

## Content
- [Project Description](#Project_Description)  
- [Questions & Hypotheses](#Questions_&_Hypotheses)  
- [Datasets](#datasets)
- [Resources](#resources) 
- [Organization](#organization)
- [Links](#links)


## Project_Description

I wanted to investigate if there is a correlation between the frequency of news articles on immigration and number of immigrants, using Australia as a case study. 

I was able to locate a dataset on Kaggle containing over 1 million news headings and their dates from the main Australian public broadcaster, ABC news. I located Australian government datasets with numbers of migrants by country of origin and migration category. 


## Questions_&_Hypotheses

A few key questions guided my analysis:

1. How many people immigrate to Australia and what are the most common origin countries?
2. How often does migration feature in the news?
3. Is there a correlation between media coverage on migration and actual immigration numbers?

I suspected that both news and immigration had increased in recent years, and hypothesized that there would be a correlation between media coverage on migration and immigration numbers. 

However, muliple (OLS) regressions indicated no statistically significant correlations between media coverage on migraiton and immigraiton numbers. This suggests that there may be other factors that have a stronger influence on the amount of news coverage, such as government policies or global events. See [presentation](https://github.com/imogen-rickert/immigration_news/blob/main/presentation.pdf)  for details. 


## Datasets
I utilised two separate databanks for my analysis.

1. ‘A Million News Headlines’
ABC news headlines for years 2003 to 2019
1 csv file
Link: https://www.kaggle.com/therohk/million-headlines

2. ‘Historical Migration Statistics’
Immigration statistics for years 1945 to X
Source: Australian Department of Home Affairs
1 excel file with 10 sheets
Link: https://data.gov.au/data/dataset/historical-migration-statistics

## Resources

As NLP was not covered in the Ironhack bootcamp, I relied on free online resources to learn the basics. I found [this video](https://www.youtube.com/watch?v=xvqsFTUsOmc&feature=youtu.be&ab_channel=PyOhio) and corresponding [Github repo](https://github.com/adashofdata/nlp-in-python-tutorial/blob/master/1-Data-Cleaning.ipynb) particularly helpful in getting started with NLP. 

## Organization

I utilised a kanban board on Trello to organise my work. 

This repository contains the following files:
- Presentation
- Notebooks: contains all jupyter notebook files
- csv_files: contains all CSV files, original and cleaned/manipulated


## Links

[Repository](https://github.com/imogen-rickert/immigration-news)  
[Presentation](https://github.com/imogen-rickert/immigration_news/blob/main/presentation.pdf) 
