# Disease Prediction using Machine Learning

This is a machine learning-based disease prediction system that helps in diagnosing diseases based on symptoms entered by the user. It uses popular machine learning models including **Decision Tree**, **Random Forest**, and **Naive Bayes** to predict diseases based on input symptoms.

## Features

### Machine Learning Models:
- The system uses three machine learning classifiers—**Decision Tree**, **Random Forest**, and **Naive Bayes**—to predict diseases.

### GUI Interface:
- A graphical user interface (GUI) is developed using **Tkinter** to input symptoms and view predictions.

### Disease Prediction:
- The system predicts diseases like **Fungal infection**, **Allergy**, **GERD**, **Peptic ulcer**, **Malaria**, **Tuberculosis**, and more based on the symptoms entered.

## Requirements

- Python 3.x
- Tkinter
- Pandas
- Numpy
- Scikit-learn

## Files

- **main.py**: Contains the main code to run the application.
- **Training.csv** and **Testing.csv**: Datasets used for training and testing the machine learning models.
- **gui_stuff.py**: (Optional) Contains the GUI-related functions and code.

## Usage

### Enter Symptoms:
- The user needs to input symptoms through the provided dropdown options.

### Predict Disease:
- After entering symptoms, the user can choose a machine learning model (**DecisionTree**, **RandomForest**, or **NaiveBayes**) to predict the disease.

### View Results:
- The predicted disease is displayed on the screen. If no matching disease is found, the output will display "Not Found."

## Machine Learning Models Used

### Decision Tree Classifier:
- A tree-like model used for classification.

### Random Forest Classifier:
- An ensemble model using multiple decision trees.

### Naive Bayes:
- A probabilistic classifier based on Bayes' Theorem.
