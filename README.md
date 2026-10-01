# 📊 Google Trends Exploratory Data Analysis (EDA)

An Exploratory Data Analysis (EDA) project leveraging the **`pytrends`** library to analyze search trends, regional interest, and time-series patterns for major technology keywords such as **Artificial Intelligence**, **Machine Learning**, **Data Science**, **Cloud Computing**, and **Deep Learning**.

---

## 📌 Project Overview

This project extracts real-time and historical search data directly from **Google Trends** using Python. The goal is to identify global interest, geographical distribution, and comparative popularity of key tech domain trends over time.

---

## 🚀 Key Features & Highlights

- **Regional Interest Analysis:** Identifies top countries searching for specific tech terms.
- **Geographical Visualization:** Interactive global maps showing search density using Plotly.
- **Time Series Tracking:** Analyized search volume movement over time.
- **Multi-Keyword Comparison:** Side-by-side comparative analysis across 5 major tech domains.

---

## 🛠️ Tech Stack & Tools

- **Programming Language:** Python 3.10+
- **Data Retrieval:** `pytrends` API
- **Data Manipulation:** `pandas`
- **Data Visualization:** `matplotlib`, `seaborn`, `plotly`
- **Development Environment:** VS Code / Jupyter Notebook

---

## 📊 Visualizations & Observations

### 1. Country-Wise Search Interest for 'Artificial Intelligence'

Top countries actively searching for *Artificial Intelligence*:

<img width="1220" height="678" alt="Screenshot 2026-10-01 212914" src="https://github.com/user-attachments/assets/3d47df25-ec68-488b-89e3-b89b6353297b" />


#### 📝 Observations:
- **Top Searchers:** Countries like **Singapore** and **South Korea** rank highest in search interest for AI.
- **Global Spread:** High concentration of interest observed across Asian, European, and African nations.

---

### 2. Time-Wise Search Interest for 'Artificial Intelligence'

Tracking AI search popularity fluctuations over time:

<img width="1263" height="688" alt="Screenshot 2026-10-01 213309" src="https://github.com/user-attachments/assets/7e82dfe8-426e-4ad1-bc4a-95bf627cfb28" />

#### 📝 Observations:
1. **Overall Trend:** The search interest for 'Artificial Intelligence' grows significantly overall between late 2025 and mid-2026.
2. **Highest Peak:** Search popularity hits its maximum score of **100** around **June 2026**.
3. **Lowest Point:** The lowest search score (~35) occurs in **January 2026**.
4. **Recent Pattern:** After reaching its peak in June 2026, the search interest fluctuates and drops by late September 2026.

---

### 3. Multiple Keyword Comparison Over Time

Comparative interest between *Artificial Intelligence*, *Cloud Computing*, *Data Science*, *Machine Learning*, and *Deep Learning*:

<img width="1477" height="736" alt="Screenshot 2026-10-01 213330" src="https://github.com/user-attachments/assets/45109f41-9e2b-4783-80e2-9ef702801f7c" />


#### 📝 Observations:
1. **Highest Search Volume:** **Machine Learning (Red Line)** remains the most searched keyword overall, reaching a peak score of **100** in mid-2026.
2. **Second Most Popular:** **Artificial Intelligence (Blue Line)** maintains the second-highest search interest throughout the period (ranging between 26 and 74).
3. **Moderate Trends:** **Data Science (Green Line)** and **Deep Learning (Purple Line)** display moderate search activity, with Data Science remaining slightly higher.
4. **Lowest Interest:** **Cloud Computing (Orange Line)** records the lowest relative search interest among all five terms (mostly between 7 and 29).
5. **Key Peaks:** All keywords share a synchronized pattern—a significant surge between **March 2026 and June 2026**, followed by a decline towards late September 2026.

---

## 📈 Project Summary

This EDA reveals critical insights into public interest surrounding modern technologies:
- **Machine Learning** consistently dominates global search volume, followed closely by **Artificial Intelligence**.
- A synchronized surge across all technology topics occurred during **Q2 2026 (March–June)**, highlighting a period of increased global attention or major developments in the tech sector.
- **Asian markets** (particularly Singapore and South Korea) show the highest relative interest density in AI topics.

---

## 💻 How to Run Locally

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/rakeshsenSE/google-trends-tech-eda.git]
   cd google-trends-tech-eda
