# Iris-Flower-Species-Classification-Using-K-Nearest-Neighbors

## Aim:
The aim of this project is to classify iris flower species based on their petal length, petal width, sepal length, and sepal width using the K-Nearest Neighbors algorithm.

## Description:
In this project, we use the Iris dataset, which contains measurements of 150 iris flowers from three different species: setosa, versicolor, and virginica. We begin by loading the dataset and performing some initial data exploration.

Next, we preprocess the data by mapping the species names to numeric values and splitting the dataset into input features (X) and target variable (y). We then create a K-Nearest Neighbors classifier and fit it to the training data.

To visualize the classification boundaries, we create a meshgrid and predict the species for each point on the grid. We plot the meshgrid as a contour plot and overlay the actual data points, color-coded by their true species.

We further analyze the relationship between sepal length and width, as well as petal length and width, for setosa and versicolor species. We plot scatter plots for each combination to observe any discernible patterns or differences between the two species.

Next, we split the data into training and testing sets and perform K-Nearest Neighbors classification on the training set. We evaluate the accuracy of the model on the test set and calculate a confusion matrix to assess the performance of the classifier.

To optimize the hyperparameters of the K-Nearest Neighbors model, we use GridSearchCV to perform a grid search over a range of values for the number of neighbors and distance metric. We find the best estimator based on cross-validated performance.

Finally, we create a new K-Nearest Neighbors classifier with the optimized hyperparameters, fit it to the training data, and evaluate its accuracy on the test set. We also make a sample prediction using the classifier.

## Conclusion:
In this project, we successfully classified iris flower species using the K-Nearest Neighbors algorithm. By analyzing the scatter plots, we observed distinct patterns between the sepal and petal measurements of setosa and versicolor species. The K-Nearest Neighbors classifier achieved an accuracy of 96% on the test set.

Through the grid search, we optimized the hyperparameters and selected the best estimator, which further improved the model's performance. The optimized K-Nearest Neighbors classifier achieved the same accuracy of 96% on the test set.

Overall, this project demonstrates the effectiveness of the K-Nearest Neighbors algorithm for classifying iris flower species based on their measurements.
