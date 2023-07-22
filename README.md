# Azure-Data-Engineering

Hello all, Here I am going to talk about all Azure Data Engineering services like 
Data Factory, Az Blob, Data Bricks, Az SQL DB, Az Synapse, Functions, Logic App and many other services related to Data Engineering.

# AZ Blob: 
It's basically a storage account storing Terabytes and Petabytes of data with structured and Unstructured data.
Below are some services that are provided by Azure
Blob, ADLS, File share, Queue service, Azure Tables

# AZ Data Factory 
Activities: Copy, Foreach, If, GetMeta data, Execute, Data flow, Lookup, Web activity and others.
Incremental Pipeline: Using High Water Mark concept in Data Factory we are going to copy the data from ADLS to SQL DB and Vice-versa incrementally like for every hour.
Data Flow: It is basically used for Transformation purposes where we can do Filter, adding and update like we have Data Bricks.
Con's: It's not suitable for Large Datasets bcs it's actually going to lot of steps to implement and Time taking process.

# AZ Data Bricks:
It's one of the popular service that used in AZ servies. 
It's used for analysing and processing of the large amount of data like Tera/Peta bytes of data by using some transformations and actions.
