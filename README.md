# Text Mining of Restaurant Reviews on TripAdvisor

# About the project

TripAdvisor is the largest travel site in the world, allowing travelers to get the most out of every trip.With million of reviews and comments on lodging spots, restaurants and attractions,TripAdvisor provides recommendations to million of travelers,as well as variety of travel and planning options when searching for specific destination. I prefer to search up a restaurant on TripAdvisor and read the menu, reviews and ratings before visiting any restaurant on my trip. As a result, I thought it would be fascinating to play around TripAdvisor restaurant reviews in order to figure out where to eat specially in the Paris city.

It is in the interest of the stakeholders to have actionable knowledge regarding customer opinions on TripAdvisor because of its significant role in Tourism. The business case is straight forward,we can be on a budget, seeking for top-rated restaurant in city, or looking for a healthy cuisine restaurant in such a scenario having information on menu, ratings, reviews, and price of available restaurants in a city in one place really helps in making better decisions. The outcome of this project can be useful virtually for every stakeholder in the tourism industry and the customers who wants to spend their time having nice food in a healthy cuisine restaurant. Also this analysis could be an important factor to the advertisement agencies and to brands who wish to sign up certain artists as ambassadors. It helps the tourism business professionals to plan their business strategies to get more beneficial.

# Data Source and Data Description

The TripAdvisor Restaurant Reviews dataset was retrieved from Kaggle https://www.kaggle.com/damienbeneschi/krakow-ta-restaurans-data-raw.

This dataset was published by Damien Beneschi on Kaggle. The data was collected for 31 Euro cities which contains information about restaurants that were registered in the TripAdvisor database. The author has obtained this dataset by web scraping the TripAdvisor tourism website for information on restaurants listing pages. Out of 31 Euro cities restaurant reviews, in my project, I have selected the TripAdvisor restaurant reviews and ratings for the city ‘Paris’. The dataset is a csv file.This dataset consists of 8301 observations or records with 8 attributes. The attribute ‘Reviews_WD’ contains reviews of the customer along with date in the same cell. Since the date on which the customer has given the review does not carry much information for my analysis I have trimmed the date part in each cell of the reviews column by using LEFT(text, LEN(text)-num_chars) in excel. This trimmed part of customer reviews is assigned to new column ‘Reviews’.

# Tool Used

RapidMiner Studio Educational (version 9.9)

# Data Preprocessing

Checked for missing values and any inconsistencies in data

# Modeling and Evaluation

1. Correlation Analysis

2. Association Analysis

3. K-Means Cluster Analysis

# Summary

The TripAdvisor travel research platform collects customer reviews, comments and opinions about restaurants, destinations , lodging and activities all around the world. The main goal of my project is to perform initial investigations and text mining analysis of restaurant reviews on TripAdvisor dataset so as to get insights of restaurant reviews on TripAdvisor with the help of text mining techniques. The TripAdvisor dataset consists of 7 attributes and 8301 records. The attribute ‘Number of reviews’ contains 65 missing values, which were replaced by its respective attribute mean value during the data cleaning process. No inconsistencies in data were observed. 

From the analysis it is observed that there is very negligible positive relationship between number of reviews and ratings. This necessarily does not mean that any restaurant with a greater number of reviews has more ratings and vice versa. Also as per the ranking attribute there is not much to conclude because this is not built on number of reviews and ratings. So, there is no correlation between ranking versus number of reviews and ratings. From the Association analysis it is evident that , the words good and service are a premise to the word food with confidence of 70.6%. It has lift value of 2.827 indicating that the confidence is 3 times larger than the baseline confidence. Also 2.6% of all documents contains an association of the terms good,food, and service. Thus the words good and service are greatly associated with word food. From this I can say that customers 
had a great service and good food experience at these restaurants in the Paris city. From the K-Means cluster analysis with k=5 I can conclude that the cluster 0 is about Asian Sushi Food, cluster 1 talks about Good healthy Vegan, Gluten free food options , cluster 2 is about Mediterranean Vegetarian food, cluster 3 is about Italian Delicious Pizza cluster 4 is about French food and great friendly service. Analyzing the reviews data on TripAdvisor, one of the largest travel site over a period would help the investors and customers to make better decisions.
