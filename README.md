# valle-del-cauca-business-analysis
Data analysis project exploring business structure in Valle del Cauca, Colombia using Python, SQL, and data visualization.
# 📊 Business Analysis of Companies in Valle del Cauca, Colombia

## 🧠 Project Overview

This project analyzes the business structure of companies located in Valle del Cauca, Colombia. The objective is to identify key patterns in company size, economic activity, and geographic distribution to better understand the regional business ecosystem.

---

## 🎯 Objectives

* Analyze the distribution of companies by size
* Identify the most common economic sectors (CIIU classification)
* Explore geographic concentration by municipality
* Detect data quality issues and limitations

---

## 🛠️ Tools & Technologies

* Python (Pandas)
* Google Colab
* SQL (for complementary queries)
* Matplotlib (data visualization)

---

## 📂 Dataset

The dataset contains business registration records, including:

* Company size
* Economic activity (CIIU codes)
* Municipality
* Registration date

---

## 🔍 Key Findings

### 1. Company Size Distribution

Microenterprises overwhelmingly dominate the business ecosystem in Valle del Cauca.

* Microenterprises represent more than **95%** of all companies
* Very low presence of medium and large companies

👉 This suggests a highly fragmented economy with limited large-scale industrial activity.

---

### 2. Economic Activity Concentration

The most common sectors are:

* Retail trade of food and basic goods
* Restaurants and food services
* Pharmaceutical and personal care products
* Clothing retail

👉 The economy is strongly oriented toward **consumption and service-based activities**.

---

### 3. Geographic Concentration

The analysis revealed a high concentration of companies in a single municipality:

* Tuluá accounts for a significant portion of the dataset

👉 This may indicate:

* A real economic concentration
* Or a dataset bias (data collection limitation)

---

### 4. Data Quality Limitations

The `FEC-MATRICULA` (registration date) field presented missing or unprocessable values (`NaT`), which prevented time-based analysis.

👉 As a result, trends in company creation over time were not included.

---

## 📈 Conclusion

The Valle del Cauca business landscape is characterized by a strong dominance of microenterprises and a concentration in retail and service sectors. While the dataset provides valuable insights into economic structure, it also highlights limitations in data quality and geographic representation.

---

## 🚀 Future Improvements

* Incorporate additional datasets for better geographic coverage
* Include time-series analysis with improved data quality
* Develop an interactive dashboard (Power BI or Tableau)

---

## 📌 Author

Daniel Ortiz
Aspiring Data Analyst | Python | SQL | Business Intelligence

GitHub: https://github.com/daniel-ortiz-mu
