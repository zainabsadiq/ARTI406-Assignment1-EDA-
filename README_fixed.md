# Sleep Health and Lifestyle Dataset - EDA

## Dataset Description
This cleaned dataset contains information about sleep patterns, lifestyle habits, and health metrics. It is prepared for exploratory data analysis after resolving key formatting and consistency issues.

## Final Dataset Size
- Rows: 132
- Columns: 14

## Features
- Person ID
- Gender
- Age
- Occupation
- Sleep Duration
- Quality of Sleep
- Physical Activity Level
- Stress Level
- BMI Category
- Heart Rate
- Daily Steps
- Sleep Disorder
- Systolic_BP
- Diastolic_BP

## Cleaning Performed
1. Standardized the **BMI Category** values so that any variation such as **Normal Weight** is stored as **Normal**.
2. Kept **Sleep Disorder** as a valid categorical value by preserving **"None"** as text instead of allowing pandas to convert it to missing values.
3. Confirmed blood pressure is stored in two numeric columns: **Systolic_BP** and **Diastolic_BP**.
4. Used the deduplicated cleaned dataset provided for analysis.

## Important Note
The original public version of this dataset often contains **374 rows** and a single **Blood Pressure** text column. This submission uses the already cleaned and deduplicated version with **132 rows** and separate blood pressure columns.

## Category Snapshot
### Sleep Disorder
- None: 73
- Insomnia: 29
- Sleep Apnea: 30

### BMI Category
- Normal: 73
- Overweight: 52
- Obese: 7

## Objective
Analyze relationships between sleep duration, sleep quality, activity, stress, BMI, and sleep disorders.

## EDA Tasks Included in the Notebook
- Data overview
- Missing value check
- Descriptive statistics
- Distribution and count visualizations
- Relationship analysis
- Correlation analysis
