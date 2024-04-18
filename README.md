In this project our main goal is to "predict the football match winners".
First of all we can import the data set(visit kaggle).
Reference-"https://www.youtube.com/watch?v=0irmDBWLrco"
Next is the most important step,that is data cleaning and preprocessing.Here we can handle null values,data types(if there is any wrong format data).
Then we can implement random forest for further process,Random forest which is a supervised learning algorithm used for classification as well as regression.
Also random forest is an ensembling learning technique,it combines the predictions of multiple individual models to produce more accurate results.
Then find the accuracy using evaluation metrics,it is used to assess the performance of thee model.
In our project we got the "Accuracy=0.6195652173913043".This indicates that the model correctly predicted the outcome of approximately 61.96% of the samples in the dataset.
Then create an another data frame from the existing one ,that is named as "combined".This creates a python dictionary,where keys are actual and prediction,and the values are test['target'] and y_pred.
Then create a cross tab that is a frequency table that shows the distribution of one variable in rows and another variable in column.
Then we find precision,which is the ratio of "True Positive/True Positive+False Positive",Here we got a precision="0.49333333333333335".So we move to the next step.
Find rolling averages,that is also known as moving averages,this is used to analyze the data points by creating a series of averages of different subset of the whole data set.
This time we got the value of "precision=0.5576923076923077",it is little bit improved.
Then we can saw that the same names are differently written in 'team' and 'opponent',we can change that and put a same name for both by using a dictionart.
Again we can find precision,that is equal to 0.5714,better than the previous time.
