# pet-adoption-analysis
Data analysis of factors associated with cat adoption speed using the PetFinder.mydataset.
# Pet Adoption Analysis

## Project Overview

This project analyzes factors associated with the adoption speed of cats using the PetFinder.my Adoption Prediction dataset.

The main objective is to understand which characteristics are associated with faster or slower adoption outcomes.

## Business Question

**Which characteristics are associated with faster adoption of cats?**

## Data

The dataset contains information about pets listed for adoption, including:

- Age
- Gender
- Breed
- Vaccination status
- Sterilization status
- Health
- Adoption speed
- Adoption fee
- Number of photos
- Other pet characteristics

For this analysis, only cats were considered, resulting in **6,861 records**.

## Analysis

The analysis was performed using:

- Google Sheets for data exploration and cleaning
- Tableau Public for data visualization

The analysis focused on:

1. Distribution of adoption speed
2. Age group and adoption speed
3. Sterilization status and adoption speed
4. Vaccination status and adoption speed

## Key Findings

- The dataset contains **6,861 cat adoption records**.
- Adoption speed varies considerably across the different categories.
- Most records correspond to cats aged **0–6 months**.
- The dataset shows an association between sterilization status and adoption speed.
- Vaccination status also shows differences across adoption-speed categories.

These findings describe associations observed in the dataset and should not be interpreted as evidence of causation.

## Dashboard

The interactive Tableau dashboard is available here:

**[View the Tableau Dashboard]((https://public.tableau.com/app/profile/michele.martins/viz/PetAdoptionAnalysis_17891626595020/Dashboard))**

## Tools Used

- Google Sheets
- Tableau Public
- GitHub

## Project Structure

```text
pet-adoption-analysis/
├── data/
│   ├── train.csv
│   ├── BreedLabels.csv
│   ├── ColorLabels.csv
│   └── train - Analysis.csv
└── README.md ```

## Dataset

Source:Petfinder.my Adoption Prediction dataset, available through Kaggle.


## Conclusion

This project demonstrates an exploratory data analysis workflow focused on understanding factors associated with cat adoption speed.

The analysis combines data preparation, categorical analysis, and interactive visualization to communicate patterns in the adoption data.
