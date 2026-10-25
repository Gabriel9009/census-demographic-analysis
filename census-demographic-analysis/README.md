# Census Demographic Analysis and Community Investment Proposal

## Overview
An exploratory data analysis project using census-style household and demographic data to investigate population structure, household occupancy, employment, commuting patterns, age distribution, and community needs. The analysis was used to develop evidence-informed recommendations for local investment and town planning.

## Objectives
- Clean inconsistent and missing demographic values.
- Standardize categorical fields and examine data quality.
- Explore age, household size, occupation, unemployment, marital status, and other demographic patterns.
- Visualize findings with Python data-analysis and plotting libraries.
- Translate descriptive findings into a community investment proposal.

## Tools
- Python
- pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook

## Repository structure
- `notebooks/` — analysis workflow
- `plots/` — selected visualizations generated during the analysis
- `reports/` — written investment proposal
- `data/` — instructions for supplying an authorized, anonymized dataset

## How to run
1. Create and activate a Python virtual environment.
2. Install the packages listed in `requirements.txt`.
3. If you are authorized to use the source data, place an anonymized CSV at `data/census.csv`.
4. Open `notebooks/census_demographic_analysis.ipynb` in Jupyter and run the cells.

The notebook expects the CSV to be located at `data/census.csv` relative to the repository root. If necessary, update the file path to match your environment.

## Important data-quality note
Some missing values in the original analysis were inferred using rules based on age, household relationships, and other fields. These are assumptions, not verified facts. Interpret derived categories cautiously and clearly distinguish observed data from imputed values.

## Privacy note
The raw household-level dataset is not included. It may contain household/location fields and sensitive demographic attributes. Do not publish it unless you have confirmed permission, appropriate anonymization, and compliance with the source's terms.

## Suggested next improvement
Add a concise executive summary with verified headline figures, limitations, and recommendations. Validate every numerical claim in the report against the final cleaned dataset before publishing.
