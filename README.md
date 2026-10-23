# sales-analytics-google-sheets
Data cleaning and sales analytics in Google Sheets: importing data from CSV, GitHub, Google Sheets and Wikipedia (IMPORTHTML), standardizing it, joining tables with VLOOKUP and building a profit dashboard.
# Customer & Transaction Data Cleaning and Enrichment in Google Sheets

## Project Overview

This project is a recreation of a Google Sheets data analysis tutorial by **Nikita Tymoshenko** from the [ION LAB YouTube channel](https://www.youtube.com/@ion_lab).

The project follows the workflow demonstrated in the tutorial [Google Sheets Data Analysis](https://www.youtube.com/watch?v=gYjQRW6N6Ws), using datasets provided in the original learning materials. In addition to recreating the tutorial, I performed further data cleaning, standardization, and enrichment to improve data quality and prepare the datasets for analysis.

## Data Sources

The workbook contains five datasets: `NewCustomerList`, `Address`, `Customers`, `Transactions`, and `AU_States`. The data covers customer demographics, occupations, geographic information, and transaction records.

Data was imported from multiple sources, including websites, Google Sheets, Google Docs, and Wikipedia.

## My Data Preparation Work

- Removed duplicate records and standardized missing values.
- Standardized geographic information, including Australian regions.
- Split combined industry and job title information into separate columns.
- Standardized date formatting and removed default placeholder values.
- Added a calculated `Profit` column to the `Transactions` dataset.
- Used `VLOOKUP` to enrich transaction records with customer industry and job title information.
- Calculated customer age and used an average age of 49 as a fallback for missing or anomalous age values.
- Retained the `AU_States` reference table without additional cleaning because no corrections were needed.

## Tools and Techniques

Google Sheets, data cleaning, data standardization, duplicate removal, `VLOOKUP`, date formatting, calculated columns, and data enrichment.

## Learning Resources and Attribution

- **Creator:** Nikita Tymoshenko
- **YouTube channel:** [ION LAB](https://www.youtube.com/@ion_lab)
- **Tutorial followed:** [Watch the original video](https://www.youtube.com/watch?v=gYjQRW6N6Ws)
- **Original datasets:** [MEGA shared folder](https://mega.nz/folder/B5ZwzSpJ#RePKaGTUzUEQS1ztS-l-Og)

This project was created for learning and practice purposes by following the original tutorial. The additional data-cleaning, standardization, and enrichment steps described above were performed as part of my own work.
