# Cardio-Good-Fitness-Statistics-EDA
The plan to collect from indivisuals who purchased the treadmil at a CardioGoodFitness store during prior 3 months. The data are stored in the CardioGoodFitness.csv file.

One Market reasearcher team is assigned the task to identify the profile to typical customer for each treaddmil product offered by the cardiogoodfitness. The team decides to investigate whether there is any difference across the product with respect to the customer charactaristics.

They plan to collect from indivisuals who purchased the treadmil at a CardioGoodFitness store during prior 3 months. The data are stored in the CardioGoodFitness.csv file.
## The team identifies the following customer variables to study:
product purchased
gender
age in years
education
relationship status
annual household income
avg number of times customer plans to use treadmil per week
avg number of times customer expect to walk/run each week
self rated fitness on1-to-5 scale where 1 is poor and 5 is excellent shape

So, one question might be rising for you now is why "Education" column value is containing floating point value in this dataframe.

its because, it sees the other column values and find out that "Income" column value is presented in floats. So, its(means the software) sort of says that what granularity do i need to store the data. So, if you will see carefully all the data has been stored in folating point columns are having saame amount of nos after (.) that is 6. Total 6 digits are present after (.)

In this description function, As i have mentioned "include= 'all'" means its showing me everything including the NAN rows. In the index column you can see values like min, max, count, top etc..

As we can see from the dataframe, 50% of the people are aged 26. So, meadian is 50% and age is 26.

Now for Mean= 1/n(X1 + X2 + X3 ...........+Xn)
Here n = 180 as we have 180 rows and 9 columns.

If we will see Mean age is already caluclated that is 28.788889 ~ 28.8 . The Avg age of the person is 26.

Median: Age of the avg. person. Mean: Avg. age of a person.

If you are confused, please go through these two lines again and watch the DataFrame, you will find out your answer.

As we can see, from age 18 to 26, 50% of the total no. covered means out of 180 people 90 people are from age 18 to 26 and other 90 people are from age 26 to 50.
