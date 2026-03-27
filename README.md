# Developer Survey Analytics Dashboard

## 📌 Project Overview

This project is an end-to-end data analytics workflow that analyzes global developer survey data to identify current technology usage, future trends, and demographic patterns.

The project demonstrates how raw, unstructured data can be cleaned, transformed, and visualized to generate meaningful insights.

---

## 🎯 Objectives

* Analyze current technology usage among developers
* Identify future technology trends
* Understand demographic distributions (age, country, education)
* Convert raw survey data into a structured format for analysis

---

## 📂 Dataset

* Source: Developer Survey Dataset
* The raw dataset contains multi-value fields (e.g., "Python;Java;C++")
* These fields were transformed into a structured long format for analysis

---

## ⚙️ Data Processing (Python)

The data preparation was performed using Python (Pandas):

* Removed inconsistencies and handled missing values
* Split multi-value fields into individual rows
* Converted wide-format data into long-format structure
* Created a unified dataset combining:

  * Technology usage (Worked)
  * Future preferences (Want)
  * Demographic information

---

## 📊 Dashboard

The dashboard was created using IBM Cognos.

### Key Sections:

* **Current Technology Usage**

  * Most used programming languages, databases, platforms, and frameworks

* **Future Technology Trends**

  * Technologies developers want to work with

* **Demographics**

  * Distribution by age, country, and education level

---

## 📈 Key Insights

* JavaScript, SQL, and Python are among the most widely used technologies
* Cloud platforms like AWS, Azure, and Google Cloud dominate usage and demand
* Modern frameworks such as React and Node.js show strong adoption
* Majority of developers fall within the 25–34 age group

---

## 📁 Project Structure

* `developer_survey_data_preparation.ipynb` → Data cleaning and transformation
* `final_dashboard_sample.csv` → Dashboard-ready dataset (sample)
* `dashboard.pdf` → Final dashboard visualization

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Jupyter Notebook
* IBM Cognos Analytics

---

## 📌 Note

A sample dataset is included due to file size limitations.
The full dataset can be regenerated using the provided notebook.

---

## 🚀 Conclusion

This project demonstrates the complete data analytics pipeline — from raw data processing to insight generation through dashboards — highlighting real-world data handling and analytical skills.
