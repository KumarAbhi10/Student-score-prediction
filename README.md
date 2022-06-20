# Student-score-prediction
Predicting the percentage of a student based on total hours of study in a day.
First we import all libraries required such as pandas, numpy, patplotlib.pyplot.
Then we read the data from remote link and import it successfully.
After that we plot the distribution of scores in the format of hours vs persentage.
Then we import from sklearn.model_selection import train_test_split to train our model.
From sklearn.linear_model import LinearRegression we define our regressor and complete our training.
Then we plot the regressor line and plot the tested data.
Finally we compare Actual vs Predicted data.
Then in the end we can test the scores for our own data, such as we tested for the data 9.25, i.i what will be the percentage of the student if he/she studies for 9.25 hrs per day?
We add our own data for for testing the results, and we get the accuracy/score for the added value.
Also we can calculate the mean absolute error for the data and score.
