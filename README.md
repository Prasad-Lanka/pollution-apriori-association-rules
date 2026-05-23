# Pollution Association Rule Mining

This is a beginner-level machine learning project that uses association rule mining to analyze relationships between pollution severity, energy recovery, and environmental factors.

## Project Overview

The main objective of this project is to discover meaningful patterns in pollution data using Apriori and FP-Growth algorithms. The project identifies frequent itemsets and association rules that show how pollution levels, renewable energy, industrial waste, and energy recovery are related.

## Dataset

Dataset used:

`Global_Pollution_Analysis.csv`

The dataset includes environmental and energy-related features such as:

- Air Pollution Index
- Water Pollution Index
- Soil Pollution Index
- Industrial Waste
- Plastic Waste Produced
- CO₂ Emissions
- Renewable Energy Percentage
- Energy Recovered
- Country
- Year

## Techniques Used

- Data preprocessing
- Percentile-based binning
- Transaction data preparation
- Apriori algorithm
- FP-Growth algorithm
- Association rule mining
- Chi-square significance testing
- Train-test validation
- K-Fold cross-validation
- Sensitivity analysis
- Data visualization

## Evaluation Metrics

The generated rules were evaluated using:

- Support
- Confidence
- Lift
- P-value

These metrics help identify strong, meaningful, and statistically significant association rules.

## Key Insights

- Association rule mining helps discover hidden relationships between pollution indicators and energy recovery.
- Apriori and FP-Growth are useful for identifying frequent environmental patterns.
- Lift and confidence help measure the strength of pollution-related rules.
- Chi-square testing helps check whether selected rules are statistically significant.
- Country-level analysis can support better pollution control and energy recovery recommendations.

## Important Note

This is a beginner-level association rule mining project created for learning purposes. The severity categories were created using percentile-based binning, so the results should be understood as pattern discovery rather than a predictive machine learning model.

## Files in this Repository

```text
pollution-association-rule-mining/
│
├── assign9_apriori.ipynb
├── Global_Pollution_Analysis.csv
├── final_report_submission_assign9.pdf
├── data_visualizations_assign9.pdf
└── README.md
