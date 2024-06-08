## Movie Rating Prediction Project

### Objective
- Build a model to predict movie ratings based on features like genre, director, and actors.
- Analyze historical movie data to develop an accurate model for estimating movie ratings.

### Steps Taken
1. **Data Exploration and Preprocessing**
   - Loaded and inspected the dataset
   - Cleaned data by handling missing values and converting data types

2. **Feature Engineering**
   - Encoded categorical features using One-Hot Encoding
   - Prepared the feature set and target variable

3. **Model Development and Evaluation**
   - Trained initial models: Linear Regression and Random Forest
   - Performed hyperparameter tuning using Optuna 
   - Evaluated models using MSE, R² score, MAE, and RMSE
   - Best model: XGBoost with an accuracy of 34.92%

4. **Insights and Visualization**
   - Analyzed feature importances to understand key factors influencing movie ratings
   - Visualized actual vs. predicted ratings and error distribution

### Findings
- **Feature Importance**: Identified important features that influence movie ratings, such as genre and director.
- **Model Performance**: XGBoost model showed the best performance with an accuracy of 34.92%.
- **Error Analysis**: Most prediction errors were centered around 0, indicating generally accurate predictions with some variability.

### Conclusion
The project successfully built and evaluated multiple models to predict movie ratings. The XGBoost model, after hyperparameter tuning, provided the best performance. Further improvements can be made by exploring additional features, advanced models, and ensemble methods.

