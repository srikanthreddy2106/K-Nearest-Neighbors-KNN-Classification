# K-Nearest-Neighbors-KNN-Classification

In this project, we implemented the K-Nearest Neighbors (KNN) Classification algorithm using the Iris dataset. The primary objective was to classify different species of Iris flowers based on their sepal and petal measurements.

We started by loading the dataset using Pandas and performed basic data cleaning by dropping the unnecessary Id column. To prepare the target variable (Species) for the model, we used Label Encoding to convert categorical labels into numeric form. Next, we normalized the feature variables using StandardScaler from Scikit-learn to bring all features to a common scale, improving model performance.

The dataset was then split into training and testing sets using train_test_split. We used the KNeighborsClassifier from Scikit-learn to build the model. Different values of K (number of neighbors) were tested to observe how it affects the accuracy of predictions. We plotted accuracy vs K values to select the best-performing K.

For evaluation, we calculated the accuracy score, confusion matrix, and classification report to check the model's performance. Finally, we visualized the decision boundaries using the first two features of the dataset to understand how the KNN algorithm separates different classes in feature space.
