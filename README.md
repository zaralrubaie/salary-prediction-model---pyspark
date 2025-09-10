# Salary Prediction using PySpark MLlib

## Overview
This project predicts **salaries** based on job-related and company features using **Apache Spark** and its **MLlib library**.  
The goal is to build a regression model that estimates salaries and identifies key factors affecting compensation.

---

## Problem Statement
Predict salary using a range of **job** and **company features**.

---

## Tools and Libraries
- Apache Spark (PySpark)  
- Spark MLlib  
- Python  

---

## Features Used
- `work_year`  
- `remote_ratio`  
- `experience_level_num`  
- `company_size_num`  
- `job_title_index`  
- `employment_type_index`  
- `salary_currency_index`  
- `employee_residence_index`  
- `remote_type_index`  

---

## ML Techniques
- Feature engineering using **VectorAssembler**  
- Indexing for categorical features  
- Regression using **DecisionTreeRegressor**  
- Train-test data split  
- Model evaluation using **RMSE** and **R²**  

---

## Results
- **Root Mean Square Error (RMSE):** 0.4758  
- **R² Score:** 0.4397  

---

## Project Structure
````
salary_prediction_spark/
│
├── salary_prediction_spark.py # Main PySpark script with full workflow
├── predictions.csv # Model predictions
├── model_summary.txt # Summary of evaluation metrics
├── README.md # Project documentation
└── requirements.txt # Required libraries
└── LICENSE # MIT License
````

---

## How to Use
1. Run the PySpark script or notebook in Google Colab or a local Spark environment.  
2. Ensure the dataset is in the correct path.  
3. Step through the script to preprocess data, train the model, and generate predictions.  

---

## License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## Contact
Reach out for questions or collaboration opportunities.
