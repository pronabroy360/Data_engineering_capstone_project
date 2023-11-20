# Capstone Project - Sales Stock Forecasting
## Overview

This comprehensive capstone project encompasses the design and implementation of an end-to-end data platform for an e-commerce company. The project is structured into distinct modules, each contributing to the development and enhancement of the company's data infrastructure and analytical capabilities.

## Modules

1. **OLTP Data Storage with MySQL**
   - Design and implementation of a data platform using MySQL as the OLTP database for efficient transactional data storage.

2. **NoSQL Catalog Data with MongoDB**
   - Integration of MongoDB as a NoSQL database to store and manage e-commerce catalog data, enhancing flexibility and scalability.

3. **Data Warehouse and Reporting Dashboard**
   - Design and implementation of a data warehouse to consolidate and organize data, followed by the creation of a reporting dashboard to visualize key business metrics.

4. **ETL Operations and Web Server Log Analysis**
   - Utilization of Python scripts for various ETL operations, enabling seamless data movement between RDBMS, NoSQL, and the data warehouse. Additionally, implementation of a pipeline for web server log analysis, extracting, transforming, and loading relevant data.

5. **Search Term Analysis and Sales Forecasting**
   - Leveraging web server data for search term analysis, and incorporating a pretrained sales forecasting model to predict future sales, contributing to strategic decision-making.

## Usage

1. **MySQL OLTP Setup:**
   - Execute scripts in the `Oltp_DB` folder to set up the OLTP database.

2. **MongoDB NoSQL Integration:**
   - Follow instructions in the `NoSQL_DB` folder to integrate MongoDB for catalog data storage.

3. **Data Warehouse and Dashboard:**
   - Refer to the `cognos_dashboard` folder for instructions on data warehouse setup and dashboard creation.

4. **ETL Operations and Log Analysis:**
   - Utilize scripts in the `data_pipelines` folder to perform ETL operations and analyze web server logs.

5. **Search Term Analysis and Sales Forecasting:**
   - Explore the `ml_spark` folder for implementation details regarding search term analysis and sales forecasting.

## N.B:
The following requirements are needed for starting with the project:

1. **IBM_DB_SA**
2. **IBM_DB**
3. **MySQL_Connector_Python**
4. **Python_Dotenv**

# Conclusion
This capstone project demonstrates a holistic approach to building and optimizing an e-commerce data platform. The seamless integration of MySQL, MongoDB, ETL processes, data warehousing, and advanced analytics contributes to the company's data-driven decision-making capabilities.
