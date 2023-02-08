
# Don’t look up: Air Pollution - Data analysis on the PM2.5 

# Context 

Air pollution is one of the most pressing environmental and health issues across OECD countries and beyond. As European citizen, Luisa and I wanted to study how is the air we breathe in the EU?
We focused on the PM2.5, a fine particulate matter which is the air pollutant that poses the greatest risk to health globally, affecting more people than any other pollutant. 

To carry out this study, we used 4 datasets:
 - Population exposure to PM2.5 (Unit: Micrograms per cubic metre)
 - Mortality from exposure to PM2.5 (Unit: Per 1 000 000 inhabitants)
 - Socio-economic data of the countries 
 
 Where: European countries (27)
 
 Date: 1990 - 2019
 
 Source: OECD data (The Organisation for Economic Co-operation and Development)
 
 - Scientific publications on the air pollution (Wikidata - Worldwide - from 1990-2022)



# Deliverables 
We created a dashboard on Tableau that you can find here: https://public.tableau.com/app/profile/maria.policarpo/viz/Project6-Airpollution/Histria1?publish=yes

We also used machine learning (linear regression) to predict the PM2.5 exposure in the upcoming years. 

All the code is in Github’s folders listed below. 

# GitHub folders - Description 

- FinalColabFiles: What is it? Those are the final Google Colaboratory files that reply to our questions. We also did the statistics on these files. 

- Machine Learning: Those are the code for the algorithms, the recommendation system and the input file.

- Exploratory Data Analysis: This is our initial analysis on the different datasets. 


# Pre-processing 

# Cleaning explanation
We chose to focus on movies so we excluded the other types (related to TV or video games) and also specific genres (Film-Noir, Game-Show, News, Reality-TV, Short, Talk-Show). 
We cleaned the tables and merged the one we needed to reply to the questions we had.

There were too many unknown movies with 10/10 rate, but not with a lot of votes, so we decided to reduce our dataset for only the movies with more than 6000 votes, which represents 5% of the initial dataset.Therefore, we excluded the movies with less number of votes. 

What is considered as a “best movie”? We defined the best movies as the ones that would belong to the list of the 1000 movies better ranked, from the 5% dataset. 
For the other queries, we decided to use only the 5% of the dataset also to present only the best movies with the best rates. 


