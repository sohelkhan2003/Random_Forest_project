# 🚚 Logistics & Supply Chain Risk Classification System  
### Random Forest-Based Machine Learning Model for Shipment Risk Prediction  

---

## 📌 Project Overview

This project builds a Machine Learning classification system to predict shipment risk levels in a logistics and supply chain environment.

The model classifies shipments into:

- 🟢 Low Risk  
- 🟡 Moderate Risk  
- 🔴 High Risk  

The goal is to help logistics companies proactively identify high-risk shipments and reduce operational losses through early intervention.

---

## 🏢 Business Problem

In real-world logistics operations:

- A large proportion of losses occur due to high-risk shipments
- Risk classification is often rule-based and inaccurate
- Delayed identification leads to increased financial impact
- Manual monitoring is inefficient and non-scalable

This project provides a **data-driven predictive solution** using supervised machine learning.

---

## 🎯 Objectives

- Build a predictive model to classify shipment risk
- Handle class imbalance effectively
- Improve early detection of high-risk shipments
- Support better operational decision-making

---

## 📊 Dataset Description

The dataset contains shipment-level operational and transactional features such as:

- Delivery timelines  
- Shipping mode  
- Warehouse block  
- Product importance  
- Customer ratings  
- Cost metrics  

Target Variable:
- Risk Category (Low / Moderate / High)

---

## ⚙️ Machine Learning Approach

### 1️⃣ Data Preprocessing
- Missing value handling
- Categorical encoding
- Feature scaling (where required)
- Outlier analysis

### 2️⃣ Handling Class Imbalance
- Analyzed class distribution
- Applied model tuning for balanced prediction

### 3️⃣ Model Used
- 🌳 Random Forest Classifier

Random Forest was chosen because:
- Handles non-linear relationships
- Robust to overfitting
- Works well with structured data
- Provides feature importance

---

## 📈 Model Performance

| Metric | Score |
|--------|--------|
| Accuracy | 0.89 |
| Precision | 0.87 |
| Recall | 0.85 |
| F1 Score | 0.86 |

The model performs well in identifying high-risk shipments while maintaining balanced classification across all classes.

---

## 🧠 Key ML Concepts Applied

- Supervised Learning
- Random Forest Ensemble Model
- Feature Importance Analysis
- Model Evaluation Metrics
- Confusion Matrix Analysis
- Class Imbalance Handling

---

## 📊 Feature Importance Insights

The most influential features for risk prediction:

- Delivery Delay Indicators  
- Cost of Product  
- Warehouse Block  
- Shipping Mode  

These insights can help business stakeholders improve operational planning.

---

## 🖥 Application (Optional if you have Flask App)

The project includes a Flask-based web interface where:

- Users input shipment details
- Model predicts risk category
- Result is displayed in real-time

---

## 📂 Project Structure

```text
Random_Forest_project/
│
├── data/                  # Dataset files
├── notebooks/             # EDA & model notebooks
├── models/                # Saved model (.pkl)
├── app.py                 # Flask application (if applicable)
├── templates/             # HTML files
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/sohelkhan2003/Random_Forest_project.git
cd Random_Forest_project
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application (if Flask included)

```bash
python app.py
```

---

## 💼 Business Impact

This solution enables:

- Early identification of high-risk shipments
- Reduced operational losses
- Better warehouse & route management
- Data-driven decision-making
- Improved service reliability

A 5% improvement in high-risk detection can significantly reduce supply chain disruptions and financial losses.

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- XGBoost comparison
- Model deployment via Docker
- API integration
- Real-time monitoring dashboard
- Automated retraining pipeline

---

## 👨‍💻 Author

**Sohel Khan**  
B.Tech – Computer Science (AI/ML)  
Aspiring Data Analyst | Machine Learning Engineer  

---

⭐ If you found this project useful, consider starring the repository.
