# Titanic Survival Prediction

This project focuses on analyzing and predicting passenger survival from the Titanic disaster using machine learning techniques. The project employs data preprocessing, exploratory data analysis (EDA), and model training to achieve reliable predictions.

## Project Overview

The Titanic disaster remains one of the most well-known tragedies in history. This project uses passenger details such as age, gender, ticket class, and other relevant features to predict whether a passenger would survive the calamity. It involves:

- Data exploration and visualization.
- Data preprocessing for model readiness.
- Building and evaluating machine learning models.

## Dataset

The dataset for this project is the classic Titanic dataset provided by Kaggle. It includes the following columns:

- **PassengerId**: Unique ID for each passenger.
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard the Titanic.
- **Parch**: Number of parents/children aboard the Titanic.
- **Ticket**: Ticket number.
- **Fare**: Amount paid for the ticket.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Libraries and Tools Used

The project utilizes the following Python libraries and tools:

- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **Seaborn**: For advanced visualization.
- **Scikit-learn**: For machine learning algorithms and evaluation.

## Project Structure

- **`main.ipynb`**: The Jupyter Notebook containing code for data preprocessing, EDA, model training, and evaluation.

## Key Steps in the Project

1. **Data Exploration**:
   - Understanding the structure and properties of the dataset.
   - Handling missing values and inconsistent data.

2. **Data Visualization**:
   - Analyzing relationships between features.
   - Identifying key factors influencing survival rates.

3. **Data Preprocessing**:
   - Encoding categorical features.
   - Filling missing values.
   - Scaling numerical features for model compatibility.

4. **Model Building and Evaluation**:
   - Training machine learning models such as Logistic Regression, Decision Trees, and Random Forests.
   - Evaluating models using accuracy, precision, recall, and F1-score.

## Results

The project demonstrates an accurate and interpretable model for predicting passenger survival on the Titanic dataset. Specific results and performance metrics are detailed in the notebook.
