### Architecture Diagram
![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/9f7ca380-907e-44c2-ac05-ef1d95014669)
### Project Architeccture Explanation
- **Data ingestion process**: Ingested raw data from on-prem SQL database using Self Hosted Integration Runtime method in Azure Data factory and then dumped data into ADLS Gen 2 storage account as a bronze layer data.
- **Transformation**: Transformed the data in Azure Databricks using Pyspark & then dumped transformed cleaned data into ADLS Gen 2 storage account as gold layer data.
- **Analyzing the data**: Created Stored Procedure for creation of views and automate the views creation through pipeline in Synapse.
- **Reporting:**: Created Synapse endpoint in Power BI to fetch the analyzed data & created report on top of it.


### Power BI visualization dashboard
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/76ad1952-526f-49d6-93c5-00dc5b4f4147)
#### Data getting sliced at State level stating number of products, total sales,no. of customers, gender classifcation in particular state
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/e45605e0-b0e7-4bc7-9834-7435a73560c9)
#### Data getting sliced at Product Category level stating number of distinct products, total sales ,no. of customers, gender classifcation for particualar product
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/72fbfddc-788f-4a37-9ca1-fbf17d3b6b06)


## Project Snapshots
- **Data ingestion**
![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/9ca2a761-56df-42f3-a7e3-41944fc85fa2)
- **Dumped raw data to ADLS**
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/3c28e9fc-b7f5-419d-8629-ff83730b1407)
- **Transformed data in Azure Databricks**
  Changed all the dates in all tables to "yyyy-MM-dd" format & dumped into silver layer container.
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/8a99074e-c26a-4289-bc96-4d4f2e0425d8)
  Made all the colum names in non pascal format, like Sales_id
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/633024ca-0026-4ef6-85c7-e5cbed7a4783)
- **Creation of Synapse Views through pipeline & Stored Procedure**
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/1a3bbefc-866f-41f3-ac4c-47504d57dcbf)
  ### Pipeline
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/b717a4d5-430e-466c-8d4c-73c114432896)

  






