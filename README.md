##P3-Extension
### 1. Does Betrayal Hide in Linguistics? Machine Learning Betrayal Detection in Diplomacy Game

### 2. Content of GitHub
There are three ipynb and 1 report here. I will briefly introduce them to you

#### extension_feature_selection
In this notebook, we perform many statistical analysis. We find the correlation of the variables, and draw graphs for them. Our team also did dimensional reductions and feature selection in this notebook.

#### extension_partI
In this notebook, we use different machine learning methods to fit the data on each seasons trying to get a good result.

#### extension_partII
In this notebook, we use different machine learning techniques to fit the data of four seasons before betrayal. 


### 3. Organization within the team  
  + Yuanhui
  
  Data processing, writing report, making video, code merging and data exploring.
  
  + Yehao
  
  Machine learning, writing report, making video, data analysis and statistic analysis.
  
  + Hangqian
  
  Data visualization, writing report, making video, data exploring and machine learning.
  


### 4. Abstract

Friendship is fickle, and there may be clues hidden in the words from friendship to betrayal. In our work, we mainly based on a previous research on linguistic harbingers of betrayal occurs in one online strategy game. We use machine learning methods like random forest, support vector machine, logistic regression to build a model that can judge whether a game will end up betrayal or not given the conversation the players have.


### 5. Research Questions
 + Can we predict the betrayal using the data in each seasons?
 + Can we predict the betrayal using the four seasons of data before betrayal?
 
### 6. Proposed dataset
  We decide to use the dataset given by the paper. There are two main reasons we do this:
  + The first reason is to reduce unnecessary work. It is hard to find enough dataset for such an old game. It also take too much time to process the data. For example, we might 
  spend extra time in learning Standford politeness test.
  + Another reason is that we can compare our result with the original paper directly. If we use different dataset, we might have high probability have different result due to 
  different preprocessing and different data. It is more convincing to say our model is better if our method increases the accuracy.

### 7. Methods
  + We will first explore if there is correlation between each pair of variables using Pearson coeficient. The interaction between variables we will look into are talkativeness and politeness, talkativeness and sentiment, number of request and politeness, number of request and sentiment. We will then use statistics test to find if the interaction between variables are helpful for predicting. 
  + We predict the betrayal using the data in each seasons via machine learning techniques like SVM and random forest
  + We predict the betrayal using the four seasons of data before betrayal via machine learning techniques like SVM and random forest to see if it is significant better.

### 8. Proposed timeline
  + First discussion on 11.28. Spend 10 hours to replicate the original paper, extract the necessary variables we will use from the data.
  + Second discussion on 12.05 & 12.06 . Spend 15 hours to extend our result.
  + Fix bugs and write report from 12.07 to 12.13. Spent 9 hours total to do this separately.
  + Make a video from 12.19 to 12.23. Spend 3-5 hours to make a video.

