# 🚲 NYC Citi Bike Project

**ORIE 5530 · Modeling Under Uncertainty** (Cornell Tech, Fall 2026)

Analysis of NYC Citi Bike trip data for August 2026: data cleaning, ride-duration distributions, and conditional probabilities by rider and bike type.

## Setup

1. Clone this repo.
2. Get `202608-citibike-tripdata.zip` from a teammate, or from [Citi Bike's public trip data](https://s3.amazonaws.com/tripdata/index.html).
3. Unzip it into the repo folder so you have:
   ```
   citibike-project/
   ├── Modeling Under Uncertainty Project.ipynb
   └── 202608-citibike-tripdata/
       ├── 202608-citibike-tripdata_1.csv
       ├── ...
       └── 202608-citibike-tripdata_6.csv
   ```
4. Open `Modeling Under Uncertainty Project.ipynb` and **Run All**.

> **Note:** The data isn't in the repo. It's ~1 GB, and GitHub rejects files over 100 MB. `.gitignore` keeps it out.

## Requirements

Python 3 with `pandas`, `numpy`, and `matplotlib`:

```bash
pip install pandas numpy matplotlib
```
