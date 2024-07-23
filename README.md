# Azure-Data-Factory

# Azure-Data-Factory
Azure is a cloud platform and it provides multiple services which are used to make our works smarter and automate by decreasing the manual work.
Some of the examples are Azure Data Factory, Azure Logic Apps, Azure function Apps etc.,
 
![image](https://github.com/user-attachments/assets/d890f46f-92bb-4b77-9c19-96bace8fb1ca)
 
 
Azure data factory as commonly known as ADF is a ETL(Extract-Transform- load ) Tool to integrate data from various sources of various formats and sizes together, in other words, It is a fully managed, server less data integration solution for ingesting, preparing, and transforming all your data at scale.The pipelines of Azure data factory are used to transfer the data from the on-premises to the cloud with in the certain period of intervals.
 
![ADF](https://github.com/user-attachments/assets/77140ad8-b793-4601-b468-94dd77141824)
 
The above picture dipicts how the Azure data factory working from start to end.
Pipeline in simple layman terms " A pipeline is a connection medium which connects both ends( Source and Sink ).
 
Now, Let me walk you through the ADF window.
 
![UI_ADF](https://github.com/user-attachments/assets/93907f68-4c6e-407b-b70c-b121d623f142)
 
On the left side panel we do have 4 types of options.
**Home** - It is the landing page when we launch the studio and we can see the recent the recent activities. And we have multiple advanced data movement activties are there.
**Author** - Here the actual data movement is happening by creating pipelines , datasets, capturing the data change etc.,
**Monitor** - In this monitor we will monitor the activities of pipelines, Triggers, CDC( change data capture ), integration runtime etc.,
**Manage** - In this manage button we are going to create connections and linked servces and many more...
 
 
See, As we are moving the data from one **source** to another source ( which we called as **sink** or our target location).
First and foremost job is we need to establish the connections and connect the source and sink by using pipeline.
For every pipeline we need to follow these steps irrespective of the source where we are extracting the data and loading to any sink.
 
Intergration runtime
Linked services
datasets
pipeline
