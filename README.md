# 📦 Data Storage for HTTP Request Pipelines

This repository is a centralized location for storing datasets (JSON, CSV, XML, etc.) that can be used to **simulate real-world data ingestion** scenarios in **data pipelines**. The goal is to mimic how companies extract data from various sources using HTTP requests or cloud connectors.

## 🔍 Purpose

- Act as a **mock data source** for testing and developing ETL/ELT pipelines.
- Enable pipelines to **send HTTP requests** to fetch data just like in a production environment.
- Help in **experimenting with tools** like Airflow, Python, Azure, Databricks, etc.

## ⚙️ Use Cases

- Make HTTP `GET` requests to static files hosted in this repository.
- Use these datasets in **Apache Airflow DAGs**, **Python scripts**, or **cloud data pipelines**.
- Replicate real-world company setups where data is pulled from APIs or remote storage.

## 📁 Structure

The repository contains a `data/` folder that includes various datasets categorized by format or use case. These files are publicly accessible and can be used as external sources in pipeline configurations.

## 🚀 Future Plans

- Add more domain-specific datasets (e.g., e-commerce, finance, healthcare).
- Organize datasets by complexity and purpose.
- Integrate with mock API services for testing full request-response workflows.

## 👨‍💻 Maintainer

Maintained by **Soumyadip Panigrahi**, a data engineer focused on building real-world, production-style data pipelines and automation workflows using modern data tools.

---

Feel free to fork or star the repository if it supports your learning or project needs!
