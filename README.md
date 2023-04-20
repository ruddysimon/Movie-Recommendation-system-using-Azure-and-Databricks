# Movie-Recommendation-system-using-Azure-and-Databricks
---

The project involves building a movie recommendation system using Microsoft Azure and Databricks. The first step in the process is to create a resource group in Azure, which is a logical container for Azure resources like virtual machines, databases, and storage accounts. The next step is to create containers in Azure Blob Storage and add the data source into the containers.

After the data is stored in Azure Blob Storage, a pipeline is created to copy the file into the container data lake edge. Azure Data Factory can be used to create this pipeline. Once the data is available in the data lake edge, Databricks can be used for analysis.

To access the file, an access key is required. The data is stored as a zip file, which is considered as a binary file. Hence, the first step is to unzip the file before analyzing the data. Once the data is unzipped, it can be processed using Databricks. Databricks is a cloud-based platform that allows for the creation of data pipelines, machine learning models, and visualizations. 
