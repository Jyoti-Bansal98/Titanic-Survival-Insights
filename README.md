Titanic Survival Prediction

A machine learning project to predict whether a passenger survived the Titanic disaster or not.
The project involves data cleaning, exploratory data analysis (EDA), feature engineering, and building classification models to achieve reliable survival predictions on the famous Kaggle Titanic dataset.

📂 Dataset

Source: Kaggle Titanic Dataset
Target Variable: Survived (0 = Did not survive, 1 = Survived)

Features:

PassengerId
Pclass (Ticket class)
Name, Sex, Age
SibSp (# of siblings/spouses aboard)
Parch (# of parents/children aboard)
Ticket, Fare, Cabin, Embarked

Tools & Libraries:

Python 
NumPy, Pandas → Data manipulation
Matplotlib, Seaborn → Data visualization
Scikit-learn → Machine Learning models
Jupyter Notebook 

🔍 Exploratory Data Analysis (EDA)

Key steps performed:

Handling missing values (Age, Cabin, Embarked)
Visualizing survival rates across different features:
Gender vs Survival
Passenger Class vs Survival
Age distribution of survivors vs non-survivors
Detecting outliers and skewness in numerical data

📊 Example insight:

Women had a much higher survival rate than men.
Passengers in 1st class survived more often than those in 3rd class.

🧹 Data Preprocessing

Encoding categorical variables (Sex, Embarked)
Creating new features (e.g., Family Size = SibSp + Parch + 1)
Scaling numerical values
Splitting dataset into train/test

Results & Insights

Achieved ~82% accuracy on the test dataset.
Women and children had significantly higher survival chances.
Higher ticket class = higher probability of survival.
