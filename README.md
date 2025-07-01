## 📱 Mobile Price Prediction – Mini Data Science Project

### 🔍 Overview

This mini data science project aims to build a simple, interpretable machine learning model to predict the **price range of mobile phones** (from 0 to 3) based on their technical specifications.

The project showcases essential data science skills such as:

* Exploratory Data Analysis (EDA)
* Feature selection
* Model building and evaluation
* Insight visualization

---

### 🧠 Problem Statement

The goal is to predict the **price category** of mobile phones — classified as **Low**, **Medium**, **High**, or **Very High** — based on features like **RAM**, **battery power**, **pixel resolution**, and more.

* **Type:** Multi-class classification
* **Target variable:** `price_range`

  * `0`: Low
  * `1`: Medium
  * `2`: High
  * `3`: Very High

---

### 🗂️ Dataset Description

* **Samples:** 2000 mobile phones
* **Features:** 20+ technical attributes
* **Target:** `price_range`
* ✅ **Clean & balanced** dataset with no missing values

---

### ⚙️ Tech Stack

* **Language:** Python
* **Libraries:**

  * `pandas`, `matplotlib`, `seaborn` – for data analysis & visualization
  * `scikit-learn` – for machine learning modeling & evaluation

---

### 🧪 Machine Learning Workflow

1. **Data Loading**
2. **EDA & Correlation Analysis**
3. **Feature Selection** – Key features like `ram`, `battery_power`, etc.
4. **Preprocessing** – Feature scaling using `StandardScaler`
5. **Modeling** – Trained and compared:

   * Logistic Regression
   * Decision Tree Classifier
6. **Evaluation** – Accuracy score and classification report
7. **Interpretability** – Analyzed feature importance for insights

---

### 📊 Key Insights

* **RAM** was the most influential feature in determining price range.
* **Battery power** and **screen resolution** were also strong predictors.
* Both models performed reasonably well, with the **Decision Tree** slightly outperforming Logistic Regression.
* Feature importance plots helped interpret the model’s decisions clearly.

---

### 📁 Project Structure

```
📦 Mobile_Price_Prediction/
├── mobile_data.csv                  # Dataset file
├── Mobile_Price_Prediction.ipynb    # Jupyter notebook with full analysis
├── README.md                        # Project overview and documentation
```

---

### ✨ Future Enhancements

* Experiment with more advanced models (e.g., **Random Forest**, **SVM**)
* Convert to a **regression task** using actual price values
* Develop a **Streamlit web interface** for interactive predictions

---

### 🧑‍💻 Author

**Vishal Choudhary**
*Data Science Bootcamp Project – 2025*

