# Smartwatch_Data_Analysis
C++ console app for analysis of smartwatch data

The purpose of this project is to develop a simple CMake based C++ console application
which receives data export from my Withings Smartwatch as input and outputs a report 
based on my aggregated daily activity.

The data export consists of several CSV files each containing different kind of data.

The report will be provided as simple console output and also as a formatted, summary CSV file.

The program shall consist of 4 main parts: 
- a Data Parser, which abstracts the data found in the CSV files,
- a Data Model, which will serve as a well structured container for the extracted data, having appropriate functions for data handling,
- a Statistic Module, which will provide functions that act on the Data Model and retrive useful information,
- and an Output Module, which will provide a structured output on the console and in a separate CSV summary file.
