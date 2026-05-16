# Students Performance — EDA

Exploratory data analysis on student exam results.

## Dataset
- **File:** [`data/Students_performance.csv`](data/Students_performance.csv)
- **Rows:** 1,000 students
- **Columns:** gender, race/ethnicity, parental level of education, lunch, test preparation course, math score, reading score, writing score.

## What's covered
- Score distributions across math, reading, and writing
- Effect of gender, parental education, lunch type, and test prep on scores
- Correlations between the three subject scores
- Group-level performance breakdowns

## Run

```bash
pip install -r ../requirements.txt
jupyter notebook notebooks/Students_performance.ipynb
```

The notebook reads `../data/Students_performance.csv` relative to itself.
