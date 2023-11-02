# 🫀 **Cardiovascular Diseases Risk Prediction**

### **By Alankrutha Reddy Purumandla**

---

## 📝 **Overview**

This project leverages machine learning techniques to predict the risk of **cardiovascular diseases (CVD)** using a comprehensive dataset of health metrics and lifestyle habits. By identifying at-risk individuals early, the model aims to assist healthcare providers in implementing **preventive measures** and **personalized treatment plans**.

Cardiovascular diseases are a leading cause of mortality worldwide, making this work crucial for improving public health and patient outcomes.

---

## 🎯 **Objective**

- Develop a robust machine learning model that predicts the risk of CVD based on health and lifestyle data.
- Use advanced preprocessing techniques like **SMOTE** to address dataset imbalances.
- Evaluate models using performance metrics such as **accuracy**, **AUC-ROC**, **precision**, and **recall**.

---

## 🔍 **Dataset**
- **Source**: Kaggle (original source: Republic of Korea e-government data portal).  
- **Size**: 308,854 records.  
- **Attributes**: 19 features, including:
  - **Heart_Disease** (target variable).
  - General health metrics (BMI, cholesterol levels, etc.).
  - Lifestyle habits (smoking, alcohol consumption, exercise frequency).

---

## 🛠️ **Technologies Used**
| **Category**               | **Tools/Technologies**              |
|-----------------------------|-------------------------------------|
| **Programming Language**    | Python                             |
| **Libraries**               | NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn |
| **Machine Learning Models** | Logistic Regression, Decision Tree, Gaussian Naïve Bayes, Bernoulli Naïve Bayes |
| **Preprocessing Techniques**| SMOTE, One-Hot Encoding            |

---

## 📈 **Methodology**

### 1. **Data Preprocessing**
   - Handled missing values.
   - Addressed **class imbalance** in the dataset using **SMOTE (Synthetic Minority Oversampling Technique)**.

### 2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions, correlations, and relationships using:
     - Heatmaps.
     - KDE plots.
     - Box plots.

### 3. **Model Training and Evaluation**
   - Trained multiple machine learning models, including:
     - Logistic Regression.
     - Gaussian and Bernoulli Naïve Bayes.
     - Decision Tree Classifier.
   - Evaluated performance using metrics like:
     - Accuracy.
     - Precision, Recall, and F1-Score.
     - AUC-ROC curves.

### 4. **Addressing Class Imbalance**
   - Used SMOTE to balance the dataset.
   - Observed significant improvements in the performance of **Logistic Regression** and **Decision Tree Classifier**.

---

## 🏆 **Key Results**

| **Model**                | **Before SMOTE (AUC-ROC)** | **After SMOTE (AUC-ROC)** |
|--------------------------|----------------------------|---------------------------|
| Logistic Regression      | 0.53                      | 0.78                      |
| Gaussian Naïve Bayes      | 0.67                      | 0.68                      |
| Decision Tree Classifier | 0.85                      | 0.92                      |

### Highlights:
- **Decision Tree Classifier** outperformed other models with an **AUC-ROC of 0.92** after SMOTE.
- **Logistic Regression** showed a significant improvement from **0.53 to 0.78** after addressing class imbalance.

---

## 📊 **Visualizations**

### Correlation Heatmap
![Heatmap](https://via.placeholder.com/800x400.png?text=Heatmap+of+Feature+Correlations)

### AUC-ROC Curve for Logistic Regression (After SMOTE)
![ROC Curve](https://via.placeholder.com/800x400.png?text=AUC-ROC+Curve+Logistic+Regression)

### General Health Distribution
![General Health](https://via.placeholder.com/800x400.png?text=General+Health+Distribution)

---

## 🚀 **How to Run**
1. Clone the repository:
   
   git clone https://github.com/Alankrutha18/CVD-Risk-Prediction.git

2. Install required dependencies:
   
   pip install -r requirements.txt

3. Run the jupyter notebook