# PDS CA1 – Analysis of Dwelling Types in Singapore

## Overview
This project explores the various factors that affect dwelling types in Singapore using multiple public datasets from data.gov.sg. The analysis focuses on how dwelling type changes over time and how it is influenced by factors such as age, gender, household size, and planning area.

The project was completed as part of **PDS CA1** and uses Python-based data analysis and visualization to identify patterns in housing composition and resident demographics.

---

## Project Objective
The main objective of this project is to answer the following question:

**What are the various factors affecting the type of dwelling, and how do they affect dwelling type over time?**

---

## Datasets Used
This project uses 6 datasets from **data.gov.sg**, related to:
- Type of dwelling
- Resident age by flat type
- Household size
- Gender-related housing patterns
- Planning area housing composition
- Landed property households

---

## Key Features
- Data cleaning and filtering using Python
- Comparison of dwelling types across different years
- Analysis of resident age by flat type
- Comparison of household sizes across flat categories
- Planning area comparison for housing composition
- Identification of areas with the most landed property households
- Data visualization using line charts, pie charts, and summary outputs

---

## Tools & Technologies
- **Python**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## Key Findings
- **HDB 4-Room flats** were found to be the most common dwelling type.
- **Others** was the least common dwelling category.
- Smaller flats such as **1-room** tend to be occupied by older residents.
- Larger flats such as **4-room, 5-room, and Executive flats** tend to have younger residents or families.
- Housing composition differs greatly by planning area.
- **Bedok** showed a more balanced housing mix and had a noticeably higher landed property share compared to places like **Jurong East** and **Outram**.
- Over time, some flat types showed increasing occupancy trends, while others declined.

---

## Example Insights
### 1. Dwelling Popularity
The project shows that 4-room flats remain the most popular housing type overall.

### 2. Age vs Flat Type
Resident age varies clearly by flat type:
- Smaller flats → generally older residents
- Larger flats → generally younger families

### 3. Planning Area Comparison
A focused comparison between **Bedok**, **Jurong East**, and **Outram** shows that each area has a different housing structure:
- **Bedok** includes a more mixed distribution with some landed housing
- **Jurong East** is dominated by mid-to-large HDB flats
- **Outram** has a higher share of smaller HDB units

---

## How to Run
1. Open the Jupyter Notebook version of this project.
2. Install the required Python libraries:
   ```bash
   pip install numpy matplotlib
