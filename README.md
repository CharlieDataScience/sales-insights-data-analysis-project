# Sales Analysis Project: Power BI Dashboard

![image](https://github.com/user-attachments/assets/5aa5496d-c4a2-403b-8a9d-fb3ca812776a)

## Project Description

This project aims to analyze a company's sales over several years using an interactive dashboard in Power BI. The analysis includes key information on revenue, sales quantity, top markets, best-selling products, and major customers. Through this dashboard, valuable insights can be obtained to support strategic decision-making.

## Dataset

### Data Description

The dataset used in this project consists of several related tables, which are described below:

- **Transactions**: Contains information about sales transactions, including customer, market, and product codes, as well as the sales quantity and normalized sales amount.
- **Customers**: Provides details about customers, such as their names and types.
- **Markets**: Includes information on the markets where the company operates, with details such as the market name and zone.
- **Products**: Contains data on the products sold, including product codes and types.
- **Date**: A date table used to segment and analyze sales over time.

### Data Model

The data model follows a star schema, where the central **Transactions** table is related to the **Customers**, **Markets**, **Products**, and **Date** tables. This allows for comprehensive sales analysis from different perspectives.

### Database
SQLite was used as the database to store and manage the datasets. The lightweight nature of SQLite made it ideal for handling the structured data used in this project, enabling efficient querying and data management.

## Analysis and Results

The dashboard provides answers to the following key questions:

1. **Which is the most profitable market?**
    
    - **Delhi NCR** stands out as the market with the highest revenue, totaling 6.23 million, followed by **Mumbai** and **Ahmedabad**.
2. **What is the revenue trend over time?**
    
    - The trend shows fluctuations, with significant peaks in mid-2018 and early 2019, followed by a decline in revenue towards 2020.
3. **What are the best-selling products?**
    
    - The product318 generates the most revenue, with 827.61 thousands of dollars, followed by **Prod316** and **Prod324**.
4. **Who are the top customers?**
    
    - **Electricalsara Stores** is the customer generating the most revenue, with a total of 4960.00 million.
5. **How are sales quantities distributed across markets?**
    
    - **Delhi NCR** also leads in sales quantity, followed by **Mumbai** and **Nagpur**.

## Tools Used

- **Power BI**: Used for creating the interactive dashboard and data visualization.
- **Excel/CSV**: For initial data manipulation and cleaning.
- **Power Query**: For data transformation within Power BI.
- **SQLite**: Used for storing and managing the data, enabling efficient querying and data manipulation.

## How to Run the Project

1. **Clone the Repository**: `git clone https://github.com/CharlieDataScience/sales-insights-data-analysis-project.git`
2. **Load Data into SQLite**: Ensure that the datasets are correctly loaded into an SQLite database.
3. **Open the Dashboard in Power BI**: Open the `.pbix` file in Power BI Desktop to explore the dashboard.
4. **Interact with the Dashboard**: Use filters and visualizations to analyze the data based on different criteria.

## Conclusions

This analysis allows the company to identify key markets, high-performing products, and strategic customers. The revenue trend suggests a need to investigate the cause of fluctuations and develop strategies to stabilize and increase revenue in the future.

## Next Steps

- **Product Optimization**: Investigate the most profitable products and their impact on different markets.
- **Predictive Analysis**: Implement machine learning models to predict future sales.
- **Dashboard Expansion**: Include additional analyses such as customer segmentation and marketing campaign performance evaluation.

## Contact

If you have any questions or suggestions about the project, feel free to contact Carlos Bermúdez Solis at charliedatascience@gmail.com.
