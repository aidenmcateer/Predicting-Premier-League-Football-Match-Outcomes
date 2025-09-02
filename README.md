# Predicting-Premier-League-Football-Match-Outcomes
Using statistical analysis and machine learning models to predict football match outcomes in the Premier League

For this data science project, i have sourced data from football-data.co.uk. The data was exported as a CSV before being transformed using delimiting factors in Excel. This meant the data was structured and easy to read, before loading into Google Colab where I then used Python for further transformation and analysis

Following completing analysis, comparing categorical columns to FTR and numerical columns to FTR I created a "form rating" 
  The analysis found that Home Wins were the most likely outcome, whereas draws were the least likely.
  The resulting analysis also showed that certain teams are more likely to win at home, whereas there is a more even distribution of outcomes in other teams. For example Man City and Arsenal are likely winners when at Home, but Everton have a lot more even distribution between the results
It also shows that the Half Time Result, has a particularly strong correlation to the Full Time Result, with 606 times the Half Time result was Home and Full Time Result was Home, whereas when the Half Time Result was Home, the Away team only won the match 59 times

I then went onto analyse the numerical columns, finding that Home Shots on Target and Away Shots on Target, had the strongest correlation of a Home or Away Result.

Using the strongest correlating columns, I then went onto create a Machine Learning Model with the dataset, which had a 62% accuracy
  The model was more accurate at predicting Home Wins, 70%, compared to lacking in accuracy when predicting draws
