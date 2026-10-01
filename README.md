# Healthcare Analytics for Doctor Visits

## Project Overview

This project analyzes healthcare data to understand patterns related to doctor visits. It examines factors such as age, gender, income, illness, health condition, reduced activity, chronic conditions, and healthcare support.

The project uses Exploratory Data Analysis (EDA) and data visualization to identify relationships between these factors and the number of doctor visits.

## Dataset

- **Records:** 5,190
- **Columns:** 13
- **Main Focus:** Understanding patterns related to doctor visits
- **Target Variable:** `visits`

### Main Variables

- `gender` – Gender of the person
- `age` – Age of the person
- `income` – Income level
- `illness` – Number of reported illnesses
- `reduced` – Days when normal activities were affected
- `health` – General health indicator
- `private` – Private healthcare/insurance coverage
- `freepoor` – Free healthcare support
- `freerepat` – Repatriation-related healthcare support
- `nchronic` – Chronic health condition
- `lchronic` – Long-term chronic health condition
- `visits` – Number of doctor visits
- `Unnamed: 0` – Record identifier


## Analysis Performed

- Dataset understanding
- Data quality checks
- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Multivariate analysis
- Data visualization
- Key insights and conclusions

## Key Findings

- Doctor visits generally increase as the reported number of illnesses increases.
- Reduced activity shows a moderate positive association with doctor visits.
- Long-term chronic conditions show a noticeable difference in average doctor visits.
- Female records have a higher average number of doctor visits than male records in this dataset.
- Age and health status show weak positive associations with doctor visits.
- Income shows a very weak negative linear association with doctor visits.
- Average doctor visits are very similar between people with and without private healthcare coverage.

These findings describe patterns in the dataset and should not be interpreted as causal relationships.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook


## Conclusion

This project demonstrates how Exploratory Data Analysis and visualization can be used to understand healthcare data and identify patterns associated with doctor visits.
