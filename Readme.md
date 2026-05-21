
## Project Overview

This project simulates a **real-world Corporate Action Processing & Reconciliation System** used by global custodian banks like **Deutsche Bank**.

It demonstrates end-to-end processing from event capture to settlement reconciliation — a core function in Securities Services.

## Key Features

- Corporate Action event capture (Dividend & Stock Split) with full lifecycle d<img width="2384" height="1475" alt="ca_dashboard" src="https://github.com/user-attachments/assets/83aaea9e-1699-452b-aa34-03df961f936a" />
ates
- Cash flow projection with holdings, FX conversion & withholding tax
- Settlement reconciliation engine with exception/break detection
- Event study analysis (price impact after corporate actions)
- Professional formatted multi-sheet Excel operations report
- Analytics dashboard with visualizations

## Business Value

- Strong demonstration of **Corporate Action Operations** knowledge
- Reconciliation & exception management skills
- Quantitative + Operational combined approach
- Ready-to-use Excel output for ops/compliance teams

## Tech Stack

- **Python** • yfinance • Pandas • NumPy
- Matplotlib • Seaborn • Openpyxl
- Simulated operational workflows

## How to Run

```bash


# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook CorpAct_Deutsche_Bank_Portfolio.ipynb
