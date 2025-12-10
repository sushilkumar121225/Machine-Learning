# Lasso Feature Selection Practical

🚀 Project Overview

This project demonstrates feature selection using Lasso Regression (L1 Regularization) in Python. Lasso helps in identifying important features while shrinking less significant features to zero, which reduces model complexity and improves interpretability.

📌 Objective

Apply Lasso Regression on a dataset to predict the target variable (marks).

Identify important features and remove irrelevant ones automatically.

Visualize relationships and model performance using graphs and ASCII outputs.

🛠️ Technologies Used

Python 3.x

Libraries:

pandas → Data handling

scikit-learn → Lasso Regression, scaling, train-test split

numpy → Numerical operations

matplotlib & seaborn → Graphs & visualizations

pyfiglet → ASCII art for titles

📁 Dataset

CSV File: data.csv

Features:

Column	Description
hours	Daily study hours
study	Weekly study sessions
age	Student age
sleep	Sleep hours per day
marks	Final exam score (Target)

Sample Data (10 rows):

hours,study,age,sleep,marks
2,3,17,6,45
5,6,18,7,78
7,8,17,5,90
1,2,16,8,30
4,5,18,6,70
6,7,17,7,88
3,4,16,6,55
8,9,18,5,92
2,3,17,7,48
5,6,18,6,80

📝 Steps Performed

Load Dataset from CSV using Pandas.

Split Features and Target (X and y).

Train-Test Split (70% train, 30% test).

Standard Scaling for better performance with Lasso.

Apply Lasso Regression to select important features.

Display ASCII Output of coefficients, selected & removed features.

Evaluate Model using R² score.

Visualizations:

Correlation Heatmap

Feature Importance Bar Graph

Before vs After Feature Shrinkage Plot

Actual vs Predicted Graph

Residual Plot

Lasso Coefficient Path Graph

💻 How to Run

Clone or download this repository.

Make sure Python 3.x is installed.

Install required libraries:

pip install pandas scikit-learn matplotlib seaborn pyfiglet


Place the dataset data.csv in the same folder as the script.

Run the script:

python lasso_feature_selection.py


Observe ASCII outputs in terminal and graphs in separate windows.

🧪 Sample ASCII Output
============= LASSO COEFFICIENTS TABLE =============
hours                --> 0.7421
age                  --> 0.0000
study                --> 0.6543
sleep                --> 0.0000

============= IMPORTANT FEATURES (NON-ZERO) =============
[SELECTED]  hours  --> Weight: 0.7421
[SELECTED]  study  --> Weight: 0.6543

============= DROPPED FEATURES (ZERO COEFFICIENT) =============
[REMOVED]  age   --> Weight: 0.0000
[REMOVED]  sleep --> Weight: 0.0000

================ MODEL PERFORMANCE ================
Lasso Model R^2 Score: 0.8221

📊 Graphs

Correlation Heatmap – Feature relationships

Feature Importance – Lasso coefficient weights

Before vs After Shrinkage – Effect of L1 regularization

Actual vs Predicted – Model performance

Residual Plot – Error spread

Lasso Alpha vs MSE – Optimal alpha selection

⚡ Benefits of Lasso Feature Selection

Removes irrelevant features automatically

Reduces model complexity

Improves interpretability of the model

Helps avoid overfitting


-----------------------------------------------------------------------------------------------------------
                                                Follow Me
-----------------------------------------------------------------------------------------------------------
🤝 Contributing
Feel free to fork the repository, improve the project, and submit a pull request.

🔗 Connect With Me
If you want to see more ML projects, tutorials, and updates, follow me on:
GitHub: https://github.com/sushilkumar121225
LinkedIn: https://www.linkedin.com/in/sushil-kumar-471614289/

🙌 Thank You for Visiting This Repository!
Happy Learning and Keep Exploring Machine Learning 🚀
