# 🏨 Hotel Booking Demand Analysis and Machine Learning

A complete end-to-end Machine Learning project that analyzes hotel booking data, performs data preprocessing and visualization, and predicts whether a hotel booking will be canceled.

## 📌 Project Overview

The objective of this project is to analyze hotel booking data and build machine learning models capable of predicting booking cancellations. The project includes data cleaning, exploratory data analysis (EDA), feature engineering, preprocessing, model training, evaluation, and business insights.

This project demonstrates a complete machine learning workflow using the Hotel Booking Demand dataset from Kaggle.

---

## 📂 Dataset

**Dataset:** Hotel Booking Demand Dataset

Source:
https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

The dataset contains booking information for city and resort hotels, including:

- Hotel Type
- Lead Time
- Arrival Date
- Number of Adults, Children & Babies
- Meal Type
- Market Segment
- Distribution Channel
- Country
- Deposit Type
- Previous Cancellations
- Average Daily Rate (ADR)
- Booking Status
- and many other booking-related features.

---

## 🎯 Project Objectives

- Understand the dataset structure
- Clean and preprocess raw data
- Handle missing values and duplicates
- Perform Exploratory Data Analysis (EDA)
- Create meaningful visualizations
- Engineer new features
- Train multiple Machine Learning models
- Compare model performance
- Predict hotel booking cancellations

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


## 📊 Exploratory Data Analysis

The project includes visualizations such as:

- Hotel Type Distribution
- Booking Cancellation Analysis
- Meal Type Distribution
- Market Segment Distribution
- Deposit Type Analysis
- Lead Time Distribution
- Average Daily Rate (ADR) Distribution
- Correlation Heatmap
- Boxplots for Outlier Detection

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Removing duplicate records
- Feature engineering
- One-Hot Encoding
- Train-Test Split
- Feature Scaling using StandardScaler
- Outlier treatment using the IQR method

---

## 🤖 Machine Learning Models

The following classification models were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)

---

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

The best-performing model was selected based on these evaluation metrics.

---

## 💡 Key Insights

- Lead Time is an important factor influencing booking cancellations.
- Deposit Type has a significant impact on cancellation behavior.
- Previous cancellation history contributes to future cancellation prediction.
- Feature engineering improved model performance.
- Machine learning can effectively identify bookings with a high likelihood of cancellation.


## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/Yoshitapol/HotelBookingDemand_DataVisualization_project.git
```

2. Navigate to the project folder

```bash
cd HotelBookingDemand_MLProject
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open the notebook

```bash
jupyter notebook
```

5. Run all notebook cells sequentially.

---

## 📌 Results

The project successfully predicts hotel booking cancellations using machine learning techniques after performing comprehensive data cleaning, preprocessing, visualization, and feature engineering.

The developed model can help hotels:

- Identify bookings likely to be canceled
- Improve occupancy planning
- Optimize revenue management
- Support data-driven business decisions

---

## 👩‍💻 Author

**Yoshita Vishal Pol**

- LinkedIn: https://www.linkedin.com/in/yoshita-pol-b98733302
- GitHub: https://github.com/Yoshitapol
