## Scraping data tables from a PDF file

<img src="https://github.com/plain-jane-gray/scraping-data-tables-from-PDF/assets/91796089/d12ded7d-e020-469c-ae68-6f30c9391c51" width=48% height=48%>   &rarr; <img src="https://github.com/plain-jane-gray/scraping-data-tables-from-PDF/assets/91796089/b3858e52-27ab-47a1-a29f-188d5f02c8db" width=48% height=48%>


The goal of this respository is to scrape data tables from a PDF file. Once extracted from the PDF file, it can be analyzed and eventually mapped to allow for the user to easily understand the data. 

This repository contains a single Jupyter notebook: 

**Scraping tables from a PDF file GH.ipynb.** 

*Input*: A single url to a PDF file on a publicly available website. 

*Output:* Three data tables as pandas dataframes that can be exported. 

The code does the following:
1. Reads in the names of the data tables in a PDF file. This allows the user to confirm that all data tables are being read.
2. Extracts data tables as lists from the PDF.
3. Accesses and flattens sublists.
4. Filters data to separate the data tables, adds headings, and remove nan values. This is repeated three times to separate out three different data tables 
