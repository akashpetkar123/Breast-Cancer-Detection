# Breast-Cancer-Detection
A Simple Analysis of Breast Cancer Detection on a given dataset.
The dataset is free and can be easily downloadable also i have attached the datset with the project.
The dataset consist of 569 rows and 32 columns. It consist of patint information such as diagnosis, radius_mean, texture_mean, perimeter_mean, area_mean etc columns which consist of values.
we use numpy, pandas, matplotlib, seaborn and sklearn libraries for this detection

we split the data into two ratio i.e training data and testing data
Training data is the data which we used to train the model i.e we feed the value so model could predict 
Testing data is the data whic we used to chek the values how data it is correctly predicting

we plot the data using seaborn's heatmap,countplot, pairplot to get the idea how values are represented in 2D for a single row against that column.
we then put data in X_train, Y_train where
X_train will have all the values which is used to identify whether a person has cancer or not i.e from 2 to 30 column
Y_train will have the value which has diagnosis whether a whether a person has cancer or not i.e 1 column
we then split this data using train_test_split of sklearn.model_selection into 75% to 25% and also scales the values

We then feed these values to a number models such as Logistic regression, Random forest, decision tree, SVM linear and SVM RBF classifer to train these values. After training the data we check the accuracy of each model which is giving better.
LogisticRegression Accuracy= 0.9906103286384976
DecisionTreeClassifier Accuracy= 1.0
RandomForestClassifier Accuracy= 0.9953051643192489
SVM Linear Accuracy= 0.9882629107981221
SVM RBF Accuracy= 0.9835680751173709

There is a confusion_matrix function of sklearn.metrics which is used to find the TruePositive, TrueNegative, FalsePositive, FalseNegative which is used to describe the performance of a model. It allows the visualization of an model.

Each classifer has its own values and we can print the values of each model its precision and recall values
Precision is used to measure the exactness of the data
Recall is used to most of the values given are correctly predicted.

For simply understanding please find the code and datasets attached. 

