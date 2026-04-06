# 🚀 Azure Serverless ETL Pipeline

## 📌 Overview

This project demonstrates a **serverless ETL (Extract, Transform, Load) pipeline** built using Microsoft Azure.
The system automatically processes data when a file is uploaded, making it scalable, efficient, and fully automated.

---

## 🧠 What is ETL?

ETL stands for:

* **Extract** → Read data from source (CSV file)
* **Transform** → Clean and modify data
* **Load** → Store processed data in a new location

---

## ⚙️ Architecture

Raw Data → Azure Blob Storage → Azure Function (Python) → Processed Data

---

## 🛠️ Technologies Used

* ☁️ Microsoft Azure
* 📦 Azure Blob Storage
* ⚡ Azure Functions (Python)
* 🐍 Python
* 🐧 Azure Cloud Shell
* 🔧 Azure CLI

---

## 📂 Project Structure

```
myfunctionapp/
│
├── processcsv/
│   ├── __init__.py        # Main function code
│   └── function.json      # Trigger configuration
│
├── requirements.txt       # Dependencies
├── host.json              # Function settings
```

---

## 🚀 How It Works

1. Upload a CSV file to the **raw-data** container
2. Azure Function is automatically triggered
3. Python script processes the file
4. Output is stored in **processed-data** container

---

## 📄 Sample Input

```
id,name,amount
1,A,100
2,B,200
3,A,100
```

---

## 🔥 Key Features

* ✅ Event-driven architecture
* ✅ Serverless (no infrastructure management)
* ✅ Automatic scaling
* ✅ Real-time data processing
* ✅ Cost-efficient solution

---

## 🧪 How to Run

1. Create Azure Storage Account
2. Create containers:

   * raw-data
   * processed-data
3. Deploy Azure Function
4. Upload CSV file
5. Check processed output

---

## 🎯 Use Cases

* Data preprocessing pipelines
* Log processing systems
* Real-time data ingestion
* Analytics data preparation

---

## 📈 Future Enhancements

* Add data transformation using Pandas
* Integrate Azure Synapse Analytics
* Connect Power BI for visualization
* Add CI/CD pipeline

---

## 💡 Learnings

* Hands-on experience with Azure serverless architecture
* Understanding of event-driven systems
* Practical implementation of ETL pipeline

---

## 🧑‍💻 Author

**Shreeyasmita**
Cloud & DevOps Enthusiast 🚀

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share!

---
