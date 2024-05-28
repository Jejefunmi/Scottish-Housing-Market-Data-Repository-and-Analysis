# Microsoft_fabric_Scottish-Housing-Market-Data-Repository-and-Analysis
![](housing.jpg)
## Introduction
This project leverages data engineering and analysis techniques to create a comprehensive data repository for analyzing and tracking housing projects within Scotland. By collecting and processing news articles related to Scottish housing, this platform aims to provide valuable insights for various stakeholders, including investment firms, mortgage providers, and financial institutions.

## Problem Statement
The Scottish housing market is influenced by various factors reported in news articles. However, the data is often scattered and unstructured, making it challenging for analysts to extract meaningful insights.
This project addresses this problem by:

   * Centralizing news data related to Scottish housing projects.
  
   * Transforming unstructured news articles into structured data.
  
   * Performing sentiment analysis to understand public perception.
  
   * Storing the processed data in a format suitable for analysis and reporting.

## Project Objectives
The primary objectives of this project are:

 * Environment Setting: Setting up Azure account and Microsoft Fabric. Also designing the Data Architecture
  
 * Data Collection: Aggregate news articles related to housing projects in Scotland from various sources.
  
 * Data Processing: Clean, transform, and store the collected data in a structured format.
  
 * Sentiment Analysis: Perform sentiment analysis on the news articles to gauge public perception.
  
 * Data Storage: Store the processed data in a Delta table for efficient querying and analysis.
  
 * Insights Generation: Provide a robust dataset that housing analysts can use to derive valuable insights.

## Data architecture
![](Data_architecture.jpg)
The Project employs a robust data architecture to collect, process, store, analyze, and visualize housing-related news.
Data is sourced from the Bing News API and stored in Lake Database. Using Synapse spark Nootbook, the data undergoes transformation, cleaning, and sentiment analysis via SynapseML.
The cleaned and enriched data is stored in Delta Lake tables, enabling efficient incremental updates. 
Power BI is used for creating interactive dashboards and visualizations, providing stakeholders with valuable insights into housing trends, sentiment analysis, and news categorization.

## Environment Setting
An Azure Account was created in other to provide access Microsoft's cloud services. This account gives access to creating Bing News API which allows me to programmatically fetch real-time news articles related to housing in Scotland. This step is crucial to obtain API Keys. The API keys generated enable secure and authorized access to Bing's news data, allowing us continuously update our dataset with the latest information.
