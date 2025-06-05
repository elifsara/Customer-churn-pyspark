# Customer Churn Prediction with PySpark

This project demonstrates how to predict customer churn using PySpark and machine learning techniques on a telecom dataset. The pipeline includes data exploration, preprocessing, model training, and evaluation — all executed in a scalable, distributed environment.

---

## 📁 Project Structure

```
customer-churn-pyspark/
│
├── Churn_Prediction.ipynb      # Main notebook with explanations
├── churn.csv                   # Sample dataset (optional or minimal version)
├── .gitignore                  # Excludes system/cache files from Git
└── README.md                   # Project documentation
```

---

## 📊 Dataset Overview

The dataset contains customer information from a fictional telecom company, including:

- Age
- Total Purchase Amount
- Account Manager Status
- Years as Customer
- Number of Website Interactions
- Churn (Target Variable)

---

## 🚀 Technologies Used

- **PySpark**: For scalable data processing and ML
- **Pandas**: For exploratory data analysis
- **Jupyter Notebook**: For combining code and visualizations
- **Spark MLlib**: For logistic regression modeling

---

## 🧪 Workflow Summary

1. Load dataset with `pandas`
2. Perform exploratory data analysis (EDA)
3. Convert DataFrame to PySpark
4. Rename and prepare features with `VectorAssembler`
5. Train a logistic regression model
6. Evaluate using AUC & Accuracy

---

## 📈 Results

- **Model**: Logistic Regression
- **AUC Score**: *0.9405*
- **Accuracy**: *~0.94*

> Further improvements may include trying different classifiers (e.g., Random Forest, GBT), encoding categorical features, and applying hyperparameter tuning.

---

## 📌 How to Run

1. Clone the repository:
```bash
git clone https://github.com/elifsara/Customer-churn-pyspark.git
```

2. Open the notebook:
```bash
jupyter notebook Churn_Prediction.ipynb
```

3. (Optional) Ensure PySpark is installed:
```bash
pip install pyspark
```

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋‍♀️ Author

Developed by [[elifsara](https://github.com/elifsara)]  
[[LinkedIn](https://www.linkedin.com/in/elifsarahan/)]  
