[**English**](README.md) | [**فارسی**](README_FA.md)
---
# 🚕 **Gett Taxi – Failed Orders Analysis (EDA Project)**  

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?logo=jupyter)

---

## 📘 Project Overview

This project focuses on **exploratory data analysis (EDA)** of the **Gett Taxi “Failed Orders” dataset**, a public dataset commonly used for analytics and interview challenges.  
The dataset captures ride request and offer data from the Gett ride-hailing platform, aiming to understand **why some ride orders fail to complete**.

The notebook explores patterns behind failed orders, customer behavior, and driver-offer interactions — using data visualization, feature exploration, and statistical analysis in Python.

---

## 🧩 Project Structure

📂 **Gett_Failed_Orders_EDA**  
├── [**eda.ipynb**](eda.ipynb)  
└── README.md  

---

## ⚙️ Step-by-Step Workflow  

### 1️⃣ Data Source  

**Dataset:** Gett Taxi — Failed Orders Dataset (publicly available on Kaggle)  
**Files Used:**  
- `data_orders.csv`  
- `data_offers.csv`  

These files include customer ride requests, driver offers, order timestamps, status flags, and pricing information.

---

### 2️⃣ Exploratory Data Analysis (Python)  

The notebook performs a full exploratory data workflow, including:  

- Data loading and inspection (shape, info, missing values)  
- Cleaning and preprocessing of order and offer data  
- Merging `orders` and `offers` tables for unified analysis  
- Detecting anomalies and failed ride patterns  
- Visualizing order distribution, cancellations, and driver response rates  
- Feature correlation analysis to identify impactful variables  

📄 **File:** `eda.ipynb`

---

### 3️⃣ Insights  

The analysis highlights several key findings:  
- A significant percentage of failed orders occur during **peak hours**.  
- **Driver response time** and **offer count** directly affect success rate.  
- Some **city zones** consistently show higher cancellation ratios.  
- Customer-side cancellations often correlate with long estimated arrival times.  

---

## 🧠 Tools & Technologies  

| Category | Tools 

|-----------|--------|
| Language | Python 3.x |
| Libraries | pandas, numpy, matplotlib, seaborn |
| Environment | Jupyter Notebook |
| Data Source | Kaggle – Gett Taxi Failed Orders |

---

## 🚀 How to Run Locally  

### Prerequisites  
- Python 3.9+  
- Jupyter Notebook  

Install dependencies:  
```bash
pip install pandas numpy matplotlib seaborn
```
![gett taxi](https://github.com/user-attachments/assets/8d63ded4-90c1-453e-9853-1710d83e8b0a)
![gett taxi 2](https://github.com/user-attachments/assets/93034ccf-16c7-4128-bfd6-faf128b88fcb)
![gett taxi 3](https://github.com/user-attachments/assets/f4a79eb3-19e5-496d-b17e-ef75ebb67b42)





