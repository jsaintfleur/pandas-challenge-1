# E-commerce Data Analysis with Pandas

## Purpose

The **E-commerce Data Analysis with Pandas** program is designed to provide insights into customer behavior, product sales, and profitability for a fictional e-commerce company. This project uses Python's Pandas library to explore and analyze a large dataset, extracting valuable business information. By examining sales, product categories, and customer patterns, this program demonstrates how data analysis can drive decision-making and strategic planning in a business environment.

As a data enthusiast, I created this program to deepen my skills in analyzing large datasets and solving business problems using Python. My motivation was to simulate a real-world scenario where data-driven insights help businesses understand their customers better and optimize their operations for profitability. The challenge enabled me to apply my knowledge of Pandas, data transformation, and summarization, enhancing my proficiency in practical data analysis.

---

## Overview

The **E-commerce Data Analysis with Pandas** program walks users through the process of exploring, transforming, and analyzing a dataset. The goal is to uncover patterns and trends that can help answer critical business questions, such as:

- Who are the top customers in terms of order quantity?
- Which product categories and subcategories are the most popular?
- How much profit does each product generate?
- What are the total revenues for the top clients?

This program provides a hands-on experience in manipulating data using Pandas, reinforcing key concepts like data exploration, aggregation, and transformation.

---

## Data Dictionary

The dataset includes the following columns:

| Column       | Data Type | Description                                                   |
|--------------|-----------|---------------------------------------------------------------|
| **first**        | `object`  | First name of the client.                                   |
| **last**         | `object`  | Last name of the client.                                    |
| **job**          | `object`  | Job title of the client.                                    |
| **phone**        | `object`  | Phone number of the client (string format).                 |
| **email**        | `object`  | Email address of the client.                                |
| **client_id**    | `int64`   | Unique identifier for the client.                           |
| **order_id**     | `int64`   | Unique identifier for the order.                            |
| **order_date**   | `object`  | The date when the order was placed (`YYYY-MM-DD` format).   |
| **order_week**   | `int64`   | The week number of the year when the order was placed (1-52).|
| **order_year**   | `int64`   | The year when the order was placed (e.g., 2024).            |
| **item_id**      | `object`  | Unique identifier for the item ordered.                     |
| **category**     | `object`  | Category of the item (e.g., decor, consumables, etc.).      |
| **subcategory**  | `object`  | Subcategory of the item (e.g., pens, wall art, etc.).       |
| **unit_price**   | `float64` | Price per unit of the item.                                 |
| **unit_cost**    | `float64` | Cost per unit of the item.                                  |
| **unit_weight**  | `float64` | Weight per unit of the item (in pounds).                    |
| **qty**          | `int64`   | Quantity of items ordered.                                  |
| **line_number**  | `int64`   | Line number within the order (useful for orders with multiple items). |

### Additional Information
- **Row Count**: The dataset consists of **54,639 entries**.
- **Data Types**: The dataset contains `object` (string), `int64` (integer), and `float64` (floating-point) data types.
- **Memory Usage**: Approximately **7.5 MB** of memory is utilized by this dataset.
- **Non-null Count**: All columns have 54,639 non-null entries, indicating no missing values in the dataset.

For more details, refer to the [Data Dictionary file](./Data%20Dictionary/Data%20Dictionary.txt) provided in the `Data Dictionary` folder.

---

## Project Structure

The project is organized into several folders and files:

- **`Data Dictionary/`**: Contains the data dictionary file (`Data Dictionary.txt`) providing detailed descriptions of each field.
- **`LICENSE`**: The license file for the project.
- **`README.md`**: This documentation file.
- **`Starter_Code/`**: Contains the starter code for the challenge.
- **`Resources/`**: Includes the main dataset file (`client_dataset.csv`) and the Jupyter Notebook (`wholesale_data_analysis_starter_code.ipynb`) used for the analysis.

---

## Use Cases

The program is designed to answer the following business questions:

1. **Customer Analysis**: Identify top clients based on the number of orders and total units purchased. This information helps businesses target their most valuable customers with loyalty programs and special offers.
2. **Product Analysis**: Discover which product categories and subcategories are most frequently ordered. This analysis enables businesses to optimize inventory management and marketing efforts.
3. **Profitability Assessment**: Calculate the profit for each line item, allowing the business to evaluate which products generate the most profit and adjust pricing strategies accordingly.
4. **Revenue Tracking**: Summarize the spending patterns of the top clients, providing insights into their contribution to total revenue and aiding in the development of personalized engagement strategies.

---

## Technologies Used

- **Python**: The core programming language used for data analysis.
- **Pandas**: A powerful data manipulation library that provides tools for exploring, transforming, and summarizing data.
- **Git**: Version control to manage code changes.
- **GitHub**: Repository hosting platform for project versioning and collaboration.

---

## Key Features

- **Data Exploration**: The program reads and displays basic statistics, allowing users to get an overview of the dataset.
- **Data Transformation**: Multiple transformations are applied, including calculating subtotals, shipping costs, and total prices, to prepare the data for deeper analysis.
- **Profit Analysis**: The program calculates the profit for each line item, offering insights into the profitability of different products.
- **Customer Insights**: Identifies top customers and provides a summary of their orders, including total spending and units purchased.
- **Functionality**: Includes modular functions to perform tasks like currency conversion and data summarization, ensuring clarity and reusability.

---

## Usage Instructions

### Part 1: Data Exploration
- Open the Jupyter Notebook located in the `Starter_Code` folder: [`wholesale_data_analysis_starter_code.ipynb`](./Resources/wholesale_data_analysis_starter_code.ipynb).
- Import the dataset from the CSV file in the `Resources` folder: [`client_dataset.csv`](./Resources/client_dataset.csv).
- Follow the instructions in the notebook to explore the dataset and answer business questions.

### Part 2: Data Transformation
- Transform the dataset by adding columns for subtotals, shipping prices, and total prices.
- Calculate the profit for each line item and confirm your calculations.

### Part 3: Confirm Calculations
- Verify the accuracy of your results by comparing them with the given receipts for specific orders.

### Part 4: Summarize and Analyze
- Use the transformed dataset to summarize the top clients and their contributions to total revenue and profit.

---

## Conclusion

The **E-commerce Data Analysis with Pandas** program is a comprehensive tool for extracting business insights from data. By focusing on key questions like customer behavior, product popularity, and profitability, the program shows how data analysis can be applied in a business setting to drive strategic decisions. This challenge not only reinforces data manipulation skills but also demonstrates the power of Python and Pandas in business intelligence.
