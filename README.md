# Linear-Regression-Prediction-System

**A Machine Learning Project Using Python, Scikit-learn, Gradio and Flask**

## Overview

The Linear Regression Prediction System demonstrates the application of supervised machine learning to two real-world prediction tasks: student exam score prediction and house value estimation.

Two independent linear regression models are trained and evaluated, with interactive interfaces developed using Gradio and Flask.

## Features

- **Student Performance Prediction:** Predicts exam scores based on study hours.
- **House Value Prediction:** Estimates median house values using median income.
- **Model Training:** Trains two independent linear regression models.
- **Model Evaluation:** Measures performance using MAE, MSE and R².
- **Gradio Interface:** Provides an interactive prediction interface.
- **Flask Interface:** Provides a browser-based web application.

## Datasets

| Dataset | Input Feature | Prediction Target |
|---|---|---|
| Student Exam Scores | Hours Studied | Exam Score |
| Housing | Median Income | Median House Value |

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- Gradio
- Flask

## Model Performance

| Model | MAE | MSE | R² Score |
|---|---:|---:|---:|
| Student Exam Score | 3.83 | 19.16 | 0.639 |
| House Value | 62,990.87 | 7,091,157,771.77 | 0.459 |

The models are evaluated on held-out test data. The results represent predictions using the selected input feature for each dataset.

## Project Structure

- `LinearRegressionProject.ipynb` — model training, evaluation and interfaces
- `student_exam_scores.csv` — student dataset
- `housing.csv` — housing dataset
- `requirements.txt` — project dependencies
- `screenshots/` — application screenshots

## Installation and Usage

1. Download or clone this repository.
2. Install the dependencies from `requirements.txt`.
3. Open the notebook in Jupyter Notebook.
4. Run the cells in order to load the datasets, train the models and launch the interfaces.

## Future Improvements

- Experiment with multiple input features.
- Compare linear regression with other regression algorithms.
- Improve the user interface and data visualizations.
- Investigate methods to improve prediction accuracy.

## Author

**Syeda Fasiha Faraz**  
Department of Robotics and AI  
SZABIST University
