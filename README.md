# 626midterm1
Find the best algorithm that gives the best performance

# Introduction
The goal of this project is to find the best performing algorithm in binary and multi-class classifications. The chosen algorithms were submitted into the leaderboard to see the actual accuracy. We will mainly focus on Random Forest and SVM because these two algorithms had the highest accuracy and were submitted to the leaaderboard.
This project contains two data files, one for training and the other for testing. The data contains information about various activities performed by subjects, and the goal is to classify these activites as either static or dynamic (binary classification) or as one of seven activity types (multi-class classification).

# Data
The data files used are 'training_data.txt' and 'test_data.txt'.

# Methodology
1. Binary Classification : The first part of the project builds a binary classifier to classify the activity of each time window into static (0) and dynamic (1). Random Forest and Support Vector Machine (SVM) are used.
2. Multi-class classification task : The second part of the project builds a multi-class classifier to classify walking (1), walking_upstairs (2), walking_downstairs (3), sitting (4), standing (5), lying(6), and static posutural transition (7-12).

# Results
For both binary and multi-class classification, SVM performs better than the Random Forest algorithm for this project.
The following are the accuracies for each classification :
1. Binary Classification : 
Random Forest : accuracy = 
SVM : accuracy = 
2. Multi-Class Classification
3. 1. Binary Classification : accuracy = 
4. Random Forest : accuracy = 


# Conclusion
The result of this project is that SVM is a better choice for both binary and mutli-class classification. Or in other words, SVM is a better choice for classifying activities as either static or dynamic (binary classification) and for classifying activites into one of the seven categories (multi-class classification). However, more experiments in different algorithms are needed to enhance the final accuracy.


# Instructions to run the code
1. Clone the repository to your local machine
2. Open 'SVM.Rmd' and 'RandomForest.Rmd" in RStudio.
3. Run the code
4. The output will be displayed in the R console

