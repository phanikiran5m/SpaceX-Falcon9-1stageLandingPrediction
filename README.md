# 🚀 SpaceX Falcon 9 First Stage Landing Prediction
### *IBM Data Science Professional Certificate Capstone Project*

---

## 📌 **Project Overview**
The primary objective of this project is to **predict whether the first stage of a SpaceX Falcon 9 rocket will land successfully**. 

* **Economic Impact:** SpaceX significantly reduces launch costs (down to **~$62M** vs **~$165M** for competitors) by reusing the first stage. 
* **Goal:** By predicting landing success, we can estimate launch costs and provide data-driven insights for competitive analysis in the aerospace industry.

---

## 🛠 **Tech Stack & Methodology**
This project follows a rigorous data science lifecycle, mirroring high-integrity software integration processes:

### **1. Data Acquisition**
* **REST API Integration:** Utilized the SpaceX API for historical launch data.
* **Web Scraping:** Extracted supplemental data from Wikipedia using **BeautifulSoup**.

### **2. Data Wrangling & EDA**
* **Preprocessing:** Cleaned data, handled missing values, and performed **One-Hot Encoding** using **Pandas** and **NumPy**.
* **SQL Analysis:** Executed complex queries to identify trends and patterns in launch success.

### **3. Visualization & Interactive Analytics**
* **EDA:** Created visualizations using **Matplotlib** and **Seaborn**.
* **Geospatial Analysis:** Built interactive maps with **Folium** to visualize launch site proximity.
* **Dashboards:** Developed a real-time interactive dashboard using **Plotly Dash**.

### **4. Machine Learning (Classification)**
Implemented and compared four major algorithms using **Scikit-Learn**:
* **Logistic Regression**
* **Support Vector Machines (SVM)**
* **Decision Trees**
* **K-Nearest Neighbors (KNN)**
* **Optimization:** Performed hyperparameter tuning using **GridSearchCV** to maximize model accuracy.

---

## 🚀 **Key Features**
* **Automated Pipeline:** Designed an end-to-end flow from raw API data extraction to a predictive machine learning model.
* **Advanced Feature Engineering:** Processed variables such as **Payload Mass**, **Orbit Type**, **Launch Site**, and **Flight Number**.
* **Decision Support Logic:** Provides a probability-based approach to determine the financial feasibility of rocket stage recovery.

---

## 📊 **Results & Conclusion**
* **Model Accuracy:** Achieved a high prediction accuracy (approx. **83.3%**) across all models.
* **Success Trends:** Identified that success rates have improved significantly over time as SpaceX flight numbers increased.
* **Site Specifics:** Determined that specific launch sites (e.g., KSC LC-39A) have higher success correlations.

---

## 👤 **Author**
**Phani Kiran** *Lead Software Architect | 17+ Years Experience in ADAS & Avionics*

---
