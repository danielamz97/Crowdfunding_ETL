# Project Name

## Overview

This repository contains the code and resources for a crowdfunding database project. The project involves creating and managing data related to categories, subcategories, campaigns, and contacts. The data is structured using DataFrames, exported to CSV files, and stored in a relational database. The database schema is defined in `crowdfunding_db_schema.sql`, and the relevant CSV files are provided in the `resources` folder.

## Project Structure

- `ETL_Mini_Project_Starter_Code_DMontiel_ECervantes_JMontoya.ipynb`: Jupyter Notebook containing the code for extracting, transforming, and loading (ETL) data into DataFrames.
- `crowdfunding_db_schema.sql`: SQL file defining the database schema.
- `resources/`: Folder containing the necessary CSV files for categories, subcategories, campaigns, and contacts.
  - `campaign.csv`
  - `category.csv`
  - `contacts.csv`
  - `subcategory.csv`
- `ERD CrowdFunding_DB.png`: Entity-Relationship Diagram illustrating the structure of the crowdfunding database.
- `ERD code.txt`: Text file containing the code representation of the Entity-Relationship Diagram.

## Data Processing

The project involves the following data processing steps:

### Category DataFrame

- Created a Category DataFrame with "category_id" and "category" columns.
- Exported the Category DataFrame to `category.csv`.

### Subcategory DataFrame

- Created a Subcategory DataFrame with "subcategory_id" and "subcategory" columns.
- Exported the Subcategory DataFrame to `subcategory.csv`.

### Campaign DataFrame

- Created a Campaign DataFrame with columns including "cf_id," "contact_id," "company_name," "description," "goal," "pledged," "outcome," "backers_count," "country," "currency," "launch_date," "end_date," "category_id," and "subcategory_id."
- Exported the Campaign DataFrame to `campaign.csv`.

### Contacts DataFrame

- Created a Contacts DataFrame with "contact_id," "first_name," "last_name," and "email" columns.
- Exported the Contacts DataFrame to `contacts.csv`.

### Crowdfunding Database

- Defined a database schema in `crowdfunding_db_schema.sql`.
- Created a database, `crowdfunding_db`, using the schema.
- Ensured appropriate primary and foreign keys and relationships.

## Usage

1. **Database Setup**: Execute the SQL commands in `crowdfunding_db_schema.sql` to set up the database schema.

2. **Data Import**: Import the CSV files into their respective tables using the appropriate database tools or commands.

3. **View Data**: Execute `SELECT *` statements to view the data in each table.

## Entity-Relationship Diagram

![ERD CrowdFunding_DB](ERD%20CrowdFunding_DB.png)

For a detailed code representation, refer to `ERD code.txt`.

## Resources

- Initial datasets: `crowdfunding.xlsx` and `contacts.xlsx` in the `resources` folder.

## Contributors

- Jessica Montoya
- Esaú Cervantes
- Daniela Montiel
