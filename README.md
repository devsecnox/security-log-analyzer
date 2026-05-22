# 🛡️ Security Log Analyzer

This project is a Python-based automated security log parser and analysis tool designed to inspect server logs, identify potential anomalies, and perform risk analysis using data science techniques. It simulates various cyber attack scenarios and provides comprehensive visual reports.

## 🚀 Features

* **Data Simulation:** Generates realistic log data for 6 different attack types, including DDoS, Phishing, and Malware.
* **Smart Data Cleaning:** Automatically detects missing or corrupted data (NaN) and handles anomalies using statistical imputation techniques.
* **Visual Reporting & Analytics:**
    * 📊 Distribution of attack types and firewall mitigation/block rates.
    * 📈 Histogram analysis of incident risk scores.
    * 📦 Risk range assessments grouped by attack vectors (Boxplot analysis).

## 🛠️ Tech Stack

* **Python 3.x**
* **Pandas:** For advanced data manipulation and security log cleaning.
* **Seaborn & Matplotlib:** For generating comprehensive data visualizations.
* **Random:** For stochastic security log simulation.

## 💻 Installation & Usage

1. Install the required dependencies:
    ```bash
    pip install pandas seaborn matplotlib
    ```
2. Execute the analysis tool:
    ```bash
    python security_log_analyzer.py
    ```

## 📈 Sample Analysis Output

Upon execution, the script automatically processes the data, exports a cleaned dataset named `temiz_guvenlik_loglari.csv`, and displays or saves the corresponding security analysis charts as `.png` files.

---

## 📊 Visual Analytics

The generated analytical charts from the project output are shown below:

### 1. Attack Type Distribution
![Saldırı Türleri](saldiri_turleri.png)

### 2. Attack Vectors vs. Mitigation Status
![Engellenme Durumu](saldırı_türleri_engelleme_durumu.png)

### 3. Risk Score Density & Distribution
![Risk Dağılımı](risk_dagilimi.png)

---
*Developed as a core technical project by [Muhammed Emir Tohumcu](https://linkedin.com/in/muhammed-emir-tohumcu-aa7296260/).*
