# Data Preprocessing Assignment

## Overview
This assignment demonstrates essential preprocessing steps on a synthetic customer dataset:
- Handling missing values
- Removing duplicates
- Encoding categorical variables
- Scaling numerical features

## Steps Implemented
1. **Data Cleaning**
   - Imputed missing values (`age` → median, `city` → mode).
   - Removed duplicate rows.

2. **Encoding**
   - One‑Hot Encoding applied to `city`.
   - Label Encoding applied to `gender`.

3. **Scaling**
   - Min‑Max Scaling and Standardisation applied to `age` and `annual_income`.

## Tools Used
- Python 3.x
- pandas, numpy
- scikit‑learn
