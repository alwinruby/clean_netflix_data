# Clean Netflix Data


A Straightforward Guide to Cleaning and Preparing Data in Python.

    1. Quick Dataset Overview

    2. Identify Missing Data
       - Create a percentage list with .isnull()

    3. Dealing with Missing Data
       - Remove a column or row with .drop, .dropna or .isnull
       - Replace it by the mean, median or mode
       - Replace it by an arbitrary number with .fillna()

    4. Identifying Outliers
       - Using histograms to identify outliers within numeric data
       - Using boxplots to identify outliers within numeric data
       - Using bars to identify outliers within categorical data

    5. Dealing with Outliers
       - Using operators & | to filter out outliers

    6. Dealing with Inconsistent Data Before Merging 2 Dataframes
       - Dealing with inconsistent column names
       - Dealing with inconsistent data type
       - Dealing with inconsistent names e.g. "New York" vs "NY"

    7. Text Normalization
       - Dealing with inconsistent capitalization
       - Remove blank spaces with .strip()
       - Remove or replace strings with .replace() or .sub()

    8. Merging Datasets
       - Remove duplicates with .drop_duplicates()
