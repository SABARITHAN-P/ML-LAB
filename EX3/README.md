# Machine Learning Assignment – 1

## Exploratory Data Analysis (EDA) on Multiple Datasets

**Name:** SABARITHAN P  
**Register Number:** 3122235001108  
**Course:** Machine Learning

---

## 📌 Objective

The objective of this assignment is to perform **Exploratory Data Analysis (EDA)** on multiple real-world datasets in order to:

- Understand the structure and characteristics of the data
- Identify patterns, trends, and relationships between features
- Visualize distributions and correlations
- Prepare the data for future machine learning tasks

---

## 📂 Datasets Used

This assignment performs EDA on the following datasets:

1. **Iris Dataset**
   - Features: Sepal length, sepal width, petal length, petal width
   - Target: Species

2. **Loan Approval Dataset**
   - Features: Applicant income, loan amount, credit history, etc.
   - Target: Loan_Status

3. **Diabetes Dataset**
   - Features: Glucose, BMI, age, insulin, etc.
   - Target: Outcome

4. **Email Classification Dataset**
   - Features related to email content
   - Used for spam/non-spam analysis

5. **Handwritten Character Recognition Dataset**
   - Features: Image paths and labels
   - Target: Character labels

---

## 🛠️ Tools & Libraries Used

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **OpenCV (cv2)**

---

## ⚙️ Methodology

The following EDA steps were applied to each dataset:

1. **Data Loading**
   - Reading CSV files using Pandas

2. **Basic Data Inspection**
   - Shape of the dataset
   - Data types and null value analysis
   - Statistical summary using `describe()`

3. **Univariate Analysis**
   - Histograms for numerical features
   - Count plots for categorical features

4. **Bivariate Analysis**
   - Box plots grouped by target variable
   - Pair plots for feature relationships

5. **Correlation Analysis**
   - Correlation matrices
   - Heatmaps to identify strong relationships

6. **Visualization**
   - Feature distributions
   - Class-wise comparisons
   - Label distributions (for handwriting dataset)

---

## 📊 Key Observations

- Iris dataset shows clear separation between species using petal features
- Loan approval depends strongly on credit history and income patterns
- Diabetes dataset shows correlation between glucose, BMI, and outcome
- Email dataset reveals numerical feature relationships useful for classification
- Handwritten dataset shows class imbalance in label distribution

---

## 🧠 Conclusion

This assignment demonstrates how **EDA is a crucial first step in machine learning**.  
Through visualization and statistical analysis:

- Important features were identified
- Data quality issues were detected
- Insights were gained that help in model selection and preprocessing

EDA helps build intuition about data before applying machine learning algorithms.

---

## 📎 Files Included

- `EX1.ipynb` – Jupyter Notebook containing full EDA code
- `README.md` – Project documentation
