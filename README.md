# Bike Buyers Dataset

## Overview

The Bike Buyers Dataset contains information about individuals and their purchasing decisions regarding bicycles. This dataset is suitable for classification analysis, customer segmentation, and predictive modeling to understand factors influencing bike purchase behavior.

## Dataset Structure

The dataset consists of two sheets:

1. **bike_buyers** (Sheet 1): Raw data with 1,000+ records
2. **Working sheet** (Sheet 2): Enhanced version with additional calculated fields

## Columns Description

| Column Name | Description | Data Type | Values |
|-------------|-------------|-----------|---------|
| ID | Unique identifier for each record | Numeric | Sequential numbers |
| Marital Status | Marital status of the individual | Categorical | M (Married), S (Single) |
| Gender | Gender of the individual | Categorical | M (Male), F (Female) |
| Income | Annual income in dollars | Numeric | $10,000 - $170,000 |
| Children | Number of children | Numeric | 0-5 |
| Education | Highest education level | Categorical | Partial High School, High School, Partial College, Bachelors, Graduate Degree |
| Occupation | Employment category | Categorical | Manual, Clerical, Skilled Manual, Professional, Management |
| Home Owner | Home ownership status | Categorical | Yes, No |
| Cars | Number of cars owned | Numeric | 0-4 |
| Commute Distance | Distance to work | Categorical | 0-1 Miles, 1-2 Miles, 2-5 Miles, 5-10 Miles, 10+ Miles |
| Region | Geographic region | Categorical | Europe, Pacific, North America |
| Age | Age of the individual | Numeric | 25-89 years |
| Purchased Bike | Target variable - purchase decision | Categorical | Yes, No |

## Additional Fields (Working Sheet)

The working sheet includes an additional calculated field:
- **Age Bracket**: Categorical age grouping based on the formula:
  - Adolescent: <31 years
  - Middle age: 31-55 years  
  - Old age: >55 years

## Potential Use Cases

1. **Classification Modeling**: Predict bike purchase decisions based on demographic and socioeconomic factors
2. **Customer Segmentation**: Identify key customer profiles for targeted marketing
3. **Feature Importance Analysis**: Determine which factors most influence purchase decisions
4. **Exploratory Data Analysis**: Understand relationships between variables and purchase behavior

## Data Quality Notes

- Contains 1,000+ complete records with no missing values
- Balanced representation across different demographic groups
- Realistic income distribution and age ranges
- Multiple geographic regions represented

## Sample Insights

The dataset shows diverse customer profiles across different income levels, occupations, and age groups, making it suitable for comprehensive analysis of bike purchasing patterns.

## File Format

- **File Name**: bike_buyers Dataset.xlsx
- **Format**: Excel workbook with two
