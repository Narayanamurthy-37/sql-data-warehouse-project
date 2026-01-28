**SQL Data Warehouse Project**

Welcome to my SQL Data Warehouse Project 🚀
This repository showcases an end-to-end data warehousing and analytics solution built using SQL Server, following Medallion Architecture (Bronze, Silver, Gold) and industry best practices.

This project is designed as a portfolio project to demonstrate practical skills in data engineering, data modeling, and analytical SQL, simulating real-world enterprise CRM and ERP systems.

🏗️ Data Architecture

The project follows a Medallion Architecture, where data matures through clearly defined layers:

Bronze Layer
Stores raw data ingested directly from CRM and ERP source systems (CSV files) without transformation. Acts as a system of record.

Silver Layer
Performs data cleansing, standardization, validation, and deduplication to produce trusted and consistent datasets.

Gold Layer
Provides business-ready views modeled using a Star Schema, optimized for analytics and reporting.

📖 Project Overview

This project covers the complete data lifecycle, including:

Designing a modern SQL-based data warehouse

Building ETL pipelines using stored procedures

Cleaning and standardizing raw operational data

Integrating CRM and ERP data into a unified model

Creating fact and dimension views for analytics

Enabling KPI reporting and business insights using SQL

The final Gold layer can be directly consumed by BI tools such as Power BI or Tableau.

🎯 Skills Demonstrated

This project demonstrates hands-on experience in:

SQL Development

Data Warehousing Concepts

Medallion Architecture

ETL & Data Transformation

Data Modeling (Star Schema)

Analytical SQL & Window Functions

Business-Oriented Data Design

📊 Analytics & Reporting

The warehouse supports analysis such as:

Customer behavior and segmentation

Product and category performance

Sales trends over time

Top and bottom performers

KPI and performance metrics

📂 Repository Structure
sql-data-warehouse-project/
│
├── datasets/            # Raw CRM and ERP CSV files
│
├── docs/                # Architecture, data flow, and documentation
│
├── scripts/
│   ├── bronze/          # Raw data ingestion scripts
│   ├── silver/          # Data cleansing and transformation scripts
│   └── gold/            # Star schema and reporting views
│
├── README.md            # Project overview
└── .gitignore
🛠️ Tools & Technologies

SQL Server

SQL Server Management Studio (SSMS)

Git & GitHub


🙏 Acknowledgement

This project is inspired by enterprise data warehousing concepts and learning resources from Data With Baraa.
All SQL logic, transformations, and documentation in this repository are independently implemented for learning and portfolio purposes.

🛡️ License

This project is licensed under the MIT License.
You are free to use, modify, and share this project with proper attribution.
