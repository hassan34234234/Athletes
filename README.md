# 🏅 Olympic Medal Prediction using Machine Learning

This project develops a machine learning model to predict the number of medals won by countries in the Olympics based on historical data. It demonstrates a complete machine learning workflow, including data preprocessing, model training, evaluation, and error analysis.

## 📚 Project Overview

- **Objective**: Predict Olympic medal counts using features such as the number of athletes and previous medal counts.
- **Dataset**: Historical Summer Olympics dataset (`teams.csv`).
- **Tools and Libraries**: Python, Pandas, Seaborn, Scikit-learn, Jupyter Notebook.

## 🛠️ Methodology

1. **Hypothesis Formation**: Medal counts are correlated with team-level statistics.
2. **Data Preparation**: Cleaned missing values and selected relevant numerical features.
3. **Exploratory Data Analysis**: Identified strong correlations between athletes, previous medals, and medal outcomes.
4. **Model Training**: Built and trained a Linear Regression model.
5. **Evaluation**: Achieved a mean absolute error (MAE) of approximately 3.3 medals on test data.
6. **Error Analysis**: Investigated prediction errors across different countries to assess model reliability.

## 📊 Results

- Model demonstrated strong performance for high-participation countries (e.g., USA, Russia).
- Accuracy varied for countries with low athlete participation.
- Proposed enhancements include additional feature engineering, alternative algorithms (Random Forest, Neural Networks), and athlete-level prediction modeling.

## 📦 Setup and Requirements

Install the required libraries:

pip install pandas seaborn scikit-learn matplotlib


🔮 Future Improvements
Incorporate additional features such as event counts, athlete demographics, and training resources.

Test different machine learning models and hyperparameters.

Build athlete-level models for improved prediction accuracy.

📜 License
This project is licensed under the MIT License.
