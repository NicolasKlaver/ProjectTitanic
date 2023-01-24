# Project Titanic Python


## Introduction
The objective of this Project is apply Machine Learning techniques to predicts which passengers survived the Titanic  Shipwreck.


### Libraries
- Pandas, Numpy, Sklearn, Matplotlib, Seaborn


### Skills used
- Data Analysis
- Feature Engineering
- Data Visualization
- Data Cleaning
- Machine Learning


## The Data
- **train.csv:** contains the details of a subset of the passengers on board.
- **test.csv:** should be used to see how well your model performs on unseen data. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.


### Files:
- Titanic_P1.ipynb: Data Analysis, Feature Engineering and Data Visualization
- Titanic_P2.ipynb: Machine Learning



# Reviewing the topics of the Project

## Data analysis 
- First look to the data
![](https://github.com/NicolasKlaver/Project_Titanic_Survivor/blob/main/img/analysis_sample.png)


- Data Types

  ![](https://github.com/NicolasKlaver/Project_Titanic_Survivor/blob/main/img/types.png)

**Numerical Features:**
- Continuous: Age and Fare
- Discrete: SibSp and Parch

**Categorical Features:**
- Survived, Sex, Embarked and Pclass

**Alphanumeric Features:**
- Ticket and Cabin




**Describe**
![](https://github.com/NicolasKlaver/Project_Titanic_Survivor/blob/main/img/describe.png)

Notes:
- There are a total of 891 passengers in our training set.
- The Age feature is missing approximately 19.8% of its values.
- I'm guessing that the Age feature is pretty important to survival, so we should probably attempt to fill these gaps.
- The Cabin feature is missing approximately 77.1% of its values.
- Since so much of the feature is missing, it would be hard to fill in the missing values. We'll probably drop these values from our dataset.
- The Embarked feature is missing 0.22% of its values, which should be relatively harmless.





## Feature Engineering and Data Visualization (Age Feature)
![](https://github.com/NicolasKlaver/Project_Titanic_Survivor/blob/main/img/feature.png)

![]()

Notes:
- Babies are more likely to survive than any other age group.




## Machine Learning
- We will use part of our training data to test the accuracy of our different models.
![](https://github.com/NicolasKlaver/Project_Titanic_Survivor/blob/main/img/training.png)


- Let's compare the accuracies of each model
![](https://github.com/NicolasKlaver/Project_Titanic_Survivor/blob/main/img/model_accuracy.png)
