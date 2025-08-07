# 📱 Social Media Addiction vs Relationships — Clustering & Prediction

This project analyzes the relationship between social media usage and its impact on students’ academic and personal lives. Using survey data from Kaggle, we applied clustering and predictive modeling to identify patterns of potential addiction and how it affects relationships.

[📊 Dataset on Kaggle](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships)

---

## 🎯 Objective

- Understand how social media usage affects relationships and academic focus.
- Group students into behavioral clusters based on addiction-related habits.
- Build a machine learning model to predict whether a student is likely addicted.

---

## 📁 Dataset Overview

- **File**: `Students Social Media Addiction.csv`
- **Source**: Kaggle
- **Features** include:
  - Hours spent on social media
  - Relationship and academic impact
  - Sleep disruption
  - Concentration and motivation issues
  - Self-perceived addiction level

---

## 🔧 Project Workflow

### 1. Data Cleaning & Preparation
- Removed missing and inconsistent values
- Converted categorical values to numeric
- Normalized relevant features

### 2. Exploratory Data Analysis (EDA)
- Uncovered key trends (e.g., high usage = academic decline)
- Visualized correlations using heatmaps and pairplots

### 3. Clustering Analysis
- Applied K-Means clustering to segment students
- Used Elbow Method and Silhouette Score to identify the best `k`
- Found distinct clusters: Low-risk, Moderate-risk, High-risk users

### 4. Predictive Modeling
- Built classification models (e.g. Logistic Regression, Random Forest)
- Predicted likelihood of social media addiction
- Evaluated models with accuracy, precision, recall, and F1-score

---

## 📊 Results & Insights

- Most predictive features: screen time, emotional impact, academic distraction
- Clustering revealed **3 behavior types**:
  - Casual Users
  - Moderate Users
  - At-Risk Users
- Best model: Random Forest (replace with actual metric if known)

---

## 🛠 Tools Used

- Python (Jupyter Notebook)
- pandas, numpy, matplotlib, seaborn
- scikit-learn (KMeans, classification models)

---

## 🧠 Future Enhancements

- Add demographic segmentation (gender, age, region)
- Convert binary addiction label into multi-class severity scale
- Build a Streamlit dashboard for visualization and use

---

## ✍️ Author

**Mehdi Akoudad**  
- [Kaggle](https://www.kaggle.com/mehdiakoudad)  
- [LinkedIn](https://www.linkedin.com/in/mehdi-akoudadd)  
- [Medium](https://medium.com/@akoudadmehdi01)

---

## 📄 License

This project is licensed under the MIT License.
