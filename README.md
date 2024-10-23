# data_to_elasticsearch
### People Data Processing and Elasticsearch Indexing

## Overview
This project performs data cleaning, analysis, and indexing on a large dataset of people's information (500,000 rows). It reads a CSV file, cleans the data, performs some basic analysis, and then indexes the cleaned data into Elasticsearch for further use.

## Features
- **Data Cleaning**: Removes rows with missing values and fills empty phone numbers with "null".
- **Data Analysis**:
  - Counts unique birth dates, jobs, and genders.
  - Identifies people with the same name or birth date.
- **CSV Export**: Saves the cleaned data to a new CSV file.
- **Elasticsearch Indexing**: Uploads the cleaned data to an Elasticsearch instance, making it searchable and usable for advanced queries.

## Requirements
- Python 3.x
- Pandas
- Matplotlib (used but no visualization is shown in the current version)
- Elasticsearch

## How to Run
1. Install the required packages:
   ```bash
   pip install pandas matplotlib elasticsearch
