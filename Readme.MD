# 🚀 End-to-End Data Engineering Project: SQL Server ➔ Azure ➔ Power BI

Welcome to my inaugural **end-to-end data engineering project**, where I designed and implemented a complete **ETL pipeline** — starting from an on-premises SQL Server database, migrating through the Azure cloud ecosystem, and culminating in an interactive **Power BI dashboard**.

---

## 🌟 Project Objectives

✅ **Understand data engineering fundamentals** and pipeline development  
✅ **Gain hands-on experience** with Microsoft Azure services  
✅ **Deliver a functional, production-style project** for GitHub, my portfolio, and my resume  

---

## 📊 Dataset

- **AdventureWorksLT2022** — Microsoft’s lightweight sample dataset  
- Includes sample tables like customers, sales orders, products, and more

---

## 🔗 Project Workflow

### 🏠 On-Premises SQL Server

- Set up **SQL Server Express** to host the local AdventureWorksLT2022 database
- Installed **SQL Server Management Studio (SSMS)** for database management
- Configured **Java Runtime Environment (JRE)** to support Parquet file formats

---

### 🌐 GitHub & Version Control

- Created a **dedicated GitHub repository** to track project progress
- Integrated **Git** with:
  - Azure Data Factory (ADF)
  - Azure Databricks
  - Azure Synapse Analytics
- Enabled **branching & version control** for all pipeline components

---

### ☁️ Microsoft Azure Cloud

| **Component**                  | **Role**                                                                                       |
|--------------------------------|------------------------------------------------------------------------------------------------|
| **Azure Resource Group**        | Centralized management of all project resources                                                |
| **Azure Data Lake Storage Gen2**| Configured containers for Bronze, Silver, Gold data layers                                      |
| **Azure Key Vault**             | Secured credentials for on-premises SQL access                                                 |
| **Azure Data Factory (ADF)**    | Built ETL pipelines for extraction, triggering Databricks notebooks, managing linked services  |
| **Azure Databricks**            | Developed **PySpark notebooks** for data transformation (Bronze ➔ Silver ➔ Gold)              |
| **Azure Synapse Analytics**     | Created stored procedures to load final Gold data into Serverless SQL Database                 |
| **Azure Entra ID (Azure AD)**   | Implemented access control and data governance using security groups                          |

---

### 📈 Power BI Dashboard

- Connected **Power BI Desktop** to the Gold layer data in Azure Synapse Analytics  
- Verified and modeled **table relationships**  
- Created **visualizations**:
  - Customer count
  - Sales volume
  - Total revenue
- Added **interactive slicers**:
  - Filter by state/province  
  - Filter by product category

---

## 🏗️ Architecture Overview

![Architecture Diagram](images/azure_data_engineering_architecture.png)  

---

## 💡 Key Highlights

✨ **Cloud-first architecture leveraging best practices**  
✨ **Secure credential management using Azure Key Vault**  
✨ **Automated ETL with ADF + Databricks**  
✨ **Modular data transformation using Bronze, Silver, Gold layers**  
✨ **Powerful reporting & analytics via Power BI**

---

## 🔧 Technologies Used

- **SQL Server Express, SSMS** (on-premises database)
- **Azure Data Lake Storage Gen2**
- **Azure Key Vault**
- **Azure Data Factory (ADF)**
- **Azure Databricks (PySpark)**
- **Azure Synapse Analytics**
- **Azure Entra ID (formerly Azure AD)**
- **Power BI Desktop**
- **GitHub**

---

## 📚 How to Explore This Project

1. **Check out the repo** — explore the notebooks, pipeline definitions, and scripts.
2. **Review the architecture diagram** — understand how the components fit together.
3. **Open the Pow**
