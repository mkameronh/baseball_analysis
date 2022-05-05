# baseball_analysis
## Week 1 - Presentation

## HB - Technologies Used
### Data Cleaning and Analysis
We will use VScode for data cleaning and github for sharing. For our initial data analysis familiarizing ourselves with the datasets, we are using VScode. 

### Database Storage
For this step we will utilize an Amazon Web Service RDS (Relational Database Service) to store our csv files. 

### Machine Learning
We will be using google collab and the plug ins Spark and Java for our machine learning process. 

### Dashboard
For our machine learning model we will be using tableau to create data visualizations and displaying them on google slides. 

## NB Presentation
### Topic: 
- Baseball Hall of Fame Induction

### Reason:
- The Baseball Hall of Fame is one of the most prestigious honors you can get. The odds to make it to the MLB are significantly low. It is estimated that the odds of a little league player making it all the way to the MLB is roughly 1 / 3,376 (which I believe to be generous). To make it to the HOF are even lower. If you try to calculate the odds of making it to the MLB + making it to the HOF, your odds signifanctly decrease.

### Data Source:
- For our Data Source we used Sean Lahman's Baseball Databank. It contains all the information we could have possible needed all the way back to the 1800s. We chose to use the Appearances, Batting, Fielding, Hall of Fame, People and Pitching csvs. This allowed us to create the necessary df's to make a machine learning model to accurately compare Pitcher only data and the position player only data.

### Question We Hope To Answer:
- Simply put, our question is "Will this person make it into the HOF"
- However, since the data is skewed in favor of not making it, our ML model will be better used to predict if they will not make it into the HOF.
