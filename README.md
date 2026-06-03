Student Performance Prediction System

Overview

This project predicts a student's final marks using Machine Learning based on:

- Attendance Percentage
- Study Hours
- Internal Marks

The project uses Python, Pandas, NumPy, Matplotlib, and Scikit-learn.

Features

- Data preprocessing
- Data visualization
- Machine learning model training
- Model evaluation
- Prediction system
- Saved trained model

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

Project Structure

data/

- student_performance.csv
- cleaned_student_performance.csv

src/

- data_preprocessing.py
- visualization.py
- train_model.py
- predict.py

models/

- student_model.pkl

images/

- attendance_vs_marks.png
- studyhours_vs_marks.png

Model Performance

- MAE: 0.25
- R² Score: 0.99

How to Run

1. Install dependencies

pip install -r requirements.txt

2. Run preprocessing

python src/data_preprocessing.py

3. Generate visualizations

python src/visualization.py

4. Train model

python src/train_model.py

5. Run prediction system

python src/predict.py

Author

Internship Project - CodeVedX AI/ML Internship