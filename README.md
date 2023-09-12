# Real-time stream processing with Stream Analytics

In this Project , I have ingested Vehicle telemetry events data into Event Hubs, processed that data in real time using Azure Stream Analytics Service and then finally loaded that data into a table created in Azure Synapse Studio Workspace. Data stored in Synapse Studio is then used to create a Power BI Report.

## Dataset Description
Data is created with the help of Data Generator Application which creates and sends simulated vehicle sensor telemetry for an array of vehicles.
Link to find this application :- https://github.com/MicrosoftLearning/DP-203-Data-Engineer/blob/master/Allfiles/TransactionGenerator.zip
Download and Unzip the folder.

## Tech Stack
   #### Langauges - SQL
   #### Services - Azure Synapse Studio , Azure Evet Hub , Azure Stream Analytics , Power BI

## Azure Event Hub
Azure Event Hubs is a big data pipeline that can ingest millions of events per second. It facilitates the capture, retention, and replay of telemetry and event stream data, using standard protocols such as HTTPS, AMQP, AMQP over websockets, and Kafka. 

## Azure Stream Analytics
Azure Stream Analytics Service allows us to perform analytics on data in real time. It supports SQL-Like language to design analytical solution. You can instantly scale-out the processing power from one to hundreds of streaming units for any job. You only pay for the processing used per job.

## Azure Synapse Studio
Azure Synapse is an end-to-end analytics platform which combines SQL data warehousing, big data analytics, and data integration into a single integrated environment. It empowers users to gain quick access and insights across all of their data, enabling a whole new level of performance and scale that is simply unmatched in the industry.

## Power BI
It is a tool that is used to create charts/dasboards/reports over the data.
