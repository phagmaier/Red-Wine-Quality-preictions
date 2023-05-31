# Red-Wine-Quality-preictions
Predicting the quality of red win

# OVERVIEW
Using a random forest to predict the quality of red win. Several of the qaulities of wine are severley under represented so we had to oversample the undersampled classes. We also attempt to normalize some of the more skewed data.

## IMPROVE
Because we do not have a lot of data and the some of the quality ratings are so sparse the oversampaling actually negativley impacts the results of the random forest so we either need to group some of the ratings together find a better solution to the sparse data and or use a different type of algorithm to classify the data. This is just a first attempt will come back and improve when i have the time. Grouping them together seeems like an obvious solution possibly turning it into a binary classification problem for 'good' and 'bad quality wine. Not the best data set.

## DATA SOURCE:
https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009
