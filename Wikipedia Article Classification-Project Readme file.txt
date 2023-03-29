1.Imported the necessary libraries
2.converted the csv file with sample of 5014 articlesnames and class into dataframe
3.Created new columns from the articles name using wikipediaapi and nltk
4.Removed the unneccesary columns
5.searched the columns as if they have any missing values .
6.searched for the outliers of each column and imputed them
7.plotted each features realtionship with others using pairplot
8.plotted each feature relation with the target whther to remove the feature if it has no relation with target
9.created train and test data with ratio 3:1
10.created models using RandomForestclassifier,AdaboostClassifier,logisticRegression,supportvectorClassification and did prediction and found out the accuracy for each model and feature importance for best model.