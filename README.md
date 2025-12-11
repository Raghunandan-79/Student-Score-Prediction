# Student Score Prediction using Supervised Learning

## Overview
This project implements a **Linear Regression** model to predict final exam scores based on weekly study hours. It demonstrates the complete machine learning workflow, from data preprocessing to model evaluation and visualization.

## Dataset
- **File:** `student_performance.csv`
- **Features:** 
    - `weekly_self_study_hours`: Independent variable (predictor)
    - `total_score`: Dependent variable (target)
- **Size:** [Specify number of samples]

## Technologies Used
- **Python** 3.x
- **Scikit-learn** - Model implementation
- **Pandas** - Data manipulation
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization

## How to Run

1. **Clone the repository**
     ```bash
     git clone <repository-url>
     cd student-score-prediction
     ```

2. **Install dependencies**
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the script**
     ```bash
     python main.py
     ```

## Results
Model performance metrics:
- **MAE (Mean Absolute Error):** [Value]
- **MSE (Mean Squared Error):** [Value]
- **RMSE (Root Mean Squared Error):** [Value]
- **R² Score:** [Value]

Visualizations include:
- Histogram of score distribution
- Scatter plot with fitted regression line

## Example Prediction
```python
model.predict([[5]])  # Predict score for 5 hours of study
```

## Learnings
- Understanding linear relationships in data
- Importance of data preprocessing
- Model evaluation best practices

## Future Improvements
- Test polynomial regression models
- Include additional features
- Implement cross-validation
- Deploy as a web application

## Author
Raghunandan Sharma