# National-Homelessness-and-Prison-Data
## Ivonne Soto & Pratyush Painuly

## Model: 
![ETL Diagram](img/diagram.png)

**NHPD (National Homelessness and Prison Data)** aims to Extract, Transform and Present data for Homelessness and Prison insights for United States. Our aim is to find detail datasets from various sources and store it in one single repository, which can be further used for analysis and research. We hope to contribute in finding key insights into such an relevant topic and generate discussions based on the data that we have discovered and compiled.

**The key features** of this ETL project are:

-  Explore and transform raw data provided by Housing and Urban Development(HUD) for the entire country. Transform the complex data into ready-to-use source. The source file used is HUD Excel metadata.
-  Find a model to identiy key variable for Prison Data. Web Scrapping Bureau of Justice website to gather the entire data set from 1978-2016 on a national, state level and group the data by proper metrics(Gender, Time period, Jail population). The data scrapped is extensively transformed to make it easy to interpret and analyze.
-  The data sets are loaded and transformed in Jupyter notebook for futher clean up and presentation.
-  Once the data sets are ready to be used and shared to public, the two sets are stored in a local Mongo Database as two separate collections. The data sets are also exported as two separate data dumps. We encourage all researchers/analysts to explore the datasets either by the csv files provided, or from the Mongo DB database that we have created, as per their convenience.
