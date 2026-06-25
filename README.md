TITANIC SURVIVAL PREDICTION (ML BASICS)

Intern Name: BIROOR HASINI

Intern ID: KDINT259136

COMPANY: KODBUD

DOMAIN: DATA SCIENCE

College Name: Malla Reddy College for Women

Duration: 18 June 2026 - 16 July 2026

Project Name: Titanic Survival Prediction

Introduction

Machine Learning is widely used to solve classification problems by predicting outcomes based on historical data. In this project, the famous Titanic dataset is analyzed to predict whether a passenger survived or not during the Titanic disaster. Logistic Regression is used as the classification algorithm to build the prediction model. The project demonstrates data preprocessing, feature selection, model training, evaluation, and visualization techniques.

Objective

The main objectives of this project are:

* Analyze the Titanic passenger dataset.
* Clean and preprocess the data.
* Handle missing values and categorical features.
* Select important features affecting survival.
* Train a Logistic Regression model.
* Predict passenger survival.
* Evaluate model performance using classification metrics.
* Visualize important insights from the dataset.

Dataset Description

The Titanic dataset contains passenger information with the following attributes:

* PassengerId
* Survived
* Pclass (Passenger Class)
* Name
* Sex
* Age
* SibSp (Number of Siblings/Spouses)
* Parch (Number of Parents/Children)
* Ticket
* Fare
* Cabin
* Embarked

Target Variable:

* Survived

  * 0 = Did Not Survive
  * 1 = Survived

Tools and Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook
* GitHub

Data Preprocessing

The following preprocessing steps were performed:

1. Downloaded the Titanic dataset from Kaggle.
2. Loaded the dataset using Pandas.
3. Checked for missing values.
4. Filled missing Age values using the median.
5. Filled missing Embarked values using the mode.
6. Removed unnecessary columns such as Cabin, Name, Ticket, and PassengerId.
7. Converted categorical variables into numerical values.
8. Verified data types.
9. Split data into training and testing sets.
10. Prepared the dataset for model training.

Exploratory Data Analysis

6.1 Survival Distribution Analysis

The distribution of survived and non-survived passengers was analyzed.

Observation:

* More passengers did not survive than survived.
* The dataset shows class imbalance.
* Survival patterns can be observed across different passenger groups.

6.2 Gender-wise Survival Analysis

Passenger survival was compared based on gender.

Observation:

* Female passengers had a significantly higher survival rate.
* Male passengers experienced higher mortality.
* Gender played an important role in survival prediction.

6.3 Passenger Class Analysis

Survival rates were analyzed across passenger classes.

Observation:

* First-class passengers had the highest survival rate.
* Third-class passengers had the lowest survival rate.
* Passenger class strongly influenced survival chances.

6.4 Age Analysis

Passenger age distribution was examined.

Observation:

* Young adults formed the largest age group.
* Children showed relatively better survival rates.
* Age contributed to survival prediction.

6.5 Fare Analysis

Passenger fares were analyzed.

Observation:

* Higher fare passengers generally had better survival rates.
* Fare reflects socio-economic status.
* Fare was an important predictive feature.

 6.6 Feature Correlation Analysis

Relationships among features were analyzed.

Observation:

* Sex and Pclass showed strong correlation with survival.
* Fare had moderate influence on survival.
* Correlation analysis helped identify important features.

 Model Building

The Logistic Regression model was used for classification.

Steps:

1. Selected relevant features.
2. Split data into training and testing datasets.
3. Trained the Logistic Regression model.
4. Predicted survival outcomes on test data.
5. Evaluated model performance.

Model Evaluation

The following evaluation metrics were used:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score

Observation:

* The Logistic Regression model achieved good prediction accuracy.
* The confusion matrix provided insight into classification performance.
* Evaluation metrics confirmed the effectiveness of the model.

Data Visualization

The following visualizations were created:

* Survival Count Plot
* Gender-wise Survival Bar Chart
* Passenger Class Survival Chart
* Age Distribution Histogram
* Fare Distribution Plot
* Correlation Heatmap
* Confusion Matrix Visualization

These visualizations helped understand the factors affecting passenger survival.

Results

The analysis revealed:

* Gender was one of the strongest factors influencing survival.
* First-class passengers had higher survival rates.
* Higher fare passengers were more likely to survive.
* Logistic Regression successfully predicted passenger survival.
* Data visualization highlighted important survival trends.
* Feature analysis improved understanding of passenger characteristics.

Conclusion

The Titanic Survival Prediction project successfully demonstrated the use of Machine Learning for classification tasks. Through data cleaning, feature engineering, exploratory analysis, model training, and evaluation, meaningful insights were obtained regarding passenger survival patterns. Logistic Regression provided reliable predictions and helped identify the most influential factors affecting survival.

Future Scope

* Apply advanced classification algorithms such as Random Forest and XGBoost.
* Perform hyperparameter tuning for improved accuracy.
* Develop a web application for real-time predictions.
* Use feature engineering techniques for better performance.
* Compare multiple machine learning models and evaluate their effectiveness.

References

* Kaggle Titanic Dataset
* Scikit-learn Documentation
* Pandas Documentation
* Matplotlib Documentation
* Seaborn Documentation
* Python Documentation
<img width="1857" height="1043" alt="image" src="https://github.com/user-attachments/assets/c4ab0687-0d74-45cd-864f-c575873e8945" />
<img width="1850" height="1025" alt="image" src="https://github.com/user-attachments/assets/a723a5ce-07cf-46b0-8d6d-1d7afba2f5ea" />
<img width="1737" height="880" alt="image" src="https://github.com/user-attachments/assets/41674c92-01c9-4990-80f7-d0af93d4c8dc" />
<img width="1852" height="996" alt="image" src="https://github.com/user-attachments/assets/2813a8c3-06d5-4c38-99eb-030fb597d44d" />
