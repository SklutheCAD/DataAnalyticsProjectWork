# White House Visitor Log Analysis

## Project Overview
This project analyzes publicly available White House visitor log data to examine
patterns in visits and meetings over time. The analysis focuses on identifying
trends in visitation frequency, scheduling patterns, and high-level insights
that can be communicated clearly through reproducible data analysis.

The objective is to demonstrate how large, multi-file administrative datasets
can be cleaned, combined, and analyzed to support analytical insight and
presentation-ready findings.

---

## Tools & Technologies
- Python
- Jupyter Notebook
- pandas
- matplotlib / seaborn

---

## Project Files & Materials

### 📓 Code & Analysis Notebook
Open in GitHub’s notebook viewer (renders outputs and visualizations):

👉 [WhiteHouseLog.ipynb](https://github.com/SklutheCAD/DataAnalyticsProjectWork/blob/main/WhiteHouseLogs/CodeFiles/WhiteHouseLog.ipynb)

---

### 📂 Data Files
Visitor log data is provided in yearly CSV files due to GitHub file size limitations.
All files share the same structure and are combined during analysis.

- 👉 [2021 Visitor Logs](Data/2021_WAVES-ACCESS-RECORDS.csv)
- 👉 [2022 Visitor Logs](Data/2022.02_WAVES-ACCESS-RECORDS.csv)
- 👉 [2023 January Visitor Logs](Data/2023.01_WAVES-ACCESS-RECORDS.csv)
- 👉 [2023 February Visitor Logs](Data/2023.02_WAVES-ACCESS-RECORDS.csv)

---

### 📑 Presentation & Deliverables
- 👉 [POTUS Scheduling Review (PPTX)](Presentation/POTUS%20Scheduling%20Review.pptx)
- 👉 [White House Logs Analysis (PDF)](Presentation/Sam%20Kluthe%20WhiteHouse%20Logs.pdf)

---

## How to Run the Analysis

### 1) Download the Repository
- Click **Code → Download ZIP**
- Extract the folder to your local machine
- Keep the folder structure unchanged

### 2) Review Data Files
- Open the `WhiteHouseLogs/Data/` folder
- Each CSV file represents one year or period of visitor logs
- Do not rename or move files, as the notebook uses relative paths

### 3) Run the Analysis Notebook
- Open a Python or Jupyter Notebook environment
- Navigate to `WhiteHouseLogs/CodeFiles/`
- Open `WhiteHouseLog.ipynb`
- Run the notebook from top to bottom

The notebook performs:
- Year-level file combination
- Data cleaning and validation
- Exploratory and trend analysis
- Generation of summary visualizations

### 4) Review Presentation
- Open the `WhiteHouseLogs/Presentation/` folder
- Compare notebook outputs with findings in the presentation

---

## Notes & Limitations
- Data files are separated by year to comply with GitHub storage limits
- Each row represents a logged visit record, not necessarily a unique meeting
- Results are exploratory and intended for analytical insight rather than policy evaluation

---

## Author
Sam Kluthe
