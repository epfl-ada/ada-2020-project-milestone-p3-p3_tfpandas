##P3-Extension
### 1. Predicting the betrayal using the interaction between variables.

### 2. Abstract

In our project, we decide to use the dataset the same as the one we are given. Our goal is to predict whether a player will betray or not using the interaction between variables.
We found that in the paper, they only study the imbalance within each variables. In our opinion, it is a waste to only use an average value in explaination and prediction.
In our project, we want to extend their analysis by analyzing the interaction betweeen these variables. We guess when people betray, they might speak more while be more polite, 
or they would speak less while more impolite. We think there is an underlying correlations within these variables. We also want to use different techniches in machine learning
like SVM or deep learning to increase the accuracy of prediction.

### 3. Research Questions
 + Is the interaction between some variables related to the probability of betrayal?
 + Can we add these interaction to increase the accuracy of prediction?
 + Can we increase the accuracy of prediction by using different models in machine learning like random forest?

### 4. Proposed dataset
  We decide to use the dataset given by the paper. There are two main reasons we do this:
  + The first reason is to reduce unnecessary work. It is hard to find enough dataset for such an old game. It also take too much time to process the data. For example, we might 
  spend extra time in learning Standford politeness test.
  + Another reason is that we can compare our result with the original paper directly. If we use different dataset, we might have high probability have different result due to 
  different preprocessing and different data. It is more convincing to say our model is better if our method increases the accuracy.

### 5. Methods
  + We will first explore if there is correlation between each pair of variables using Pearson coeficient. The interaction between variables we will look into are talkativeness and politeness, talkativeness and sentiment, number of request and politeness, number of request and sentiment. We will then use statistics test to find if the interaction between variables are helpful for predicting. 
  + We add these interaction to see if we can increase the accuracy of the result based on their model.
  + Finally, we will try other methods in machine learning like SVM, random forest and deep learning to do the task, see if we can achieve a higher accuracy.

### 6. Proposed timeline
  + First discussion in 11.28. Spent 10 hours to replicate the original paper, extract the necessary variables we will use from the data.
  + Second discussion in 12.05 & 12.06 . Spent 15 hours to extend our result.
  + Fix buges and write report 12.07 - 12.13. Spent 9 hours total to do this separately.
  + Make a video 12.14 - 12.18. Spend 3-5 hours to make a video.

### 7. Organization within the team
A list of internal milestones up until project milestone P4. Add here a sketch of your planning for the next project milestone.

  + Week 1: Yuanhui will be responsible for extracting all the needed variables from the json data, return as a pandas dataframe for later usage. Yehao and Hangqian will use the data to explore the correlation bettween each pair of variables mentioned before. If time allowed, more pairs of variables will be examined. 
  + Week 2: Yehao will implenment the logistic regression model used in the paper with extra variables which are the meaningful interactions. We analyze the result, see if adding interactions is helpful for predicting betrayal. The three of us will start to use different machine learning methods to do the prediction.
  + Week 3: Get results from our different methods, analyze the result. Start to write report and make video.
  
### 8. Questions for TAs (optional)
No question right now.
