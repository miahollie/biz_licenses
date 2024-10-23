# biz_licenses

Analysis of Issued Business Licenses — 1995 to 2024
This repository contains data, a Google Sheets analysis, the basics of conducting the analysis via code and findings that support portions of a non-published article about business trends in New York City post-COVID. 

# Data
This analysis uses one spreadsheet.

The spreadsheet comes from the following source: NYC Department of Consumer and Worker Protection (available via https://opendata.cityofnewyork.us)
Issued_Licenses_YYYYMMDD.csv: Raw data of business licenses issued since 1995. The name of the file will correspond to the date in which it is downloaded.

The spreadsheet contains, among others, the following columns relevant to the analysis:
Business Unique ID — a unique string identifier for each business
Business Category — refers to the conduct of the business, e.g. “locksmith” or “pedicab driver.”
Initial Issuance Date — date the license was first issued
Expiration Date — date in which the license expired 

# Methodology
A document including descriptive code has also been made available.
The Jupyter Notebook in this repo performs the following:
- imports libraries
- retrieves basic information about the dataset
- produces an analysis of the dataset to make it easier to see how many new licenses for new businesses were issued each year in New York City.

Note: Once the output csv file is downloaded to your machine, the rest of the analysis takes place in Excel. 

# Licensing
All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

# Feedback / Questions?
Contact Mia at mia.hollie48@journalism.cuny.edu.
