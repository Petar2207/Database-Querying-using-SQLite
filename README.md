## Overview

This repository contains a set of SQL queries and Python scripts that allow for the analysis of various datasets related to the city of Chicago. The datasets include information about census data, public schools, and crime statistics in Chicago. The project aims to explore and answer questions related to community welfare, crime patterns, and school safety based on this data.

## Datasets

The following datasets are used in this project:

1. **Chicago Census Data**: Contains demographic and socio-economic information about the different community areas in Chicago.
2. **Chicago Public Schools Data**: Contains information about public schools in Chicago, including safety scores.
3. **Chicago Crime Data**: Contains detailed information about reported crimes in Chicago, including the type of crime, description, and community area location.

## Setup

1. **Database Setup**: The Python script will automatically load the data from the CSV files into an SQLite database called `DinalDB.db`. The data will be stored in the following tables:
    - `CENSUS_DATA`
    - `CHICAGO_PUBLIC_SCHOOLS`
    - `CHICAGO_CRIME_DATA`

2. **Running the Queries**: The SQL queries in this project explore a variety of questions such as:
    - The total number of crimes recorded in the crime data.
    - The community areas with a per capita income less than $11,000.
    - All case numbers for crimes involving minors.
    - All kidnapping crimes involving a child.
    - The types of crimes that were recorded at schools.
    - The average safety score for each school type (elementary, middle, or high school).
    - The five community areas with the highest percentage of households below the poverty line.
    - The most crime-prone community area.
    - The community area with the highest hardship index.
    - The community area with the most number of crimes.

## Usage

To use this project:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run the Python script to load the data into the SQLite database and execute SQL queries.
4. Alternatively, if you are using a Jupyter notebook or IPython interface, you can run the SQL queries interactively using the `%sql` magic command.

## Example Queries

Some of the key queries include:

- Total number of crimes recorded in the crime data.
- Community areas with per capita income less than $11,000.
- All kidnapping crimes involving a child.
- The community area with the highest hardship index.

## Contributing

Contributions are welcome! If you have suggestions, bug fixes, or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

