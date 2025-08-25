# titanic-survival-ml-pipeline
Titanic survival prediction with a reproducible ML pipeline. Includes EDA, preprocessing, feature engineering (Age, Embarked, Fare, Name, Parch, Pclass, Sex, SibSp), modeling with Random Forest, and evaluation (Accuracy : 0.8212; classification report &amp; confusion matrix). Notebook-driven workflow.



# 🚢 Titanic Survival Prediction

This repository contains a machine learning pipeline to predict passenger survival on the Titanic dataset.  
The project includes **EDA, preprocessing, feature engineering, model training, and evaluation**.

## 📌 Dataset
- **train.csv** used for training and evaluation.
- Features used in the project:
  - Age
  - Embarked
  - Fare
  - Name
  - Parch
  - Pclass
  - Sex
  - SibSp
  - Title

## 🧠 Model
- **Random Forest Classifier**

## 📊 Results
- **Accuracy:** 0.8212 (approx 82%)  
- **Evaluation:** Classification Report + Confusion Matrix

## 🛠️ Tech Stack
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  

## ▶️ How to Run
```bash
git clone https://github.com/WaleedAfridi-1/titanic-survival-ml-pipeline.git
cd titanic-survival-ml-pipeline
pip install -r requirements.txt
jupyter notebook titanic.ipynb
```

## 📈 Workflow
1. Load and inspect dataset
2. Handle missing values
3. Perform feature engineering
4. Train Random Forest Classifier
5. Evaluate with accuracy, classification report, and confusion matrix

## 👤 Author
**Waleed Afridi**
