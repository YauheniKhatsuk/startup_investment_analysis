# Startup Investment & Acquisition Analysis

## Project Overview

This project explores startup funding and acquisition patterns to identify strategic investment opportunities. 

The objective was to analyze funding behavior, acquisition prices, and company lifecycle characteristics to support decision-making for venture investments and startup acquisitions.

---

## Business Goal

To identify:
- Typical funding ranges
- Market segments with high acquisition prices
- Relationship between funding rounds and acquisition probability
- Outlier behavior in startup financing

---

## Data Used

- acquisition.csv
- company_and_rounds.csv
- people.csv
- education.csv
- degrees.csv

The dataset contains information about:
- Startup funding rounds
- Acquisition deals
- Company status
- Employee education data

---

## Key Analysis Performed

### 1. Data Preprocessing
- Cleaned column names
- Converted date columns
- Handled missing values
- Split merged dataset into structured company & rounds tables

### 2. Funding Distribution Analysis
- Identified highly skewed funding distribution
- Used median instead of mean
- Calculated IQR-based outlier thresholds

### 3. Startups Acquired for $0 or $1
- Identified symbolic acquisitions
- Investigated funding before acquisition
- Explained repeated acquisition records

### 4. Startup Categories by Acquisition Price
- Ranked categories by median acquisition price
- Calculated price variability (IQR)
- Identified high-risk / high-reward segments

### 5. Funding Rounds by Company Status
- Found that most acquired startups had 0–2 rounds
- IPO companies had higher average funding rounds
- Late-stage acquisitions are rare

---

## Key Findings

- Typical startup funding range: $0.1M – $14M
- Funding distribution is heavily right-skewed
- Many acquisitions happen at early stages
- High acquisition value categories:
  - Real Estate
  - Manufacturing
  - Biotech
  - Finance
  - Security
- Large funding outliers distort averages — median is preferred

---

## Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- SciPy

---

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
