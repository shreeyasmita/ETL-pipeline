# 🚀 Azure Serverless ETL Pipeline

## 📌 Overview
This project demonstrates a serverless ETL (Extract, Transform, Load) pipeline using Azure services.  
The system automatically processes data when a file is uploaded, making it efficient and scalable.

---

## 🧠 What is ETL?

- **Extract** → Read data from source (CSV file)
- **Transform** → Clean and process data
- **Load** → Store processed data in a new container

---

## ⚙️ Architecture

User → Blob Storage (raw-data) → Azure Function → Processed Data (processed-data)

---

## 🚀 Features

- Event-driven processing using Blob Trigger  
- Serverless architecture (no infrastructure management)  
- Automatic data transformation  
- Cloud-native deployment  

---

## 🛠 Tech Stack

- Azure Functions  
- Azure Blob Storage  
- Python  
- GitHub Actions (CI/CD)  

---

## 📊 Output

Processed CSV file stored in `processed-data` container
