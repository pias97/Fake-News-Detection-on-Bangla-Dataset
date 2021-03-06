# Fake-News-Detection-on-Bangla-Dataset

## Table of Contents:
### 1. Description
### 2. Dataset
### 3. File Description
### 4. Classifiers
### 5. Evaluation



### 1. Description:
This is a simple implementation of a paper named `Detection of Bangla Fake News using MNB and
SVM Classifier` for my University's Course `Machine Learning`.
>Authors : Md Gulzar Hussain, Md Rashidul Hasan, Mahmuda Rahman, Joy Protim and Sakib Al Hasan.

This project was built using two of the most popular Machine Learning Technique named SVM and MNB.
It is a classification-based supervised learning project. 
Both [`bnlp_Toolkit`](https://pypi.org/project/bnlp-toolkit/) and Manually created [`Stopwords`](https://www.ranks.nl/stopwords/bengali) list were used for different approach.  
Natural Language Processing technique like TF-IDF also used for feature extraction. 


### 2. Dataset:

The Dataset is collected from [Github](https://github.com/gulzar09/Bangla_Fake-Real_News_Small_Dataset) and the language of the dataset is Bangla. 

### 3. File Descriptions:
1. `FinalData1.csv` - the whole dataset
2. `Real` - 1548
3. `Fake` - 993   

### 4. Models:
1. `TF-IDF` - TF-IDF is a very popular feature extraction technique. Text needs to converted into vector or matrix before fed them to the Machine Learning model.  
2. `Support Vector Machines`
3. `Multinomial Naive Bayes`  

### 5. Evaluation
1. `Confusion Matrix`
2. `Accuracy` 
3. `F1 Score` 
