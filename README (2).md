# Mobile Sales Data Analysis

**Author:** Vahid Hushen  
**Program:** AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026 | BharatCares

## Project description
This Python project analyzes a public mobile-sales dataset. It checks data quality, removes exact duplicate rows, calculates sales value where possible, summarizes units sold, and explores trends by month, brand, mobile model, city, payment method, and customer ratings when those fields exist.

The analysis is descriptive. It does not claim to use machine learning.

## Dataset and source
- Dataset filename: `Mobile Sales Data (2).xlsx`
- Public source repository: https://github.com/DataWithRohit/Mobile-Sales-Dashboard
- Direct dataset file: https://github.com/DataWithRohit/Mobile-Sales-Dashboard/blob/main/Mobile%20Sales%20Data%20(2).xlsx

The notebook tries to download the workbook automatically. If that fails, download the Excel file from the source repository and put it in the same folder as the notebook.

## Technologies
Python 3, Jupyter Notebook, pandas, NumPy, Matplotlib, openpyxl.

## Submission files
- `VahidHushen_MobileSalesAnalysis.ipynb` — code and analysis
- `requirements.txt` — Python dependencies
- `VahidHushen_ProjectReport.docx` — project report
- `README.md` — project instructions and dataset source

## Setup and run
1. Install Python 3.10 or newer.
2. Open a terminal in this project folder.
3. (Optional) Create a virtual environment: `py -m venv .venv`
4. Activate it on Windows PowerShell: `.venv\Scripts\Activate.ps1`
5. Install libraries: `python -m pip install -r requirements.txt`
6. Start Jupyter: `python -m jupyter notebook`
7. Open `VahidHushen_MobileSalesAnalysis.ipynb` and choose **Run All**.
8. If the dataset download fails, download `Mobile Sales Data (2).xlsx` from the source repository and place it next to the notebook.

## Outputs
- Dataset shape, columns, types, missing-value counts and duplicate count
- KPI table with calculated sales and units when the required fields are present
- Monthly sales trend when date and sales fields are present
- Brand, model, city, payment-method and customer-rating analysis where available

## Limitations
The dataset is public and educational, not independently verified company data. Findings depend on the workbook contents and data quality. Review actual notebook outputs before writing specific numeric conclusions.
