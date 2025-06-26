# Sales-Data-ETL-Pipeline-with-Talend-SCD2-Transformation-
ETL project using Talend to read, clean, and transform sales data from CSV. Includes filtering, total price calculation, and basic SCD2 logic. Outputs cleaned data to CSV using Talend components like tMap and tFileOutputDelimited.


Sales Data ETL Pipeline using Talend

This project demonstrates a simple ETL pipeline built in Talend Open Studio to process sales data from a CSV file. It reads the raw input, filters out invalid or incomplete rows, performs a transformation by calculating the TotalPrice (Qty × UnitPrice), and outputs the cleaned data to a new CSV file.

Key features include:

Input from flat file using tFileInputDelimited

Data transformation and filtering using tMap

Conditional calculations with null handling

Output using tFileOutputDelimited

Basic Slowly Changing Dimension (SCD2-like) flag logic for updated records

Logs for monitoring using tLogRow

This project is designed for learning ETL fundamentals, Talend component usage, and building job flows for data cleansing and transformation tasks. It is ideal for beginners and intermediate-level data engineers.


