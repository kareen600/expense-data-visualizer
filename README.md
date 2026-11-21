# Expense Data Visualizer

A simple and interactive web app to track, categorize, and visualize personal expenses and payments from bank statement CSV files.

## What This App Does
- **Upload Bank Statements:** Upload a CSV file containing transactions (`Date`, `Details`, `Amount`, `Debit/Credit`).
- **Auto-Categorization:** Automatically assigns categories to transactions based on saved keywords in `categories.json`.
- **Interactive Editing:** Add new categories, update transaction categories in a table, and save new merchant keywords automatically.
- **Visual Summary:** View total expenses by category in a summary table and an interactive pie chart, plus total incoming payments.

## Built With
- **Python**
- **Streamlit** (Web Interface)
- **Pandas** (Data Cleaning & Processing)
- **Plotly** (Interactive Charts)

## How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kareen600/expense-data-visualizer.git
   cd expense-data-visualizer
2. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
3. **Run the application:**
   ```bash
   streamlit run main.py

## Project Files
- `main.py` — Main application code.
- `categories.json` — Saved categories and merchant keywords.
- `requirements.txt` — List of Python libraries needed to run the app.
- `sample_bank_statement.csv` — Sample CSV file to test the app.

   
