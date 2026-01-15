# :rocket: Accidental-Drug-Related-Deaths-2012-2024-
The machine learning model in your project, based on the Accidental Drug Related Deaths (2012-2024) dataset, uses regression and classification techniques to analyze and predict patterns in drug-related fatalities.

## :bar_chart: Dataset
The dataset used is https://github.com/ShittuOluwashola77/Accidental-Drug-Related-Deaths-2012-2024-/blob/main/Accidental_Drug_Related_Deaths_2012-2024_20250703.csv , which contains over 12,000 records. Key features include: 

Demographics: Race.

Geography: Residence City/County, Injury City/County, and Geolocation data.

Clinical Data: Description of Injury, Cause of Death, and Manner of Death.

## :brain: Models and Performance
ThIS project implements both regression and classification models to evaluate different aspects of the data.

## :robot: Regression Models

Used to predict numerical representations of outcomes:

Linear Regression: Achieved a Mean Absolute Error (MAE) of ~2143.72.

Decision Tree Regressor: Outperformed Linear Regression with a lower MAE of ~1948.20.

Based on initial testing, the Decision Tree consistently performed better across Accuracy, Precision, Recall, and F1-score metrics compared to Logistic Regression (as seen in the notebook output snippet).

## :balance_scale: Key Implementation Steps

Data Preprocessing: Handled missing values and used LabelEncoder to transform categorical text data (like Race and City) into numerical format for the models.

Model Training: Split the data into training and testing sets using train_test_split.

Evaluation: Evaluated models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Precision.
