# Netflix Movies & TV Shows — EDA

Exploratory data analysis on the Netflix catalogue of movies and TV shows.

## Dataset
- **File:** [`data/Netflix.xlsx`](data/Netflix.xlsx)
- **Columns:** title, type (Movie / TV Show), director, cast, country, date_added, release_year, rating, duration, listed_in, description.

## What's covered
- Catalogue composition (movies vs TV shows)
- Content distribution by country, rating, and release year
- Growth of additions to the platform over time
- Most common genres and durations

## Run

```bash
pip install -r ../requirements.txt
jupyter notebook notebooks/Netflix.ipynb
```

The notebook reads `../data/Netflix.xlsx` relative to itself, so launch Jupyter from the project root or from the `notebooks/` directory.
