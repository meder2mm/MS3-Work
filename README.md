# MS3-Interview

# DESCRIPTION

1. We need a Java application that will consume a CSV file, parse the data and insert to a SQLlite In-Memory database.  

  a. Table X has 10 columns A, B, C, D, E, F, G, H, I, J which correspond with the CSV file column header names.

  b. Include all DDL in submitted repository

  c. Create your own MySQL DB


2. The data sets can be extremely large so be sure the processing is optimized with efficiency in mind.  


3. Each record needs to be verified to contain the right number of data elements to match the columns.  

  a. Records that do not match the column count must be written to the bad-data-<timestamp>.csv file

  b. Elements with commas will be double quoted


4. At the end of the process write statistics to a log file

  a. # of records received

  b. # of records successful

  c. # of records failed
