# Data-Integration-Pipelines-for-NYC-Payroll-Data-Analytics-with-Azure
Udacity Data Engineering (Pipelines)
Project Overview
Project Introduction

The City of New York would like to develop a Data Analytics platform on Azure Synapse Analytics to accomplish two primary objectives:

    Analyze how the City's financial resources are allocated and how much of the City's budget is being devoted to overtime.
    Make the data available to the interested public to show how the City’s budget is being spent on salary and overtime pay for all municipal employees.

You have been hired as a Data Engineer to create high-quality data pipelines that are dynamic, can be automated, and monitored for efficient operation. The project team also includes the city’s quality assurance experts who will test the pipelines to find any errors and improve overall data quality.

The source data resides in Azure Data Lake and needs to be processed in a NYC data warehouse. The source datasets consist of CSV files with Employee master data and monthly payroll data entered by various City agencies.
NYC Payroll DB Schema
![nyc-payroll-db-schema](https://github.com/Danny-Kirchner/Data-Integration-Pipelines-for-NYC-Payroll-Data-Analytics-with-Azure/assets/168898273/fcac4576-b173-4e46-b37f-48862e10dc83)


In the following pages, we will go through the project instructions and by the end you will have built a Data Integration Pipelines on the NYC Payroll Data. We will be using Azure Data Factory to create Data views in Azure SQL DB from the source data files in DataLake Gen2. Then we built our dataflows and pipelines to create payroll aggregated data that will be exported to a target directory in DataLake Gen2 storage over which Synapse Analytics external table is built. At a high level your pipeline will look like below

High level Pipeline Overview
![data-integration-pipelines-overview](https://github.com/Danny-Kirchner/Data-Integration-Pipelines-for-NYC-Payroll-Data-Analytics-with-Azure/assets/168898273/65d2c628-6005-4c2b-b262-41beb0665562)

