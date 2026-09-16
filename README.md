# 🏦 Customer Churn Prediction | Machine Learning 🤖

Predicting whether a customer will **exit a financial institution** using Machine Learning and customer-level behavioural data.

## 🎯 Objective

Build a **classification model** that identifies customers likely to churn, helping financial institutions understand customer behaviour and improve retention strategies.

## 📂 Dataset

* `train.csv` — Training data with features + target
* `test.csv` — Test data with hidden target
* `sample_submission.csv` — Required submission format

## 🔍 Features

| Feature               | Description                |
| --------------------- | -------------------------- |
| 👤 `customer_id`      | Unique customer identifier |
| 📊 `credit_score`     | Customer credit score      |
| 🌍 `country`          | Country of residence       |
| ⚧️ `gender`           | Customer gender            |
| 🎂 `age`              | Customer age               |
| ⏳ `tenure`            | Years with the institution |
| 💰 `acc_balance`      | Account balance            |
| 🏦 `prod_count`       | Number of products used    |
| 💳 `has_card`         | Credit card ownership      |
| ⚡ `is_active`         | Recent activity indicator  |
| 💵 `estimated_salary` | Estimated salary           |
| 🚪 `exit_status`      | **Target: Customer churn** |

## ⚙️ ML Workflow

```text
📂 Raw Data
     ↓
🧹 Data Cleaning
     ↓
📊 Exploratory Data Analysis
     ↓
🔍 Missing Values & Outliers
     ↓
🛠️ Feature Engineering
     ↓
🔤 Categorical Encoding
     ↓
⚖️ Class Distribution Analysis
     ↓
🤖 Classification Models
     ↓
🧪 Cross-Validation
     ↓
🎯 Model Evaluation
     ↓
🔮 Churn Prediction
```

## 🧠 Machine Learning

The project explores classification and tree-based ensemble approaches to capture nonlinear relationships between customer characteristics and churn behaviour.

## 📏 Evaluation

Models are evaluated using:

* 🎯 Accuracy
* 🎯 Precision
* 🎯 Recall
* 🎯 F1-Score
* 📈 ROC-AUC

Validation performance is used to assess how well the model generalizes to unseen customers.

## 💡 Key Insight

Customer churn is rarely caused by a single factor.

Variables such as **age, account activity, product usage, tenure, balance and credit profile** can interact to influence the probability of a customer leaving.

```text
👤 Customer Profile
        +
📊 Financial Behaviour
        +
⚡ Activity
        ↓
🤖 ML Model
        ↓
🚪 Churn Probability
```

## 🚀 Future Scope

* [ ] SHAP-based model explainability
* [ ] Hyperparameter optimization
* [ ] Churn probability scoring
* [ ] Customer segmentation
* [ ] Retention analytics dashboard
* [ ] Streamlit deployment

## 🛠️ Tech Stack

**Python** • **Pandas** • **NumPy** • **Scikit-learn** • **Matplotlib** • **Seaborn** • **Machine Learning**

---

### 🏦 Customer Data → 🧠 ML → 🚪 Churn Prediction → 📈 Retention Insights
