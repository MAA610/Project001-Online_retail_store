# Project001-Online_retail_store
This is an analysis for transactional data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

# files
- The source file for the dataset comes from [UC Irvine machine learning repository](https://archive.ics.uci.edu/dataset/352/online+retail)  
- The final dashboard analysis can be found in project001.xlsx

# Tools
The following Excel skills were utilized for analysis:  
- 📉 Charts
- 🧮 Formulas and Functions
- ❎ Data Validation

# Process
## Explaratory data analysis
First, I explored the dataset inorder to get a high-level understanding of the kind of data i'm dealing with.
## ETL process
After importing the dataset into excel, I strated the ETL process using excel's power query. Using power query, I was able to exclude rows with empty cells in the description column, customer ID column, and item price column. Less than 1% of the dataset was affected by these transformations.  
The following tables were created to help analyse the dataset using the 'group by' option:  
- invoices table
- customers table
each table is further utilized in the next step. 

## Building blocks
The following tables were created to help analyse the dataset using excel's pivot tables:  
- invoices pivot tables.
- customers pivot tables.
  
## Visualizations
Using the pivot tables created in the previos step, the following visualizations were created:
1. Sales per quarter
     
   ![image](https://github.com/user-attachments/assets/c8784d8b-69f4-459e-840e-d6dfe5944321)
   an interactive line chart created with a country slicer.
   
2. Sales per country and international presence  
   ![image](https://github.com/user-attachments/assets/68be847a-06bd-4ea7-a910-a19d3c8573d7)
   ![image](https://github.com/user-attachments/assets/8ba2efc3-b909-4a8f-a9fd-811fbd51a91e)
   a pie chart and amap to visualise sales per country and the disrribution of serviced countries.

3. customers per country
   ![image](https://github.com/user-attachments/assets/d8beaa51-f497-49e3-a20d-9659fd3eb9c4)
   a horizontal bar graph showing the number of cutomers per country

5. Invoices per country
   ![image](https://github.com/user-attachments/assets/fc47eb1e-386b-44e0-9e5d-2f710e19a997)
   ![image](https://github.com/user-attachments/assets/b72d358b-9746-474b-8c97-09f0a5718d1d)
   a horizontal bar graph and a line chart representing the distribution of ivvoices per country, along with a date slicer.


# Analysis

# Conclusion
