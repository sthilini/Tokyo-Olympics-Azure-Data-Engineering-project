# 🏅 Olympic Data Analytics | Azure End-to-End Data Engineering Project  

## 📘 Overview  
This project demonstrates an **end-to-end data engineering workflow on Microsoft Azure** using Olympic Games data.  
The dataset was obtained from **Kaggle** and uploaded to a **GitHub repository**.  
Data was then extracted from the **GitHub API** using **Azure Data Factory**, processed with **Azure Databricks**, and analyzed using **Azure Synapse Analytics** to gain insights from the transformed data.  

---

## 🧩 Architecture  
1. **Data Source:**  
   - Olympic dataset sourced from Kaggle  
   - Uploaded to GitHub and accessed through the GitHub API  

2. **Azure Data Factory (ADF):**  
   - Created and scheduled a pipeline to extract the dataset from the GitHub API  
   - Stored the extracted data in **Azure Data Lake Storage Gen2**  

3. **Azure Data Lake Storage Gen2 (ADLS):**  
   - Used to store both raw and transformed data in different layers (Bronze and Silver)  

4. **Azure Databricks:**  
   - Loaded the raw data from ADLS  
   - Wrote **PySpark code** to clean and transform the data  
   - Loaded the transformed data back into ADLS  

5. **Azure Synapse Analytics:**  
   - Connected to the transformed data in ADLS  
   - Ran **SQL queries** to analyze and gain insights from the transformed dataset  

---

## 🛠️ Technologies Used  
- **Azure Data Factory** – Data ingestion and pipeline orchestration  
- **Azure Data Lake Storage Gen2** – Data storage for raw and transformed layers  
- **Azure Databricks** – Data transformation and processing using PySpark  
- **Azure Synapse Analytics** – Querying and data analysis  
- **Python (PySpark)** – Data transformation scripting  
- **SQL** – Querying transformed data  
- **GitHub** – API data source and version control  
- **Kaggle** – Original dataset source  

---

## 🎯 Objectives  
- Build a complete **end-to-end data engineering solution** on Azure  
- Automate **data ingestion from the GitHub API** using Azure Data Factory  
- Implement **data lake architecture** for storing raw and transformed data  
- Perform **data cleaning and transformation** using PySpark in Databricks  
- Use **Synapse Analytics** to query transformed data and extract insights  
