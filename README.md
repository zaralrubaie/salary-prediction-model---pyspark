
This project predicts salaries based on job-related and company features using Apache Spark and its MLlib library.

# Problem Statement
Predict salary using a range of job and company features.

#Tools and Libraries
- Apache Spark (PySpark)
- Spark MLlib
- pythin
#Features Used
- `work_year`
- `remote_ratio`
- `experience_level_num`
- `company_size_num`
- `job_title_index`
- `employment_type_index`
- `salary_currency_index`
- `employee_residence_index`
- `remote_type_index`

# ML Techniques
- Feature engineering with `VectorAssembler`
- Indexing for categorical features
- Regression using `DecisionTreeRegressor`
- Train-test data split
- Model evaluation (RMSE, R²)

#Results
- **Root Mean Square Error (RMSE):** 0.4758  
- **R² Score:** 0.4397

#Next Steps
- Try `RandomForestRegressor` or `GBTRegressor`
- Tune hyperparameters using `CrossValidator`


