# Food-Inspection-Data-Engineering-Project
This GitHub repository explores NYC restaurant inspection data through a data analyst's journey, using SQL, Alteryx, and BI tools like Power BI and Tableau to load, model, and visualize data.

# New York City Food Inspections - A Data Analyst Journey

This repository contains a series of projects and tasks associated with the data analysis of New York City restaurant inspection results. The data is sourced from [NYC Open Data](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j), and this project aims to explore various aspects of data handling and visualization using SQL, Alteryx, and BI tools such as Power BI and Tableau.

## Data Source

The data used in this project is the "DOHMH New York City Restaurant Inspection Results," which is publicly available for download:
- Direct link to dataset: [DOHMH Dataset](https://data.cityofnewyork.us/api/odata/v4/43nn-pn8j)

## Project Structure

### Part 1: Data Loading and Profiling
- Download and load data into staging tables (prefixed with `stg_`).
- Perform initial data profiling to understand the dataset's structure and quality.

### Part 2: Dimensional Modeling
- Design a dimensional data model.
- Implement the model in a SQL database using DDL scripts.

### Part 3: Data Integration
- Load data from staging tables into the integration schema based on the dimensional model.
- Ensure data integrity and accuracy during the load process.

### Part 4: Business Intelligence Dashboards
- Develop BI dashboards using Power BI and Tableau to visualize inspection results and identify trends.
- Dashboards cover various analytics, including inspection types, results, violations, and trends over time.

## Usage

To replicate this project:
1. Clone the repository.
2. Download the dataset using the provided link.
3. Set up your SQL database environment.
4. Run the SQL DDL scripts included in the `/sql` directory to create the necessary database schema.
5. Use Alteryx workflows from the `/alteryx` directory to load and transform the data.
6. Open and run the BI dashboard files in Power BI or Tableau, located in the `/dashboards` directory.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
