# 🎓 Task 03 – College Event Feedback Analysis

## Internship Program  
**Future Interns – Data Science & Analytics Internship**  
Track Code: DS

---

## 📌 Project Title  
College Event Feedback Analysis using Survey Data

---

## 🎯 Objective  
The objective of this project is to analyze student feedback collected after a college event or course and uncover satisfaction trends.  
The analysis aims to help organizers understand strengths, identify improvement areas, and make data-driven decisions for future events.

---

## 📂 Dataset  
The dataset used in this project is a student feedback survey dataset containing numeric ratings provided by students on a scale of 1–10 for various aspects of the event/course.

### Dataset Attributes:
- Subject Knowledge  
- Concept Clarity  
- Presentation Quality  
- Assignment Difficulty  
- Doubt Solving  
- Course Structure  
- Student Support  
- Course Recommendation  

Each row represents feedback submitted by one student.

---

## 🛠 Tools & Technologies  
- Google Colab  
- Python  
- pandas  
- seaborn  
- matplotlib  

---

## 🧠 Methodology  

### 1️⃣ Data Cleaning  
- Removed unnecessary index column  
- Verified data types and handled missing values  
- Renamed columns for better readability  

### 2️⃣ Feature Engineering  
- Computed an **Overall Satisfaction Score** by averaging multiple rating columns  

### 3️⃣ Sentiment Analysis  
- Classified student feedback into:
  - **Positive**
  - **Neutral**
  - **Negative**  
- Sentiment was derived using rule-based classification from overall satisfaction scores  

### 4️⃣ Visualization  
- Sentiment distribution bar chart  
- Overall satisfaction score distribution  
- Average rating comparison across feedback categories  

---

## 📊 Key Insights  

- Majority of students expressed **Neutral sentiment**, indicating moderate satisfaction  
- A significant number of students showed **Positive sentiment**, reflecting good overall experience  
- Very few **Negative responses**, suggesting minimal dissatisfaction  
- Subject knowledge and concept clarity received higher ratings  
- Assignment difficulty and student support showed scope for improvement  

---

## 📈 Conclusion  

This project demonstrates how survey-based feedback data can be transformed into meaningful insights using data analytics techniques.  
The findings can help improve future college events and academic programs by focusing on student satisfaction and continuous improvement.

---

## 📁 Files Included  

- Jupyter Notebook / Google Colab file  
- Dataset (CSV)  
- Screenshots of analysis and visualizations  
- README.md  

---

## 👤 Author  
Kushal K  
Data Science & Analytics Intern – Future Interns
