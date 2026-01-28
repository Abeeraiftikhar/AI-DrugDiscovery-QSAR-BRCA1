# AI-DrugDiscovery-QSAR-BRCA1
A QSAR data curation project using ChEMBL API for BRCA1 target, focusing on IC50 retrieval, cleaning, and standardization for AI-based drug discovery.

## 📖 Overview

This project demonstrates the complete workflow for retrieving, evaluating, and curating bioactivity data from the ChEMBL database for Quantitative Structure–Activity Relationship (QSAR) modeling. The study focuses on the BRCA1 protein, which is clinically significant in breast and ovarian cancer.
Due to limited availability of bioactivity data, this project serves as a proof-of-concept for QSAR data preparation in AI-driven drug discovery.

## 🎯 Objectives

Retrieve BRCA1 bioactivity data from ChEMBL
Filter IC50 measurements
Clean and standardize datasets
Remove invalid and duplicate entries
Prepare a curated dataset for QSAR modeling

## 🔬 Methodology

Target selection (BRCA1)
Data retrieval using ChEMBL API
Data quality assessment
IC50 filtering
Unit standardization (to nM)
Duplicate removal
CSV export

## ⚙️ Tools & Technologies

Python
ChEMBL Web API
Pandas
Requests
Jupyter Notebook

## 📊 Workflow

Target Selection → Data Retrieval → Evaluation → Cleaning → Standardization → Final Dataset

## 📁 Dataset

The curated dataset contains standardized IC50 values related to BRCA1 and is stored in CSV format for further modeling.

## 📌 Limitations

Limited number of bioactivity records
Insufficient data for robust QSAR modeling
Mainly for educational and methodological demonstration

## ✅ Conclusion

This project highlights the importance of data availability and preprocessing in QSAR studies. While BRCA1 has limited small-molecule data, the workflow demonstrates best practices for preparing high-quality datasets for AI-based drug discovery.
