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


# Analysis

# Conclusion
