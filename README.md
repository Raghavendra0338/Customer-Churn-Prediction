# Customer Churn Prediction

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. This project builds a **Machine Learning model** to predict whether a customer is likely to churn based on demographic information, service usage, contract details, and billing information.

The project includes:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Machine Learning model development
* Model evaluation

---

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer information such as:

* Customer demographics
* Internet and phone services
* Contract type
* Monthly and total charges
* Payment method
* Tenure
* Churn status (Target Variable)

Target Variable:

* **Churn Value**

  * `1` → Customer churned
  * `0` → Customer retained

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The project performs several visual analyses, including:

* Churn distribution
* Contract type vs Churn
* Monthly Charges vs Churn
* Tenure vs Churn
* Correlation Heatmap

### Key Insights

* Customers with **Month-to-Month contracts** have the highest churn rate.
* Customers paying **higher monthly charges** are more likely to churn.
* Customers with **shorter tenure** tend to churn more frequently.
* Longer contract durations significantly improve customer retention.

---

## ⚙ Data Preprocessing

The preprocessing pipeline includes:

* Removing unnecessary columns
* Removing leakage features such as:

  * Churn Label
  * Churn Score
  * Churn Reason
  * Customer ID
  * CLTV
* Handling missing values
* One-Hot Encoding categorical variables using `pd.get_dummies()`
* Train-Test Split

---

## 🤖 Machine Learning Model

The project uses:

* **Logistic Regression**

### Training Steps

1. Feature selection
2. One-hot encoding
3. Train-test split
4. Model training
5. Prediction
6. Performance evaluation

---

## 📈 Evaluation Metrics

The model is evaluated using:

* Accuracy Score
* Classification Report

  * Precision
  * Recall
  * F1-Score

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── Telco_customer_churn.xlsx
├── README.md
└── requirements.txt (optional)
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

2. Navigate to the project folder

```bash
cd customer-churn-prediction
```

3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open:

```
Customer_Churn_Prediction.ipynb
```

and run all cells.

---

## 📌 Future Improvements

* Compare multiple machine learning algorithms:

  * Random Forest
  * XGBoost
  * Support Vector Machine
* Hyperparameter tuning
* Cross-validation
* Feature importance analysis
* Build an interactive web application using Streamlit
* Deploy the trained model

---

## 📚 Learning Outcomes

Through this project, I learned:

* Data cleaning and preprocessing
* Exploratory Data Analysis
* Feature engineering
* Handling categorical variables
* Logistic Regression implementation
* Model evaluation using classification metrics
* Building an end-to-end machine learning workflow

---

## 👨‍💻 Author

**Your Name**

Feel free to connect with me on LinkedIn or contribute to this project by creating issues or submitting pull requests.

---

## ⭐ If you found this project helpful, consider giving it a star on GitHub!
