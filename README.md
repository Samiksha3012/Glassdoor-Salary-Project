# Glassdoor Salary Prediction

A machine learning project that analyzes Glassdoor job-posting data to explore salary trends and predict salaries based on job roles, seniority, location, company characteristics, and required skills.

## 🎯 Project Objectives
- Explore salary distributions and compensation patterns.
- Identify job-related factors associated with salary differences.
- Build regression models to predict salaries.
- Compare model performance using MAE, RMSE, and R².

## 🔄 Project Workflow
1. **Data Cleaning:** Handle missing values, inconsistent entries, and data types.
2. **Exploratory Data Analysis:** Analyze salary distributions across job titles, seniority levels, locations, and skills.
3. **Feature Engineering:** Prepare numerical and categorical features for machine learning.
4. **Preprocessing:** Encode categorical variables and scale features where required.
5. **Model Training:** Train Linear Regression, Ridge Regression, Random Forest, and Gradient Boosting models.
6. **Model Evaluation:** Compare predictions using MAE, RMSE, and R².
7. **Salary Prediction:** Select a model based on evaluation results and generate salary estimates.

## 📊 Key Areas of Analysis
- Salary differences across job roles and seniority levels
- Geographic variation in salaries
- Relationships between technical skills and compensation
- Company characteristics and salary patterns
- Actual versus predicted salary comparisons
- Feature importance for understanding model predictions

## 🤖 Models Used
- Linear Regression
- Ridge Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## 📈 Evaluation Metrics
- **MAE:** Average absolute prediction error.
- **RMSE:** Penalizes larger prediction errors more heavily.
- **R² Score:** Measures the proportion of salary variation explained by the model.

The reference project, [US Salary Project](https://github.com/fraperez/US-Salary-Project), reports an R² score of approximately **0.72** in its own setup. Results from this implementation may differ depending on preprocessing, features, and train-test split.

## 🛠️ Technologies Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and Jupyter Notebook.

## 🚀 How to Run
1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Open the Jupyter notebook.
4. Configure the dataset path.
5. Run the cells sequentially to perform EDA, train the models, and evaluate predictions.

*Note: Ensure the dataset is available locally and the file paths are correctly configured.*

## 📝 Conclusion
This project demonstrates how salary data can be used to identify compensation patterns and build predictive regression models. Comparing multiple algorithms helps evaluate their suitability for salary estimation, while feature importance and exploratory analysis provide insights into the factors associated with salary differences.

Predictions are estimates and depend on the quality, completeness, and representativeness of the dataset.

## 📚 Reference
- [US Salary Project — GitHub](https://github.com/fraperez/US-Salary-Project)

**Author:** Samiksha Zagade
