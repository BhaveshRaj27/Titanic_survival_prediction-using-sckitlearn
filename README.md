# Titanic_survival_prediction-using-sckitlearn
The Titanic_survival_prediction is one of the classic problem. The prediction is done on the different parameters such as age, gender, seat, class of passenger or cost of tickets passenger ID etc. The problem is perfect combination of practicing various segments of machine learning like working with .csv file, feature extarction, data cleaning, working with missing values, one hot encoding etc. 

![](https://github.com/BhaveshRaj27/Titanic_survival_prediction-using-sckitlearn/blob/master/Image/tenor.gif)

# Dataset 
The dataset is in the form of csv.Download the dataset from here https://www.kaggle.com/c/titanic/data the data format is shown below.

![](https://github.com/BhaveshRaj27/Titanic_survival_prediction-using-sckitlearn/blob/master/Image/datacopy.png)


# Step to follow 
1. Download the dataset and use pandas library to access the .csv file.
2. Clean the dataset, assign new value to the place where value is not present. You can use mean, median or any other method to fill the blank points. Also can use one hot encoding to convert the alphabet or column with language into feature or numeric form. 
3. I used random forest here as it is a quite robust technique for the supervise classification. The random forest work on predict answer using multiple decision trees and each decision tree use different batch of dataset to train and the average of all the tree is return as the answer. Random forest is generally used to prevent overfitting as in the case of decision_tree classifier.

![](https://github.com/BhaveshRaj27/Titanic_survival_prediction-using-sckitlearn/blob/master/Image/Randomforest.png)


# Result 
The accuracy I got is about 98% which is quite good higher value may be achieved by tunning the parameter more.
