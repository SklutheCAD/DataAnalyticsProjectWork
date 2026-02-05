# Alberta Wildfire Status & Burn Rate Analysis

This repository contains data, Python analysis, and presentation materials used to examine the development of wildfire status and burn rates in the province of Alberta.  
The project focuses on identifying patterns and trends in wildfire activity using historical data, with outputs designed for both analytical and non-technical review.

---

## Repository Structure

├── CodeFiles/
│ └── Alberta_Wildfire.ipynb
├── Data/
│ ├── FireData_CLEAN.xlsx
│ ├── fp-historical-wildfire-data-2000-*.csv
│ └── fp-historical-wildfire-data-dictionary.xlsx
├── Presentation/
│ └── Milestone2.pdf
└── README.md


---

## Project Overview

This project examines:
- Changes in wildfire status over time
- Trends in wildfire burn rates
- Historical wildfire patterns across Alberta

The analysis was completed in Python using a Jupyter Notebook.  
A cleaned dataset was also created to allow users to easily explore the data in Excel without running code.

---

## Data Description

### Raw Data
- Historical wildfire records provided in the `fp-historical-wildfire-data-2000-*` files
- Original data structure and field definitions are documented in:
  - `fp-historical-wildfire-data-dictionary.xlsx`

### Cleaned Data
- **`FireData_CLEAN.xlsx`**
  - Cleaned and standardized version of the wildfire dataset
  - Created to:
    - Remove inconsistencies
    - Standardize variable formats
    - Enable analysis in Excel if desired
  - Used directly by the Python notebook

---

## How to Run the Analysis

### 1. Download the Repository
- Click **Code → Download ZIP**
- Extract the folder to your local machine
- Keep the folder structure unchanged

---

### 2. Open the Python Notebook

The notebook:
- Loads the cleaned wildfire data
- Performs exploratory analysis
- Examines wildfire status and burn rate trends
- Generates visualizations and summary outputs

---

### 3. Optional: Excel-Based Review

If you prefer not to run Python:
- Open `FireData_CLEAN.xlsx`
- Explore, filter, or visualize the cleaned data directly in Excel

---

## Presentation Deliverable

- **`Milestone2.pdf`**
  - Summarizes the analysis findings
  - Includes key visualizations and interpretations
  - Designed for non-technical stakeholders

---

## Tools Used

- Python
- Jupyter Notebook
- pandas
- matplotlib / seaborn
- Excel (optional, for data inspection)

---

## Project Files

- 📓 [Exploratory Analysis Notebook](Wildfire_EDA.ipynb)
- 📊 [Cleaned Dataset](data/wildfire_clean.csv)
- 📈 [Visual Outputs](outputs/)


## Notes & Limitations

- The analysis relies on the accuracy of the provided historical wildfire datasets
- No assumptions were made beyond basic cleaning and transformation
- Results are exploratory and intended for analytical insight, not operational forecasting


Navigate to the `CodeFiles` folder and open:

