## UNC Data Analytics Bootcamp Module 12: NoSQL-Databases

### UK Food Analysis: Exploring Restaurant Data in NoSQL Databases

This repository contains materials for Module 12 of the UNC Data Analytics Program, focusing on NoSQL databases. It includes JSON datasets as the source data and Jupyter Notebooks for setup and analysis.

The `Resources` folder contains the JSON file with information on restaurants in the UK.

### Files Included

- **NoSQL_setup_starter.ipynb**: Jupyter Notebook which establishes the connections to the database and does some preliminary cleansing of data.
- **NoSQL_analysis_starter.ipynb**: Jupyter Notebook which conducts various queries on the dataset and converts the results to Pandas DataFrames for further analysis.
- **establishments.json**: Json file with dataset to be imported and analyzed.

## Usage

1. Clone the repository to your local machine.
2. In your terminal, navigate to the `Resources` folder.
3. Run the following command to import the dataset into MongoDB: `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`
4. Execute the code in the NoSQL_setup_starter.ipynb file to load the uk_food database and establishments collection. The file will also clean up and standardize various sets of information.
5. Execute the code in the NoSQL_analysis_starter.ipynb file to run the analysis on the dataset.

## Dependencies

- pandas
- pprint
- pymongo