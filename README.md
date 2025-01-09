Overview:
This project involves building a classification model to predict truck de-fleeting decisions using a supervised machine learning approach. The model aims to uncover patterns in truck usage and assist in fleet
optimization.

Dataset:
The dataset, defleet_truck_dataset.csv, contains randomized data representing various truck attributes such as mileage, age, and service history. It should be noted that the randomization introduces noise, 
making it challenging to achieve a high accuracy score. However, this project serves as a demonstration of the modeling workflow rather than a production-ready solution.

Objective:
The primary goal of this project is to create an interpretable classification model to predict de-fleeting decisions, with a focus on applying machine learning techniques to real-world-style datasets.
Despite the dataset's randomized nature, the project emphasizes process and methodology.

Methodology:

Data Preprocessing:
Numerical features were scaled, and categorical features were encoded. Exploratory Data Analysis (EDA) helped identify trends and understand the limitations posed by data randomization.
Feature Engineering:
Features were selected and transformed to maximize the model's ability to capture patterns within the randomized dataset.
Modeling:
The Random Forest algorithm was selected for its ability to handle non-linear relationships and provide insights through feature importance. Hyperparameter tuning was conducted for optimization.
Evaluation:
Metrics such as accuracy, precision, recall, and F1-score were used. The model's performance reflects the challenges of working with randomized data, which resulted in a lower accuracy score.
Results:
Despite the inherent limitations of the dataset, the Random Forest model achieved an accuracy of 64.2% and provided meaningful insights into the factors that influence de-fleeting decisions.
