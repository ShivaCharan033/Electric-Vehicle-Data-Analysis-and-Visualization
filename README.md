# 🚗 Electric Vehicle Data Analysis and Visualization

## 📌 Project Overview
This project provides an in-depth analysis of **electric vehicle (EV) adoption trends** using **geospatial, statistical, and machine learning techniques**.  
It visualizes **vehicle population distributions, tracks historical adoption trends, and evaluates EV characteristics** such as **price, range, and charging station accessibility**.

---

## 🗂️ Dataset
- **electric_vehicle_population_data.csv** - Contains EV registration records, model year, price, electric range, and location data.
- **Images & Visualizations** - Includes **heatmaps, classification reports, confusion matrices, scatter plots**, and **trend analysis graphs**.

---

## 📊 Key Visualizations

### **1️⃣ Geospatial Heatmap**
📍 This heatmap highlights **EV adoption across the U.S.**, with regions like Seattle and California showing the highest concentration.

![EV Heatmap](/Users/charan/Desktop/Semesters/SEM_2/AIT614/FINAL PROJECT/WhatsApp Image 2024-04-28 at 20.25.00 (1).jpeg)  
*(Replace `images/ev_heatmap.png` with your actual uploaded image path)*

---

### **2️⃣ Electric Vehicle Growth Over Time**
📈 This stacked area chart shows the growth of **Battery Electric Vehicles (BEV)** and **Plug-in Hybrid Electric Vehicles (PHEV)**.

![EV Growth Chart](images/ev_growth_chart.png)

---

### **3️⃣ Classification Model Results**
We built a **machine learning classification model** to predict EV trends, achieving **high accuracy**.

Accuracy: 0.99997 Precision, Recall, F1-score: 1.00

yaml
Copy
Edit

📊 **Classification Report:**
![Classification Report](images/classification_report.png)

🔍 **Confusion Matrix:**
![Confusion Matrix](images/confusion_matrix.png)

---

### **4️⃣ Scatter Plot Matrix**
📊 This scatter plot matrix analyzes **price, range, and model year** correlations among different EV models.

![Scatter Plot](images/scatter_plot.png)

---

## 🔍 Machine Learning Model
- **Classification**: Trained a machine learning model to **classify EV types and adoption trends**.
- **Performance**: Achieved **near-perfect accuracy**, suggesting strong patterns in EV adoption.

---

## ⚙️ How to Run This Project

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/yourusername/electric-vehicle-analysis.git
cd electric-vehicle-analysis
