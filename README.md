## Scraping data tables from a PDF file

<img src="https://github.com/plain-jane-gray/scraping-tables-from-PDF/blob/main/PDF%20image.jpg" width=48% height=48%>   &rarr; <img src="https://github.com/plain-jane-gray/scraping-tables-from-PDF/blob/main/pandas%20table.jpg" width=48% height=48%>

The code in this respository scrapes data tables from a PDF file. Once extracted from the PDF file, it is clean, analyzed, and mapped. The map allows the user to easily understand the data. 

This repository contains a single Jupyter notebook: 

**Scraping tables from a PDF file GH.ipynb.** 

*Input*: A single url to a PDF file on a publicly available website. 

*Output:* Three data tables as pandas dataframes that can be exported. 

The code does the following:
1. Reads in the names of the data tables in a PDF file. This allows the user to confirm that all data tables are being read.
2. Extracts data tables as lists from the PDF.
3. Accesses and flattens sublists.
4. Filters data to separate the data tables, adds headings, and remove nan values. This is repeated three times to separate out three different data tables 
