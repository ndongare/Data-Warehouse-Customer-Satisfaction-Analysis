# Data-Warehouse-Customer-Satisfaction-Analysis

The project involves building an integrated data warehouse/ business intelligence solution for Fudge Corporation for customer satisfaction analysis. The goal was to create an integrated warehouse for 2 subsidiaries of Fudge Corporation: FudgeMart and FudgeFlix. 

1. Fudgemart – Fudgemart is a fictitious online retailer, similar to Amazon.com or Walmart.com. The database consists of customers, products and vendors, and has familiar business processes you would find in any online retailer.
2. Fudgeflix – Fudgeflix is a fictitious online DVD by mail and video on demand service, similar to Amazon instant video or Netflix. The database for Fudgeflix contains concepts such as accounts, subscriptions and video titles as well as other things associated with an online video streaming service. 

The project deliverables include high level dimensional modeling for 5 business processes like order fulfillment, customer satisfaction, payroll management, sales analysis and title rentals analysis as well as the detailed level modeling for Kimball (DDS) data warehouse architecture for customer satisfaction business process (reviews and ratings). The star schema (ROLAP) includes 4 Dimensions (Customer, Product, Date and TweetDictionary) and 1 Fact table (CustomerSatisfaction). The ETL was performed using SSIS to load the data from source to stage and stage to data warehouse and the MOLAP Cube is created using SSAS. The ROLAP star schema and MOLAP cube is used to visualize and explore the data with business intelligence tools like PowerBI and Excel to create interactive reports,
charts, maps, and dashboards. The insights obtained were used to provide data driven recommendations for improving customer satisfaction.
