# Student Performance Prediction

## Project Overview
This project uses Python, Pandas, and scikit-learn to explore student academic performance and predict final marks using a simple machine-learning model.

## Objectives
- Inspect and validate the dataset.
- Predict final marks using attendance, study hours, and previous marks.
- Compare Linear Regression with a baseline model.
- Evaluate prediction errors using MAE, RMSE, and R².
- Document limitations and responsible use.

## Tools and Technologies
- Python
- Pandas
- scikit-learn
- Google Colab
- GitHub

## Dataset
The synthetic dataset contains 20 student records with attendance percentage, weekly study hours, previous marks, and final marks. It is created for educational purposes and does not represent real students.

## Models
- **Baseline:** Predicts the mean of the training-set target values.
- **Linear Regression:** Estimates final marks from the selected input features.

## Evaluation Metrics
- MAE: Mean Absolute Error
- RMSE: Root Mean Squared Error
- R²: Coefficient of determination

## Repository Structure
- `data/` — Student performance CSV
- `notebooks/` — Notebook containing data checks, model training, evaluation, and error analysis

## How to Run
1. Open the notebook in Google Colab.
2. Upload `student_performance_prediction.csv` if it is not available in the session.
3. Run the cells in order.

## Limitations
The dataset is small and synthetic. Its evaluation results are not evidence of reliable real-world prediction. Larger, representative datasets and stronger validation are needed before drawing practical conclusions.

## Responsible Use
Predictions should not be used alone to make decisions about students. Any real-world use would require careful validation, privacy protections, bias checks, and human review.
