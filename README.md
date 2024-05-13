# CIS9440 Data Warehousing and Analytics Project

## Description

This project was developed for the CIS9440 Data Warehousing and Analytics course. The course aims to provide students with a comprehensive understanding of database warehousing and analytics systems. The focus areas include data warehouse modeling and architecture, Extract-Transform-Load (ETL) processes, administration, security, and advanced database systems like column-store, streaming, NoSQL databases, and complex event processing. The project involves the creation of a complete data warehouse system and the implementation of a business intelligence suite.

## Data Source

The project utilizes real estate sales data maintained by the Office of Policy and Management, which includes sales from $2,000 and above that occur annually from October 1 to September 30. Detailed information about each property such as town, address, sale date, type, price, and assessment is included. This data is collected under Connecticut General Statutes, sections [10-261a](https://www.cga.ct.gov/current/pub/chap_172.htm#sec_10-261a) and [10-261b](https://www.cga.ct.gov/current/pub/chap_172.htm#sec_10-261b).

- **Data source link**: [Real Estate Sales 2001-2018](https://catalog.data.gov/dataset/real-estate-sales-2001-2018)
- **Metadata and Data Dictionary**:
  - [Metadata details](https://data.ct.gov/Housing-and-Development/Real-Estate-Sales-2001-2021-GL/5mzw-sjtu/about_data)


## Technologies Used

- **Azure Blob Storage**: Used for data storage in containers.
- **Google Colab**: Platform for running Python code and performing data analysis.
- **PostgreSQL on Microsoft Azure**: Hosted database service used for building the data warehouse.
- **DBSchema**: Tool for creating and visualizing database schemas.
- **DataGrip**: Database management platform used for SQL manipulations.



## ETL Process

### Transformation Details

Transformations applied to the data include:
- Standardizing date formats to YYYY-MM-DD.
- Splitting dates into multiple components (Year, Quarter, Month, Day).
- Removing duplicate records and null values.
- Enforcing data types and creating new calculated fields.

### Transformation Scripts

Scripts used for data transformation are stored in the project's GitHub repository and are continuously updated as the project evolves.

## Modeling

Data modeling involves creating a fact table with a surrogate key and several dimension tables. DBSchema is used for this purpose.

- **Data Model Documentation**: Included in the repository, showing the design of fact and dimension tables.

## Data Visualization and Reporting

### Tools Used

- **PowerBI**: is used for the datavisualizarion

### Features

- Interactive dashboards with filtering by date or dimensions.
- Various chart types including pie charts, column charts, line charts, and heat maps.


## Installation and Usage

Please refer to the GitHub repository's main page for detailed instructions on setting up and running the project locally.

## License

This project is released under the MIT License.

## Contact Information

For further information or inquiries, please contact Yuliia Pylypenko (mailto:yuliia.pylypenko20@gmail.com)

