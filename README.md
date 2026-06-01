**Graph Generator**

This R script generates charts dynamically based on parameters specified in a JSON configuration file. It loads data from CSV files, maps variables to data frames, and executes a selected graphing function using information provided in the JSON input.

The primary purpose of this script is to automate graph creation without requiring changes to the R code itself. Users can modify the JSON configuration to select different variables and graph types.

**Requirements**
R Packages

Install the required packages before running the script:

install.packages(c("tidyverse", "jsonlite"))

The script uses:

tidyverse – data manipulation and visualization, jsonlite – reading JSON configuration files
