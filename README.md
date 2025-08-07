# python_internship_task3

# Python Internship Task 3: Linear Regression

This repository contains my submission for Task 3 of the Elevate AI & ML Internship. The focus of this task is to implement, evaluate, and interpret simple and multiple linear regression models using the House Prices dataset.

## Objective

- Build and understand linear regression models.
- Evaluate model performance with MAE, MSE, and R² metrics.
- Visualize regression fits and residuals to gain insight into model behavior.
- Interpret coefficients to understand the impact of features on the target.

## Approach

1. **Data Preparation:**  
   Loaded the cleaned dataset from Task 1 and selected relevant features for regression analysis, including both simple (single feature) and multiple feature models.

2. **Train-Test Split:**  
   Divided the dataset into training (80%) and testing (20%) subsets for unbiased evaluation.

3. **Model Training and Prediction:**  
   Used Scikit-learn's `LinearRegression` to fit models on training data and predict target values on the test set.

4. **Evaluation Metrics:**  
   Calculated:
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - R² Score (coefficient of determination)  
   These metrics quantify model accuracy and goodness of fit.

5. **Visualizations:**  
   - Plotted scatter plots with regression line for simple linear regression (e.g., SalePrice vs GrLivArea).  
   - Created actual vs predicted plots for multiple regression to visualize model performance.  
   - Displayed residual distributions and residuals vs fitted values to assess error behavior.

6. **Interpretation:**  
   Analyzed model coefficients to understand how each feature influences house prices, acknowledging strengths, limitations, and potential areas for improvement.

## Repository Contents

- **linear_regression_notebook.ipynb**: Jupyter notebook with complete code, visualizations, and interpretations.  
- **cleaned_data.csv**: Cleaned dataset from Task 1 used for modeling.  
- **train.csv**: Original dataset for reference.  
- **README.md**: This overview document.

## How to Run

- Open `python_internship_task3.ipynb` in Google Colab or Jupyter environment.  
- Upload `cleaned_data.csv` if not already present.  
- Sequentially run all cells to reproduce analyses, graphs, and insights.  
- Required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn.

## Learnings and Insights

This task deepened my understanding of regression modeling, highlighting how to connect data preprocessing and exploratory analysis to build predictive ML models. Visualizing fits and residuals helped clarify linear regression assumptions and potential pitfalls. Interpreting coefficients reinforced the practical meaning behind model outputs, enabling actionable insights into housing price determinants.

Feel free to review the notebook for detailed explanations and visual evidence of this journey through linear regression!
