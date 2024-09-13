🚀 Project Completed: Automated ETL Pipeline for Sales Data Transformation 🚀

I’m excited to share a recent project where I designed and implemented an automated ETL pipeline for sales data using Pentaho and PostgreSQL. This project involved transforming raw sales data into a structured core schema, significantly enhancing data usability and reporting.

Key Transformations:

Data Extraction & Loading: Imported data from CSV into the staging schema, including fields like transaction_id, transactional_date, product_id, customer_id, payment, and more.

Date & Time Dimension Creation: Developed date and time dimension tables with foreign key mappings, using formats like YYYYMMDD for date and HHMMSS for time.

Calculated Columns: Added and calculated total_cost, total_price, and profit to provide deeper insights into the data.

Junk Dimension: Created a junk dimension to manage and consolidate miscellaneous payment types and related attributes.

The data flow was automated with two separate master jobs for initial and delta loads, ensuring the core schema remains up-to-date with the latest sales information. Both the master jobs have their own tranformations. Most of them are the same and being resused but the Staging Job within the Master ETL job varies in the case of delta and initial load obviously, as the last load variable had to be a value such that all data would be extracted in the case of initial load.



📊 Data Visualization:

Input Data: Displays raw CSV data.
Core Data: Showcases the transformed core schema with enriched metrics and structured dimensions.

📈 This project highlights my skills in data engineering, ETL processes, and database management, demonstrating my ability to transform raw data into valuable insights while maintaining efficiency and accuracy.
