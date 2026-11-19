# biostat721-project2-airpollutiondata

Project 2: Air Pollution Analysis

Analyzing three air pollutants (CO, PM2.5, and O3) across the years of 2018 - 2020 in Durham County, North Carolina.

Data Source: Air pollution data from the EPA monitor at the RDU airport.

File Structure: 
  Project Folder contains :
    - RProj file-
    - RMarkdown file that contains the code for data cleaning, and table/plot generation.
    - Final Report (Word Document)
    - Data Folder:
      - 2018 Air Quality Excel File
      - 2019 Air Quality Excel File
      - 2020 Air Quality Excel File
    - README file with project description
    
How to Reproduce:
1) Set up R Project folder to include script and Data folder
2) Create function with inputs of the folder path and specification of units.
3) Clean data by formatting Date variable in standard R format
4) Clean data by setting pollutant values less than 0 to 0
5) Clean data by calculating the average for duplicate values
6) Clean data by removing any duplicate rows
7) Use function to specify if units should be parts per million (ppm) or parts per billion (ppb)
8) Bind the three outputted cleaned (2018, 2019, and 2020) datasets together
9) Creat summary tables for each year with the minimum and maximum values for each pollutant
10) Create Plot 1 by calculating the monthly average and 95% confidence interval for pollutants CO and O3 across the three years, and plotting using box plots across the months (using ggplot)
11) Create Plot 2 by finding the monthly average of PM2.5 for each of the three years, and visualizing using a line graph across the months for each year.

R Packages:
- dplyr: Version 1.2.1
- ggplot2: Version 4.0.3
- lubridate: Version 1.9.5
- wesanderson: Version 0.3.7
- gt: Version 1.3.0
- tidyr: Version 1.3.2

Author: Arya Nair
Date: 11-20-2026
