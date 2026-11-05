# Crime Data Cleaning

This is a practice project I made using Python and Pandas. The purpose was to take a messy crime incidents dataset and clean it step by step.

## What I worked on

- Checked the dataset and its columns.
- Found missing values and duplicate records.
- Fixed spelling mistakes and inconsistent categories.
- Cleaned age and numeric columns.
- Checked latitude and longitude values.
- Converted incident dates into datetime format.
- Standardized phone number formatting.
- Saved the cleaned data as a CSV file.

## Dataset

| | Rows | Columns |
|---|---:|---:|
| Before cleaning | 5,250 | 33 |
| After cleaning | 5,050 | 35 |

I removed 200 exact duplicate rows. Two extra columns were also added to track missing values in selected numeric columns.

## Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- VS Code

## A note about missing values

I did not fill every missing value. Some information, such as names, IDs, dates and coordinates, cannot be safely guessed. I kept those values missing when there was no reliable source to recover them.

For practice, I used median values for selected numeric columns. These are estimates, not the original missing information.

## Project Files

- `notebooks/` – Jupyter Notebook containing the cleaning work.
- `data/raw/` – Original dataset.
- `processed/` – Cleaned CSV file.
- `report/` – Project reports.

## What I learned

While working on this project, I got practical experience with Pandas, missing values, duplicates, data types, data validation and CSV files.