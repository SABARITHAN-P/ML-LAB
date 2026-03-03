# Machine Learning Assignment – 2  
## Data Preprocessing and Classification using Naive Bayes & KNN

**Name:** SABARITHAN P  
**Register Number:** 3122235001108  
**Course:** Machine Learning  

---

## 📌 Objective
The objective of this assignment is to:
- Perform **data preprocessing and feature engineering**
- Apply **classification algorithms**
  - Naive Bayes
  - K-Nearest Neighbors (KNN)
- Evaluate and compare model performance

---

## 📂 Dataset Description
The dataset used contains:
- Numerical features
- Categorical features
- A class label (target variable)

The data represents a real-world classification problem and requires preprocessing before model training.

---

## 🛠️ Tools & Libraries Used
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## ⚙️ Methodology

### 1️⃣ Data Loading & Inspection
- Dataset loaded using Pandas
- Initial exploration using `head()`, `info()`, and `describe()`

### 2️⃣ Data Preprocessing
- Handling missing values using mean/median/mode
- Encoding categorical variables using:
  - Label Encoding
  - One-Hot Encoding
- Feature scaling using:
  - StandardScaler

### 3️⃣ Train-Test Split
- Dataset split into training and testing sets
- Ensures unbiased evaluation

---

## 🤖 Machine Learning Models Used

### 🔹 Naive Bayes Classifier
- Probabilistic classification algorithm based on Bayes’ Theorem
- Assumes feature independence
- Suitable for high-dimensional data
- Used to predict class labels efficiently

### 🔹 K-Nearest Neighbors (KNN)
- Distance-based classification algorithm
- Classifies data based on nearest neighbors
- Uses distance metrics such as Euclidean distance
- Sensitive to feature scaling, hence normalization is required

---

## 📊 Model Evaluation
- Accuracy score calculated for both models
- Performance comparison between:
  - Naive Bayes
  - KNN
- Observations made based on prediction results

---

## 📈 Observations
- Data preprocessing improves classification accuracy
- Naive Bayes performs well with independent features
- KNN performance depends on value of **K** and feature scaling
- Proper normalization is critical for KNN

---

## 🧠 Conclusion
This assignment demonstrates the complete pipeline of:
- Data preprocessing
- Feature engineering
- Classification using Naive Bayes and KNN

Both algorithms have different strengths:
- **Naive Bayes** is fast and efficient
- **KNN** is simple but computationally intensive

Proper preprocessing plays a key role in achieving good model performance.

---

## 📎 Files Included
- `MAIN2.ipynb` – Jupyter Notebook with preprocessing and classification code
- `README.md` – Assignment documentation