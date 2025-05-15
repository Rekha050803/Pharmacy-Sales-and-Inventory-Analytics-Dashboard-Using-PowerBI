# Pharmacy Sales and Inventory Analytics Dashboard Using PowerBI with Forecasting and Predictive Modeling

This project focuses on leveraging data analytics and machine learning to solve real-world challenges faced by pharmacies, such as inventory management, demand forecasting, expiry tracking, and prescription pattern analysis. It was developed using real sales data from **Tamilnadu Co-operative Pharmacy**, Madurai.

## 🏪 Business Context
- **Pharmacy Name:** Tamilnadu Co-operative Pharmacy  
- **Location:** East Veli Street, Madurai, Tamil Nadu  
- **Objective:** Optimize inventory, predict seasonal demand, reduce wastage, and enhance decision-making through data insights.

---

## 📊 Key Objectives
- Identify sales and prescription trends.
- Predict future demand and stock requirements.
- Classify near-expiry medicines to reduce loss.
- Improve operational efficiency using data-driven methods.

---

## 📥 Data Collection

- **Source:** Tamil Nadu Co-operative Medical Stores Portal  
  🔗 [Visit Portal](https://tncoopws.tn.gov.in/medicaljpc/usermanager/youLogin.jsp)

- **Data Duration:** October 2024 – February 2025  
- **Method:** Bills were downloaded as PDFs and parsed using Python libraries (`PyPDF2`, `pdfplumber`).  
- **Sample Data Fields:**  
  - Bill Number, Date  
  - Doctor & Patient Name  
  - Medicine Name & Manufacturer  
  - Quantity, Expiry, Price, GST, Discount  
  - Total Payment

- 📄 [Sample Dataset Link](https://docs.google.com/spreadsheets/d/1qMRmSIWhoCjH6jh9y78FnBhAW_8NQ6W6/edit?usp=drive_link)

---

## 🧹 Data Preprocessing
- Removed noisy characters and standardized formats.
- Converted data types for accurate computation.
- Handled missing values and duplicates.
- Validated with original PDFs to ensure accuracy.

---

## 📈 Analytical & Statistical Methods

- **Doctor-wise Prescription Pattern**  
  Understand popular medicines prescribed by specific doctors.

- **Hypothesis Testing on Bill Amounts**  
  Identify anomalies and outliers in billing behavior.

- **Pareto Analysis (80/20 Rule)**  
  Highlight top patients contributing to sales.

- **Correlation Between Quantity & Discount**  
  Analyze the impact of bulk discounts on sales.

- **Cohort Analysis**  
  Group patients by first purchase and evaluate retention.

- **Product Life Cycle Curve**  
  Classify medicines into Introduction, Growth, Maturity, Decline phases.

- **RFM Analysis**  
  Segment customers using Recency, Frequency, and Monetary scores.

- **Restock Logic**  
  Intelligent stock refill recommendation based on sales and forecast.

---

## 🤖 Prediction Models

- **ARIMA:** Forecast future sales trends.  
- **SARIMA:** Capture seasonal patterns in medicine demand.  
- **Random Forest Classifier:** Predict if a medicine is safe, near expiry, or expired.  
- **Medication Adherence Prediction:** Identify patients likely to drop off medication.

---

## 📊 Dashboard

All analysis and predictions are consolidated into a Power BI Dashboard offering:
- Interactive filtering and exploration
- Real-time sales trend monitoring
- Stock-level alerts
- Doctor-prescription tracking
- Predictive insights for planning

🔗 [View Dashboard](https://app.powerbi.com/links/ReA0aFVzoV?ctid=562673cb-3a12-4428-9c2e-82d74fd5889a&pbi_source=linkShare)  

![img alt](https://github.com/Rekha050803/Pharmacy-Sales-and-Inventory-Analytics-Dashboard-Using-PowerBI/blob/67b6b130990f8c0a002fbe9cbc069739cc377fac/Pharmacy%20Dashboard/Snapshots/Page1.png)
![img alt](https://github.com/Rekha050803/Pharmacy-Sales-and-Inventory-Analytics-Dashboard-Using-PowerBI/blob/e362c9813d91513d1b8aa46aa67b273af3d8d885/Pharmacy%20Dashboard/Snapshots/Page2.png)
![img alt](https://github.com/Rekha050803/Pharmacy-Sales-and-Inventory-Analytics-Dashboard-Using-PowerBI/blob/e362c9813d91513d1b8aa46aa67b273af3d8d885/Pharmacy%20Dashboard/Snapshots/Page3.png)
![img alt](https://github.com/Rekha050803/Pharmacy-Sales-and-Inventory-Analytics-Dashboard-Using-PowerBI/blob/e362c9813d91513d1b8aa46aa67b273af3d8d885/Pharmacy%20Dashboard/Snapshots/Page4.png)

🎥 [Dashboard Walkthrough Video](https://drive.google.com/file/d/1TzLw6Na8McX-zzxVVAEEG715MXMozhqj/view?usp=sharing)

---

## 🧑‍💻 Code & Tools

- **Languages & Tools:** Python, Power BI, Pandas, Matplotlib, Statsmodels, Scikit-learn  
- **Libraries Used:**  
  - `PyPDF2`, `pdfplumber` – PDF text extraction  
  - `pandas`, `numpy` – Data manipulation  
  - `matplotlib`, `seaborn` – Visualization  
  - `statsmodels` – ARIMA, SARIMA  
  - `sklearn` – Random Forest Classification

🔗 [Google Colab Notebook](https://colab.research.google.com/drive/1Ae-iLvD8h7r4AR00UxYPUVCmZUiDxTYt?usp=sharing)

---

## ✅ Outcome

This project:
- Reduced medicine expiry waste through proactive classification.
- Improved stock management via forecasting and restocking logic.
- Revealed valuable prescription and purchasing patterns.
- Enabled informed, strategic pharmacy decision-making using data.

---

## ✍️ Read the Full Blog

Check out the detailed blog post here: [**Pharmacy Sales and Inventory Analytics Using Power BI**](https://medium.com/@rekha.prakash0508/tablets-trends-where-healthcare-meets-data-science-0673dc349776)
