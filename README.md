# Retail Order Data Analysis

This project focuses on analyzing retail order data using SQL queries with a MySQL database. It leverages two Jupyter notebooks to process and analyze order information, providing insights into customer behavior, sales trends, and product performance through targeted queries. This project can be expanded or adapted to any retail dataset for deeper analysis and reporting.



## Project Structure

The project consists of two key Jupyter Notebook files:

1. **`Dataframe_to_MysqlDatabase.ipynb`**  
   This notebook demonstrates how to:
   - Convert a retail order dataset (in CSV or similar formats) into a Pandas DataFrame.
   - Store the DataFrame in a MySQL database.
   - Handle database connections, data insertion, and querying.

2. **`Order_data_analysis_with_python_sql.ipynb`**  
This notebook focuses on:
- Solving SQL queries to analyze retail data.
- Extracting insights related to:
  - Sales trends across different regions.
  - Product category performance.
  - Customer segmentation.
- The results provide a foundation for further analysis and reporting.

## Dataset Information

The dataset used in this project contains retail order information with the following key columns:

| Column Name       | Description                                               |
|-------------------|-----------------------------------------------------------|
| **Order Id**       | Unique identifier for each order.                         |
| **Order Date**     | The date the order was placed.                            |
| **Ship Mode**      | The shipping method used (e.g., Second Class).            |
| **Segment**        | Customer segment (e.g., Consumer, Corporate).             |
| **Country**        | Country of the order (e.g., United States).               |
| **City**           | City of the customer.                                     |
| **State**          | State where the customer resides.                         |
| **Postal Code**    | Postal code of the delivery address.                      |
| **Region**         | Geographical region within the country (e.g., South).     |
| **Category**       | Product category (e.g., Furniture, Technology).           |
| **Sub Category**   | More detailed product classification (e.g., Chairs).      |
| **Product Id**     | Unique identifier for the product.                        |
| **Cost Price**     | The cost price of the product.                            |
| **List Price**     | The list price or selling price of the product.           |
| **Quantity**       | The number of units ordered.                              |
| **Discount Percent**| Percentage discount applied to the order.                |

## Tools & Technologies Used

- **Python**: For data manipulation and analysis.
- **MySQL**: For data storage and querying.
- **Pandas**: For handling the dataset and performing data transformations.
- **SQLAlchemy**: For managing MySQL database connections.
