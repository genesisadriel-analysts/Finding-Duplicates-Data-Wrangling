## 📊 Finding Duplicates – Data Wrangling Project
## 📌 Overview

This project demonstrates a structured approach to data wrangling by identifying, analyzing, and removing duplicate entries in a survey dataset using Python.

The workflow focuses on distinguishing true duplicate records from shared response patterns, ensuring that only unintended duplicates are removed while preserving valid survey responses. It highlights best practices in maintaining data integrity during cleaning processes.

## 🎯 Key Objectives

Duplicate Identification: Detect exact row duplicates using pandas functions.

Pattern Analysis: Differentiate between true duplicates and common response patterns across non-unique columns.

Strategic Cleaning: Apply full-row comparison to safely remove only identical records.

Verification: Validate results to ensure data accuracy after cleaning.

## 🛠️ Tech Stack & Skills

Language: Python
Libraries:
 * pandas (Data Manipulation & Cleaning)
 * matplotlib (Data Visualization)
Environment: Jupyter Notebook

## 🚀 Execution Guide
1. Environment Setup

Clone the repository and install dependencies:
    
    git clone https://github.com/yourusername/duplicate-data-wrangling.git
    cd duplicate-data-wrangling
    pip install pandas matplotlib

2. Run the Analysis

  Launch Jupyter Notebook and open the project file:
  
     jupyter notebook

Open: Finding Duplicates-Data Wrangling.ipynb

## 🧠 Project Insights & Skills Learned
  * Data Integrity Awareness: Learned to avoid removing valid data by relying on full-row duplication instead of partial column matching.
  * Analytical Thinking: Differentiated between duplicate records and shared real-world patterns.
  * Data Cleaning Techniques: Applied pandas functions like duplicated() and drop_duplicates() effectively.
  * Validation Practices: Ensured accuracy by verifying dataset shape and duplicate counts post-cleaning.

## 🔮 Future Roadmap
  * Advanced Filtering: Introduce conditional duplicate detection using subsets with caution.
  * Enhanced Visualization: Expand charts to analyze duplicate distribution across more variables.
  * Pipeline Automation: Convert the notebook into a reusable data cleaning script.

## 📩 Contact
Genesis Adriel Segovia
📧 genesisadriel.segovia@outlook.com
