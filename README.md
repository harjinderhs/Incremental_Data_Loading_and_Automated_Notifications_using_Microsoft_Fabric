# 📊 Incremental Data Loading and Automated Notifications using Microsoft Fabric

## 📌 Introduction

In today’s data-driven landscape, organizations rely heavily on timely, accurate, and integrated data pipelines to support analytics and decision-making. This project—**"Incremental Data Loading and Automated Notifications using Microsoft Fabric"**—focuses on building a robust, end-to-end solution that enables seamless ingestion, transformation, and monitoring of data workflows.

Leveraging Microsoft Fabric's capabilities, including Dataflow Gen 1, Fabric Notebooks, and Warehouses, this solution automates data ingestion from on-premises sources, applies structured transformation logic such as SCD Type 1, and triggers real-time email notifications upon successful execution.

---

## 🎯 Problem Statement

Organizations face challenges when it comes to:

- Efficiently ingesting and transforming data from diverse on-premises sources
- Performing incremental data loads
- Ensuring data quality and integrity through transformation pipelines

This project solves these challenges using a structured, scheduled data pipeline built entirely on the Microsoft Fabric platform.

---

## ✅ Project Objectives

This project demonstrates how to:

1. **Ingest data from on-premises environments** into a Fabric Lakehouse using the **On-Prem Gateway**
2. **Utilize the AI Bank Dataset** as the structured source
3. **Implement Dataflow Gen 1** to join tables, remove duplicates, and clean data
4. **Load cleansed data into a Fabric Warehouse**
5. **Apply SCD Type 1 logic** using Fabric Notebooks and save results to separate tables

---

## 🛠️ Technologies Used

- Microsoft Fabric Lakehouse  
- Microsoft Fabric Dataflow Gen 1  
- Microsoft Fabric Warehouse  
- Microsoft Fabric Notebooks  
- On-Prem Gateway  

---

## 🔁 Workflow Overview

1. Connect on-premises CSV data using On-Prem Gateway.
2. Ingest data into **Microsoft Fabric Lakehouse**.
3. Use **Dataflow Gen 1** to transform and clean the data.
4. Store the transformed data in a **Fabric Warehouse**.
5. Use **Fabric Notebooks** to apply **SCD Type 1** logic.
6. Write the updated data back to the Lakehouse or Warehouse.

---

## 🤝 Contributions

I welcome contributions from the community!

If you'd like to contribute:

- 🍴 **Fork** the repository
- 🛠️ **Create a new branch** for your feature or fix
- 📥 **Commit your changes**
- 🚀 **Open a pull request**

You can also:
- 💬 **Raise issues** for bugs or suggestions
- 🌟 **Star the repo** if you find it helpful

Thank you for helping make this project better!
