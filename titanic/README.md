# Titanic Survival — EDA

Exploratory data analysis on the classic Titanic passenger dataset.

## Objective
Understand the relationship between passenger attributes (gender, age, class, embarkation port, etc.) and survival rate.

## Dataset
- **Source:** loaded from `seaborn.load_dataset("titanic")` inside the notebook.
- **Snapshot:** a copy is saved alongside as [`data/titanic.xlsx`](data/titanic.xlsx) for offline reference.

## What's covered
- Univariate analysis of passenger attributes
- Bivariate analysis vs. survival (sex, class, age, fare, embarkation)
- Missing-value handling
- Key insights on which passenger groups had higher survival rates

## Run

```bash
pip install -r ../requirements.txt
jupyter notebook notebooks/titanic.ipynb
```

No external data file is required — seaborn fetches the dataset at runtime.
