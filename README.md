**Automated Analytics Reporting**

An R-based, configuration-driven analytics tool that automates the creation of data visualizations from CSV datasets and JSON configuration files.

The tool separates visualization configuration from the underlying R code, allowing users to define variables, chart types, and visualization settings without modifying the source code.

**How It Works**

The reporting workflow is driven by two inputs:

1. CSV Dataset

The CSV file provides the underlying data used for analysis and visualization.

2. JSON Configuration

The JSON configuration defines how the data should be visualized, including:

Variables to analyze
Graph types
Visualization parameters
Data mappings
Chart-specific settings

The R script reads both inputs and dynamically generates the requested visualizations.

CSV Data ──────────────┐
                       ├──> R Analytics Engine ──> Visualizations
JSON Configuration ────┘

This separation allows the same R code to be reused across different datasets and reporting requirements.

**Features**
Configuration-driven visualization
Automated chart and graph generation
JSON-based visualization parameters
Dynamic variable mapping
CSV-based data input
Automated data processing
Reusable visualization workflows
Multiple graphing functions and visualization types
No R source-code modification required for new configurations

<img width="2206" height="552" alt="mermaid-diagram (17)" src="https://github.com/user-attachments/assets/800e3056-2882-461c-80ba-dca2772c94af" />

