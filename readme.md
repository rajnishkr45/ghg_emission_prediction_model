# 🌍 GHG Emissions Prediction Model | Edunet foundation internship

This project focuses on predicting **Greenhouse Gas (GHG) emissions** using machine learning techniques. The goal is to forecast emissions based on historical environmental and industrial data to assist in sustainability analysis and climate change mitigation strategies.

---

## 📁 Project Structure

```
├── GHG_Emissions_Prediction.ipynb   # Main notebook with code, EDA, and model
├── ghgemission_data.xlsx            # Input dataset
├── 01_venv.py                       # Python file (optional helper or script)
├── .gitignore                       # Git ignored files and folders
└── requirements.txt                 # (optional) Package dependencies
```

---

## 🔍 Problem Statement

With climate change being one of the biggest challenges globally, accurately predicting GHG emissions can help:

* Understand future environmental impact
* Plan emission reduction strategies
* Advise policy-making

---

## 📊 Dataset

* **File:** `ghgemission_data.xlsx`
* Contains historical data on GHG emissions, likely categorized by region, year, and sector.

---

## 🧪 Approach

1. **Data Preprocessing**

   * Load and clean data from `.xlsx` file
   * Handle missing values, normalization if required

2. **Exploratory Data Analysis (EDA)**

   * Visualize trends, outliers, and correlations
   * Understand feature importance

3. **Model Building**

   * Train regression models (Linear Regression, Random Forest, etc.)
   * Evaluate with metrics like RMSE, MAE, R²

4. **Prediction**

   * Use trained model to predict GHG emissions on test or future datasets

---

## 🚰 Tech Stack

* Python
* Jupyter Notebook
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* OpenPyXL / xlrd (for reading Excel files)

---

## ✅ How to Run

1. **Clone the repository:**

   ```bash
   git clone git@github.com:rajnishkr45/ghg_emission_prediction_model.git
   cd ghg_emission_prediction_model
   ```

2. **Create and activate virtual environment:**

   ```bash
   python -m venv venv
   venv\Scripts\activate   # On Windows
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch the notebook:**

   ```bash
   jupyter notebook GHG_Emissions_Prediction.ipynb
   ```

---

## 📈 Sample Output

*Plots of trends in emissions, model predictions vs. actual, and feature importances will be displayed in the notebook.*

---

## 📌 Future Improvements

* Integrate time-series models like ARIMA or LSTM
* Add API to expose predictions as a service
* Dashboard visualization using Streamlit or Dash

---


## 👨‍💻 Author

**Rajnish Kumar**
[GitHub](https://github.com/rajnishkr45)
