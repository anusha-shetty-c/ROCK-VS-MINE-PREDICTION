# ROCK-VS-MINE-PREDICTION
🪨 Rock vs Mine Prediction

This project uses Logistic Regression to classify sonar signal data as either Rock (R) or Mine (M) based on the strength and frequency of the sonar return signal.

📘 Project Overview

Sonar signals are used to detect underwater objects. Each object (rock or mine) reflects sound differently.
This machine learning model analyzes sonar signal data and predicts whether the detected object is a rock or a mine.

⚙️ Features

Loads and preprocesses the Sonar dataset (sonar data.csv)

Splits data into training and testing sets

Trains a Logistic Regression model

Evaluates model accuracy on training and test data

Predicts object type (rock or mine) for a given input

🧠 Technologies Used

Python 3.x

NumPy

Pandas

scikit-learn (LogisticRegression, train_test_split, accuracy_score)

📊 Dataset

The dataset used is the Sonar Data Set from the UCI Machine Learning Repository.
Each sample contains 60 numerical features representing sonar signal strengths at various frequencies, followed by a label:

R → Rock

M → Mine

Ensure you have the file named sonar data.csv in your working directory.

🚀 How to Run

Clone or download this repository.

Make sure Python and required libraries are installed:

pip install numpy pandas scikit-learn


Place the dataset (sonar data.csv) in the same folder as rock_vs_mine_prediction.py.

Run the script:

python rock_vs_mine_prediction.py
