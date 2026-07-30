**Automated-Analytics-Reporting**

An R-based, configuration-driven analytics tool that automates the creation of data visualizations from CSV datasets and JSON configuration files.

The script dynamically loads and processes data, maps variables to data frames, and generates visualizations based on parameters defined in a JSON configuration file. Users can select the variables, graph types, and visualization settings through the configuration file without modifying the underlying R code.

This approach simplifies and standardizes repetitive reporting workflows while making the visualization process more flexible, reusable, and scalable.

**Features**

Automated chart and graph generation
JSON-driven configuration for customizable visualizations
Dynamic variable mapping and data processing
CSV-based data input
Reusable visualization workflows without modifying R source code
Supports multiple graphing functions and visualization types

**Requirements**

Install the required R Packages before running the script:

install.packages(c("tidyverse", "jsonlite"))

**R Packages**

tidyverse – Data manipulation and visualization
jsonlite – Reading and processing JSON configuration files
