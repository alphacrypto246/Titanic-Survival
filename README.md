# Titanic Survival Prediction

## Overview
This project uses machine learning techniques to predict the survival of passengers aboard the Titanic, based on features such as age, sex, class, and other relevant data. The dataset used in this project is the famous Titanic dataset, which is a commonly used dataset for classification tasks in machine learning.

## Objective
The main objective of this project is to build a predictive model that can accurately classify whether a passenger survived or not based on the available features. We use various machine learning models, including Random Forest, Support Vector Machine (SVM), and Logistic Regression, to predict the survival outcome.

## Dataset
The dataset used in this project is the Titanic dataset from Kaggle. It consists of the following features:

* **Pclass**: Passenger class (1st, 2nd, 3rd)
* **Name**: Name of the passenger
* **Sex**: Gender of the passenger (male or female)
* **Age**: Age of the passenger in years
* **SibSp**: Number of siblings or spouses aboard the Titanic
* **Parch**: Number of parents or children aboard the Titanic
* **Ticket**: Ticket number
* **Fare**: Passenger fare
* **Cabin**: Cabin number
* **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/alphacrypto246/Titanic-Survival.git
```

2. Navigate to the project directory:
```bash
cd Titanic-Survival
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

4. Run the notebook:
```bash
jupyter notebook main.ipynb
```

## Approach

### 1. Data Preprocessing
* Handle missing values in the dataset
* Convert categorical variables into numerical values using encoding techniques
* Normalize the data for some machine learning models

### 2. Model Selection
* Implement multiple machine learning models like Logistic Regression, Random Forest, and Support Vector Machine (SVM)
* Train the models on the training dataset and test them on the test dataset

### 3. Evaluation
* Evaluate the models using metrics like accuracy, precision, recall, and F1-score to measure their performance

### 4. Final Model
* The best-performing model is selected based on evaluation metrics for final predictions

## Results
The project compares multiple machine learning models' performance in predicting Titanic passenger survival. It presents the results of each model's accuracy and provides insights into which features are most important for predicting survival.

## Technologies Used
* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Contributing
Feel free to fork the repository, open issues, and submit pull requests for any improvements or fixes. Contributions are welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
* Titanic dataset is provided by Kaggle: https://www.kaggle.com/c/titanic
