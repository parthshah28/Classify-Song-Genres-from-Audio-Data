# [Classify-Song-Genres-from-Audio-Data](https://github.com/parthshah28/Classify-Song-Genres-from-Audio-Data)
Using a dataset comprised of songs of two music genres (Hip-Hop and Rock), I trained a classifier to distinguish between the two genres based only on track information derived from Echonest (now part of Spotify).I applied data preprocessing, dimensionality reduction and machine learning algorithms using scikit-learn package.

## Datset
Download dataset from [here.](https://github.com/parthshah28/Classify-Song-Genres-from-Audio-Data/tree/master/dataset)  

## Correlation Matrix
![](https://github.com/parthshah28/Classify-Song-Genres-from-Audio-Data/blob/master/images/Screenshot%202020-09-29%20232734.png)

## Explained Variance Ratios from PCA using all features
![](https://github.com/parthshah28/Classify-Song-Genres-from-Audio-Data/blob/master/images/Screenshot%202020-09-29%20232913.png)

## Cumulative Explained Variance plot
![](https://github.com/parthshah28/Classify-Song-Genres-from-Audio-Data/blob/master/images/Screenshot%202020-09-29%20232955.png)

## Model Building
First, I Normalized feature data. I also split the data into train and test sets.

I tried two different models and evaluated them using Cross Validation Score. I chose CV to get a good sense of how well our models are actually performing.

I tried two differnet models:
  1. Decision Tree Classifier
  2. Logistic Regression
  
## Model Performance
The Logistic Regression model is working better than Decision Tree Model on the test and validation sets.
### Decision Tree: 0.7241758241758242 
### Logistic Regression: 0.7752747252747252
