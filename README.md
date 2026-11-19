# Company-Rating-Analysis-


# Companies Ratings Analysis

Suggested repository name: `companies-ratings-analysis`

This project uses Python, Pandas, and Matplotlib to explore company ratings, company types, and headquarters locations. It does **not** analyze sales or revenue because the source data has no sales or revenue fields.

## Files

- `companies_data.csv` — source dataset.
- `companies_sales_analysis.ipynb` — notebook for data inspection, cleaning, analysis, and visualizations. The notebook filename is retained, but its analysis is about company ratings.

## Run the notebook

Install the required packages:

```bash
python -m pip install pandas matplotlib jupyter
```

Start Jupyter from this project directory so the notebook can find `companies_data.csv`:

```bash
jupyter notebook
```

Open `companies_sales_analysis.ipynb` and run the cells in order.

## Data notes

- The source CSV contains many repeated company records. The notebook removes exact duplicate records, leaving 30 company records for analysis.
- A malformed Concentrix row is corrected in the notebook before deduplication.
- The `reviews` column is entirely empty and is removed during cleaning.
- Findings describe this dataset only and should not be treated as representative of all companies.
