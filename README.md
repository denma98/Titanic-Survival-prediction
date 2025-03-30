# Titanic Survival Prediction

![Titanic](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/1200px-RMS_Titanic_3.jpg)

A machine learning project to predict passenger survival on the Titanic using various features like age, gender, ticket class, etc.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)

## Project Overview
This project implements a machine learning pipeline to:
- Preprocess Titanic passenger data
- Handle missing values and categorical variables
- Train multiple classification models
- Evaluate performance using various metrics
- Analyze feature importance

## Dataset
The dataset contains information about 891 Titanic passengers with the following key features:

| Feature      | Description |
|--------------|-------------|
| Survived     | Survival (0 = No, 1 = Yes) |
| Pclass       | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| Sex          | Gender |
| Age          | Age in years |
| SibSp        | Number of siblings/spouses aboard |
| Parch        | Number of parents/children aboard |
| Fare         | Passenger fare |
| Embarked     | Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

**Missing Values Analysis:**
- Deck 78.2%
- Cabin 78.2%
- Age 20.6%
- AgeGroup 20.6%
- Fare 0.2%
- FareGroup 0.2%

  
## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/titanic-survival-prediction.git
cd titanic-survival-prediction
jupyter notebook titanic_survival_prediction.ipynb
