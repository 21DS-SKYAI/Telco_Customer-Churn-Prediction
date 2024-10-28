<h1 align="center">📉 Customer Churn Prediction Model for Telecom Sector</h1>
<p align="center">
  <strong>Using advanced machine learning techniques to predict telecom customer churn and improve retention strategies</strong>
</p>

![Project Banner](Customer churn banner.png)


---

## 🌐 Dataset
The dataset is sourced from Kaggle and can be found [here](https://www.kaggle.com/blastchar/telco-customer).

---

## 📝 Project Overview
Developed a sophisticated machine learning model to predict **customer churn** for a telecom company. This project leverages **data preprocessing**, **imbalanced data handling**, and **high-performance classifiers** to ensure reliable predictions with high accuracy.

---

## 📌 Key Responsibilities

### 1. Data Preprocessing
- **Cleaning and Transforming**: Addressed missing values and transformed raw data.
- **Encoding Categorical Variables**: Converted categorical features into numerical values for compatibility with machine learning models.

### 2. Imbalanced Data Handling
- Applied **SMOTEENN (Synthetic Minority Over-sampling Technique and Edited Nearest Neighbors)** to balance the dataset, improving model performance on minority classes (i.e., churned customers).

### 3. Model Training and Evaluation
- Implemented **Decision Tree** and **Random Forest** classifiers.
- Evaluated model performance using:
  - **Precision**
  - **Recall**
  - **F1-Score**
  - **Confusion Matrix**
- Achieved **92.36% accuracy** with the Random Forest classifier, ensuring high precision and recall for the minority (churned) class.

### 4. Model Deployment
- Saved the trained model as `model.sav` for easy deployment through **APIs**, enabling real-time churn predictions.

---

## 🛠️ Technologies Used

- **Programming Language**: Python
- **Libraries**: `pandas`, `scikit-learn`, `imbalanced-learn`
- **Techniques**: SMOTEENN, Decision Tree, Random Forest, Data Preprocessing

---

## 💡 Impact
- **Accuracy Improvement**: Enhanced model accuracy and reliability, particularly in predicting churned customers.
- **Business Value**: Enabled proactive customer churn management, allowing the telecom company to improve customer retention strategies and boost overall revenue.

---

## 📊 Evaluation Metrics
| Metric       | Value  |
|--------------|--------|
| **Accuracy** | 92.36% |
| **Precision**| High   |
| **Recall**   | High   |
| **F1-Score** | High   |

The model demonstrates high accuracy and effectiveness, especially in identifying churned customers.

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the project, make updates, and submit a pull request.

