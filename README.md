# Project Name: Recommendation
Udacity Data Scientist Nanodegree - Recommendation for IBM

## Working Environment
In order to determine which articles to show to each user, it is suggested to be performing a study of the data available on the IBM Watson Studio platform. 

However, I would develop this project on Jupyter Notebook/Python 3.6 on my own environment. The overall algorithm, procedure and outputs should be consistent.

## Data source
Two data tables to be used in this project, which were provided:
- user-item-interactions:  Data set containing which user interacted with which article.
- articles_community: Data set consists the details of the articles
 
## Python libraries used:
   python3
   python packages in the requirements.txt file: datetime, pandas, numpy, seaborn, matplotlib   

## Tasks:
### I. Exploratory Data Analysis
#### Before making recommendations of any kind, explore the data for the project. 

### II. Rank Based Recommendations
#### First find the most popular articles simply based on the most interactions.  

### III. User-User Based Collaborative Filtering
#### Look at users that are similar in terms of the items they have interacted with.  

### IV. Content Based Recommendations (EXTRA - NOT REQUIRED)
#### Complete a content based recommendation system.

### V. Matrix Factorization
#### Finally, complete a machine learning approach to building recommendations.  


## Output:
(see the .html file)
 
## Conclusion:
Observed Trending:
The training accuracy gets improved along with the increase of number of latent features, while the testing accuracy is on opposite direction but very slightly.
200 latent features might be the best for both population.

Statistical drawback:
The testing dataset is too small (20 out of 5993). Therefore, it is not sufficient to conclude the good prediction of the model. 
The training accuracy is >99%, indicating the overfitting of the model.

Conclusion:
SVD by self is not a good recommendation engine in the given case. Additional recommendation agorithem should be applied 
(such as Content based or rating based recommendation, or collaborating filtering). Also, an A/B testing should also be applied for each engine.

