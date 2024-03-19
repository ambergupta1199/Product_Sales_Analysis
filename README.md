### Architecture Diagram
![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/9f7ca380-907e-44c2-ac05-ef1d95014669)
### Project Architeccture Explanation
- **Data ingestion process**: Ingested raw data from Github using HTTP method in Azure Data factory and then dumped data into ADLS Gen 2 storage account.
- **Transformation**: Transformed the data in Azure Databricks using Pyspark & then dumped transformed cleaned data into ADLS Gen 2 storage account.
- **Implementation of Business Logic:** Implemented Logic in Azure Synapse using SQL after loading data into Synapse from ADLS
- **Analyzing the data:**: Created Synapse endpoint in Power BI to fetch the transformed data & created report on top of it.
### Power BI visualization dashboard
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/76ad1952-526f-49d6-93c5-00dc5b4f4147)
## Project Snapshots
- **Data ingestion**
![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/9ca2a761-56df-42f3-a7e3-41944fc85fa2)
- **Dumped raw data to ADLS**
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/3c28e9fc-b7f5-419d-8629-ff83730b1407)
- **Transformed data in Azure Databricks**
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/633024ca-0026-4ef6-85c7-e5cbed7a4783)
- **Creation of Synapse Views through pipeline & Stored Procedure**
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/1a3bbefc-866f-41f3-ac4c-47504d57dcbf)
  ### Pipeline
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/b717a4d5-430e-466c-8d4c-73c114432896)

  






