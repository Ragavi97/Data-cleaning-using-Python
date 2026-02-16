# Data-cleaning-using-Python
## Data Cleaning

Data cleaning is the process of detecting, correcting, and standardizing raw data to improve its accuracy, consistency, and usability for analysis.

In this project, customer, employee, and car datasets were cleaned using a reusable, class-based approach to ensure data quality and privacy compliance.

Key Cleaning Steps

Removed duplicate records to eliminate redundancy

Handled missing values using appropriate filling techniques

Masked phone numbers to protect sensitive information

Standardized data formats for consistency

Implementation

All cleaning operations were implemented in a custom DataCleaning class, enabling a modular and reusable pipeline that can be applied across multiple datasets.

Result

The final datasets are clean, consistent, privacy-safe, and ready for analysis or machine learning applications.



data-cleaning-project/
│
├── data/
│   ├── customer.csv
│   ├── employee.csv
│   └── car.csv
│
├── src/
│   └── data_cleaning.py   # DataCleaning class & functions
│
├── cleaned_data/
│   └── (processed datasets)
│
└── README.md

