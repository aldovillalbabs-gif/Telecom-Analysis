# Telecom-Analysis
Customer usage analysis and segmentation for ConnectaTel telecom dataset using Python.
# 📊 Telecom Analysis – ConnectaTel Customer Usage

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aldovillalbabs-gif/Telecom-Analysis/blob/main/notebooks/Project-ConnectaTel.ipynb)

Customer usage analysis and segmentation for the **ConnectaTel telecom dataset** using Python.

---

# 📌 Project Overview

This project analyzes customer communication behavior for **ConnectaTel**, a telecom company operating in Latin America.

The goal is to:

✔ Understand communication patterns  
✔ Detect extreme usage behavior (outliers)  
✔ Segment customers by usage and age  
✔ Generate business insights for telecom plan optimization  

Through **Exploratory Data Analysis (EDA)** and segmentation techniques, the analysis identifies high-value customers and potential opportunities for improving telecom service offerings.

---

# 📂 Dataset

The analysis uses three datasets located in the `data/` directory:

### 👤 users_latam.csv
Customer demographic information such as:

- Age
- Telecom plan
- User ID

### 📞 usage.csv
Customer communication activity including:

- Messages sent
- Calls made
- Total call minutes

### 📦 plans.csv
Details of the telecom plans offered by ConnectaTel.

---

# 🗂 Repository Structure

Telecom-Analysis
│
├── 📁 data
│ ├── plans.csv
│ ├── usage.csv
│ └── users_latam.csv
│
├── 📁 notebooks
│ └── Project-ConnectaTel.ipynb
│
└── README.md


---

# 🔎 Analysis Workflow

The project follows a structured **data analysis pipeline**.

### 🧹 1. Data Cleaning
- Validation of missing values  
- Detection of inconsistencies  
- Dataset preparation  

### 📊 2. Data Aggregation
Usage data was aggregated per user to compute:

- Total messages
- Total calls
- Total call minutes

### 📈 3. Exploratory Data Analysis (EDA)

Visualizations were used to analyze:

- Age distribution
- Communication activity
- Differences between telecom plans

### 📉 4. Distribution Analysis

Histograms were used to evaluate distributions of:

- Age
- Messages
- Calls
- Call minutes

### 🚨 5. Outlier Detection

Outliers were detected using:

- **Boxplots**
- **Interquartile Range (IQR) method**

Variables analyzed:

- Messages sent
- Calls made
- Call minutes

### 👥 6. Customer Segmentation

Customers were segmented based on usage behavior.

| Segment | Criteria |
|------|------|
| 🟢 Low Usage | Calls < 5 and Messages < 5 |
| 🟡 Medium Usage | Calls < 10 and Messages < 10 |
| 🔴 High Usage | All other cases |

Users were also segmented by age:

| Age Segment | Criteria |
|------|------|
| 🧑 Young | Age < 30 |
| 👨 Adult | Age < 60 |
| 👴 Senior | Age ≥ 60 |

---

# 💡 Key Insights

🔹 Most customers fall into the **medium usage segment**, indicating moderate engagement with telecom services.

🔹 **Adult users** represent the largest demographic group among ConnectaTel customers.

🔹 A smaller subset of users generates **significantly higher call minutes**, suggesting potential high-value customers.

🔹 Extreme usage patterns likely represent **business or heavy communication users**.

---

# 🚀 Business Recommendations

Based on the analysis, several strategic opportunities emerge.

### ⭐ Create Premium Plans
Heavy users with high call minutes may benefit from **premium telecom plans**.

### 🎯 Target Medium Usage Customers
The largest customer segment could be targeted with **marketing campaigns to increase engagement**.

### 💼 Identify High-Value Customers
Extreme usage users may represent **enterprise or professional customers**.

### 🔄 Optimize Telecom Plans
Usage patterns suggest opportunities to **redesign existing plans to better match customer behavior**.

---

# ▶️ How to Run This Project

The notebook is fully reproducible using **Google Colab**.
Click the **Open in Colab** button at the top of this page.


---

# 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

---

# 👨‍💻 Author

**Aldo Villalba**

Data Analyst | Operations & Business Analytics

GitHub  
https://github.com/aldovillalbabs-gif



