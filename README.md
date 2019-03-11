# ClassificationUsingKNN
Using the Verterbal Data set, performing Binary Classification to classify the data to labels Normal,NO=0 or Abnormal,AB=1
Begin with pre-processing and exploratory data analysis
  Analysed the scatterplots and boxplots for the independednt variables
 Splitting the data into train and test as, first 70 rows of Class 0 and the first 140 rows of Class 1 as the
training set and the rest of the data as the test set.

Implementation of KNN
  Peformed classification for k-nearest neighbors with Euclidean metric.
  Tested all the data in the test database with k nearest neighbors. Take decisions by majority polling.
  Computed the confusion matrix, true positive rate, true negative rate, precision,
  and F-score when k = k*
  Plotted a Learning Curve
  
 Variants of KNN using 
  Minkowski Distance
  Manhattan Distance
  Chebyshev Distance
  Mahalanobis Distance
  
The majority polling decision can be replaced by weighted decision, in which the
weight of each point in voting is proportional to its distance from the query/test
data point. In this case, closer neighbors of a query point will have a greater
influence than neighbors which are further away. 
Used weighted voting with Euclidean, Manhattan, and Chebyshev distances and report the best test errors.

Analysed the lowest training error in the project.
 
