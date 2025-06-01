📌 Objective
To implement and understand **Simple Linear Regression** using the Housing dataset.

🧰 Tools Used
- Python
- Pandas
- Matplotlib
- Scikit-learn

📊 Dataset
The dataset `Housing.csv` contains features like:
- `area`
- `bedrooms`
- `bathrooms`
- `furnishingstatus` (categorical)
- `price` (target variable)
Before applying linear regression, categorical columns were converted into numeric using one-hot encoding.

🔍 Approach
1. **Data Preprocessing**:
   - Loaded the dataset using `pandas`
   - Converted categorical variables (like `furnishingstatus`) using `pd.get_dummies()`
2. **Modeling**:
   - Selected `'area'` as the independent variable `X`
   - Used `'price'` as the target variable `y`
   - Split data into training and testing sets (80/20 split)
   - Trained a `LinearRegression` model from Scikit-learn
3. **Evaluation**:
   - Calculated Mean Squared Error (MSE)
   - Calculated R² Score to check model accuracy
4. **Visualization**:
   - Plotted predicted vs actual values using a scatter plot and regression line

📈 Results
- The model shows the relationship between house `area` and `price`
- Evaluation metrics like R² help assess the performance of the regression model

📁 Files Included
- `Housing.csv` - Dataset used for regression
- `regression_model.py` - Python code for data preprocessing, modeling, and evaluation
- `plot.png` - Scatter plot showing predicted vs actual values

✅ Conclusion
This provides a practical understanding of how simple linear regression can be used to model and predict real-world outcomes like housing prices. Further multiple regression is used with more features.
