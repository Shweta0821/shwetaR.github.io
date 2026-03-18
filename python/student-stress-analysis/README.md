# 🧠 Student Stress & Academic Performance Analysis

## 📌 Project Overview
This project analyzes the impact of physiological stress on student academic performance using biometric sensor data such as Electrodermal Activity (EDA), Heart Rate (HR), and Body Temperature.  

The analysis includes feature engineering (RMSSD, HRV), time-based stress segmentation, and correlation analysis to understand how stress affects exam outcomes.

---

## 🎯 Objectives
- Analyze stress patterns during exams  
- Derive HRV and RMSSD from IBI data  
- Identify peak stress phases  
- Study correlation between stress and grades  

---

## 📊 Dataset
The dataset includes:
- Inter-Beat Interval (IBI)
- Heart Rate (HR)
- Electrodermal Activity (EDA)
- Body Temperature
- Student Demographics
- Midterm & Final Scores  

---

## ⚙️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  

---

## 🔧 Key Steps Performed

### 1. Data Cleaning
- Handled missing values  
- Standardized demographic data using RegEx  

### 2. Feature Engineering
- Calculated RMSSD from IBI data  
- Derived Heart Rate Variability (HRV)  

### 3. Data Integration
- Merged multiple datasets into a unified dataframe  

### 4. Temporal Analysis
- Segmented exam into phases  
- Identified peak stress periods  

### 5. Visualization
- Time-series plots for HR  
- Distribution charts for grades  

---

## 📈 Key Insights
- Highest stress observed in the **final phase of exams**  
- Students with higher HRV performed better  
- Physiological burnout observed before performance drop  

---

## 📷 Sample Output

![HR Graph](./images/hr-plot.png)

![EDA Analysis](./images/eda-analysis.png)

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib seaborn
python main.py
