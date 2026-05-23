# Pollution Apriori Association Rule Mining

This is a beginner-level machine learning project that uses association rule mining to analyze relationships between pollution severity and energy recovery levels.

## Project Overview

The main objective of this project is to find useful patterns between pollution indicators and energy recovery using the Apriori algorithm. The project focuses on discovering association rules that show how different pollution severity levels are related to energy recovery levels.

## Dataset

Dataset used:

`Global_Pollution_Analysis.csv`

The dataset contains environmental and energy-related features such as:

- Air Pollution Index
- Water Pollution Index
- Soil Pollution Index
- Industrial Waste
- Plastic Waste Produced
- CO₂ Emissions
- Renewable Energy Percentage
- Energy Recovered

## Techniques Used

- Data preprocessing
- Percentile-based binning
- Transaction data preparation
- Apriori algorithm
- FP-Growth algorithm
- Association rule generation
- Rule evaluation using support, confidence, and lift

## Workflow

1. Loaded and explored the pollution dataset
2. Created severity categories for pollution indicators
3. Converted selected features into transaction format
4. Applied the Apriori algorithm
5. Applied FP-Growth for comparison
6. Generated association rules
7. Evaluated rules using support, confidence, and lift
8. Visualized frequent itemsets and association rules
9. Prepared final reports and insights

## Evaluation Metrics

The association rules were evaluated using:

- Support
- Confidence
- Lift

These metrics help identify strong and meaningful relationships between pollution severity and energy recovery levels.

## Key Insights

- Association rule mining helps discover hidden relationships in pollution and energy recovery data.
- Pollution severity levels can show useful patterns with energy recovery levels.
- Apriori and FP-Growth are useful for identifying frequent itemsets.
- Support, confidence, and lift help measure the strength and usefulness of generated rules.
- The analysis can support better understanding of pollution control and energy recovery strategies.

## Important Note

This is a beginner-level association rule mining project created for learning purposes. The severity categories were created using percentile-based binning, and the results should be understood as pattern discovery using Apriori rather than a predictive machine learning model.

## Files in this Repository

```text
pollution-apriori-association-rules/
│
├── apriori.ipynb
├── Global_Pollution_Analysis.csv
├── Apriori_Pollution_Report.pdf
├── assign_8_Data_Visualizations_Report.pdf
└── README.md
