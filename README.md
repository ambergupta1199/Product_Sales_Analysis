### Architecture Diagram
![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/9f7ca380-907e-44c2-ac05-ef1d95014669)
### Project Architeccture Explanation
- **Data ingestion process**: Ingested raw data from Github using HTTP method in Azure Data factory and then dumped data into ADLS Gen 2 storage account.
- **Transformation**: Transformed the data in Azure Databricks using Pyspark & then dumped transformed cleaned data into ADLS Gen 2 storage account.
- **Implementation of Business Logic:** Implemented Logic in Azure Synapse using SQL after loading data into Synapse from ADLS
- **Analyzing the data:**: Created Synapse endpoint in Power BI to fetch the transformed data & created report on top of it.
### Power BI visualization dashboard
  ![image](https://github.com/ambergupta1199/Product_Sales_Analysis/assets/79975210/76ad1952-526f-49d6-93c5-00dc5b4f4147)

