# SWYNEX-Data-Cleaning-and-Basic-Analysis

## Overview
This repository contains the deliverables for **Task 2: Data Cleaning and Basic Analysis** of the Bioinformatics Internship at **SWYNEX Technologies**. 

The goal of this task is to perform basic exploratory data analysis (EDA), inspect data types, handle missing values, and summarize a selected biological dataset using Python and Google Colab.

---

## Dataset Information
- **Dataset Source:** UniProtKB
- **Accession ID:** `P01308`
- **Protein Name:** Insulin (Homo sapiens)
- **File Processed:** `uniprotkb_accession_P01308_2026_10_19.xlsx.gz`

---

## Files Included in this Repository
1. `SWYNEX_Data_Cleaning_Analysis.ipynb` (or your downloaded notebook file): The complete Google Colab notebook containing the Python code for data loading, decompression, cleaning, and statistical summary.
2. `cleaned_uniprot_P01308.csv`: The exported clean tabular dataset containing structured attributes.

---

## Summary of Data Cleaning & Analysis Steps
1. **Data Loading & Decompression:** Successfully loaded and decompressed the gzipped Excel export using Python's `gzip` and `pandas` libraries with `openpyxl`.
2. **Structural Inspection:** Verified the dataframe shape (1 row, 7 columns) and confirmed all data types (`Entry`, `Reviewed`, `Entry Name`, `Protein names`, `Gene Names`, `Organism`, and `Length`).
3. **Missing Value Check:** Inspected missing values across all columns and verified **0 missing values**, confirming a high-quality dataset.
4. **Basic Statistics:** Analyzed numerical attributes, confirming the protein length of the Insulin sequence to be **110 amino acids**.
5. **Export:** Cleaned and exported the final structured output into a CSV format for subsequent visualization tasks.

---

## Author
* **Name:** Harshitha Ghantasala
* **Intern ID:** `SWX-2026-002467`
* **Domain:** Bioinformatics Internship
