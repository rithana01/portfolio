# Data Scientist

### Education
M.S. Data Science, University of Malaya (2024-2026)
BSc. Genetics, University of Malaya (2020-2024)
Mandarin Language, National Taiwan Normal University (2024-2025)

### Work Experience
Accreditation Officer @ Department of Standards Malaysia
• Evaluated and assisted in accreditation of certification bodies to ensure they meet national and international standards.
• Observed thorough assessments and audits to verify compliance with accreditation requirements.
• Provided guidance and support to conformity assessment bodies to enhance their quality management systems.
• Collaborated with stakeholders to promote accreditation to enhance trust and reliability in products, services, and systems.
• Uphold the integrity and impartiality of accreditation activities to foster confidence in conformity assessment results.

Laboratory Technician @ National Population and Family Development Board (LPPKN) · Internship
• Assisted in sample preparation, analysis, and data collection for a wide range of laboratory tests and studies.
• Operated laboratory equipment and instruments, ensuring their proper maintenance and calibration.
• Performed multiple sperm analyses of patients and sperm preparation for IUI such as the swim-up technique, contributing to the laboratory's role in reproductive health and family planning.

### Projects
### Predictive Modeling for Telco Customer Retention
## Overview
This project analyzes customer churn in the telecom industry using **machine learning, deep learning, and unsupervised learning techniques**. The dataset, sourced from Kaggle, consists of **33 variables and 7,043 observations**, covering customer demographics, service details, and churn factors.

## 🚀 Techniques Used

### 1️⃣ Data Preprocessing & Feature Engineering
- **Categorical Encoding & Missing Value Handling**: Imputed missing *Total Charges* using *Tenure Months* and *Monthly Charges*.
- **Feature Transformation**: Converted *Tenure Months* into categorical bins for better interpretability.
- **Feature Selection**: Removed redundant features (*CustomerID, Country, State, Churn Score, CLTV*).
- **Data Balancing**: Addressed **class imbalance** using **Synthetic Data Generation (SMOTE or similar techniques)**.

### 2️⃣ Machine Learning Models
- **Logistic Regression**: Simple and interpretable for binary classification.
- **Random Forest**: Handles high-dimensional data efficiently.
- **Gradient Boosting (XGBoost)**: Boosts predictive performance and reduces bias.
- **K-Nearest Neighbors (KNN)**: Suitable for pattern recognition in customer data.
- **Support Vector Machines (SVM)**: Effective for complex decision boundaries.

### 3️⃣ Deep Learning Models
- **Artificial Neural Networks (ANNs)**: Captures intricate customer behavior patterns.
- **Convolutional Neural Networks (CNNs)**: Used for automatic feature extraction.

### 4️⃣ Unsupervised Learning for Customer Segmentation
- **K-Means Clustering & K-Medoids**: Identifies distinct customer groups.
- **Hierarchical Clustering**: Provides insights into customer segment structures.
- **Cluster Validation Metrics**: Applied **Silhouette, Elbow, and Gap Statistics** to determine optimal cluster count.

### 5️⃣ Model Evaluation Metrics
- **Confusion Matrix, Accuracy, Precision, Recall, F1-score** for classification assessment.
- **AUC-ROC Curve** to evaluate model discrimination ability.

## 🎯 Business Impact & Applications
✅ **Predictive modeling** enables proactive customer retention strategies.
✅ **Segmented marketing campaigns** improve customer engagement.
✅ **Churn analysis insights** help optimize telecom service offerings.

📌 Check out the full code and analysis in this repository! 🚀
