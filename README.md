# **Closed Encounters Analysis & Missing Data Investigation**

### **Project Overview**
This project aims to identify missing encounters from a client's **Electronic Health Records (EHR)** system by comparing two datasets: **Closed Encounters** from the client's EHR and **Imported Closed Encounters** from a database. The goal is to detect missing encounters, analyze the reasons behind their absence, and improve the data import process.

### **Objectives:**
1. **Identify Missing Encounters**: Compare **Closed Encounters** and **Imported Closed Encounters** to pinpoint missing encounters.
2. **Analyze Missing Data**: Investigate the reasons behind missing encounters (e.g., incomplete data or mismatched identifiers).
3. **Generate Insights**: Provide a detailed report summarizing the analysis and findings.

### **Tools & Technologies Used:**
- **Python**: For data analysis and manipulation.
- **Pandas**: For data cleaning and manipulation.
- **Matplotlib & Seaborn**: For data visualization and insights generation.
- **Jupyter Notebooks**: For interactive analysis and reporting.

### **Repository Structure:**
- `missing_data_analysis.py`: Python script for analyzing the missing encounters.
- `visualize_missing_data.py`: Script to visualize patterns in missing data.
- `missing_data_report.txt`: Detailed report summarizing the analysis and findings.

### **Key Findings:**

* **Missing Values**: Identified missing values in key fields such as **Provider Name**, **Date of Service**, and **CPT Code**.
* **Patterns & Insights**: Patterns were detected, revealing potential issues with incomplete or incorrect data leading to missing encounters.

### **Conclusion:**

This project helps in identifying missing encounters and understanding why some data may not have been successfully imported. It aims to improve the accuracy of data imports in healthcare systems.
