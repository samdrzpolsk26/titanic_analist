# titanic_analist
In this project, I conducted a comprehensive analysis of the famous Titanic dataset, with the aim of predicting passenger survival using machine learning techniques. This analysis not only demonstrates my ability to clean and preprocess data, but also my ability to apply and evaluate various classification models."

Exploratory Data Analysis (EDA):

"I started with a detailed exploratory analysis to better understand the data and discover relevant patterns:

Age Distribution: I used a histogram to visualize the age distribution of the passengers, which allowed me to identify the presence of children and older adults on the ship.
Survival by Class: Using a bar graph, I examined the relationship between passenger class and survival rate, revealing that first-class passengers had a higher probability of survival.
Correlation Matrix: A heat map of the correlation matrix helped me identify the variables that have the greatest influence on survival, such as sex and class."
Data Preprocessing:

"Preprocessing was a crucial step in preparing the data for modeling:

Handling of Null Values: I imputed the missing values in the 'Age' column with the median and removed the 'Cabin' column due to the large number of missing values.
Encoding of Categorical Variables: I used one-hot encoding to convert the categorical variables 'Sex' and 'Embarked' into numerical variables, which is essential for many machine learning algorithms.
Feature Selection: I removed irrelevant columns such as 'Name', 'Ticket' and 'PassengerId' to avoid the curse of dimensionality and improve model performance."
Modeling and Evaluation:

"I implemented and compared three classification models to predict survival:

Logistic Regression: A linear model that serves as a baseline for comparison.
Random Forest: An ensemble model that often provides good performance in classification problems.
XGBoost: Another ensemble model known for its high accuracy and efficiency.
Neural Networks: I implemented a neural network using TensorFlow/Keras to explore more complex models.
I evaluated the performance of the models using metrics such as accuracy, precision, recall and F1-score. In addition, I used cross-validation to obtain a more robust estimate of model performance."

Results and Conclusions:

"The results showed that the Random Forest and XGBoost models achieved the best performance, with an accuracy of around 82%. This demonstrates the effectiveness of the ensemble models for this type of problem. The neural network also showed competitive performance, validating the importance of exploring different model architectures.

This project allowed me to apply and improve my skills in data cleaning, exploratory analysis, feature engineering and predictive modeling. In addition, it provided me with valuable experience in the comparison and evaluation of different machine learning algorithms."
