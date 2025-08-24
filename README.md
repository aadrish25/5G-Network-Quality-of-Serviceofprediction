# 5G-Network-Quality-of-Serviceofprediction
5G Quality of Service (QoS) Dataset and Analysis
Project Overview
This repository provides a comprehensive dataset and analysis pipeline for evaluating Quality of Service (QoS) in 5G networks. The dataset logs resource allocation and service metrics across a variety of applications (video calls, streaming, emergency services, gaming, IoT, web browsing, etc.) to study how different user scenarios impact network performance and resource management.

Dataset Description
The CSV file, Quality-of-Service-5G.csv, contains time-stamped observations including:

Timestamp: Date and time of the record

User_ID: Unique identifier for each user/session

Application_Type: Type of network use (e.g., video call, streaming, emergency service, etc.)

Signal_Strength: Received signal strength in dBm

Latency: End-to-end network latency in milliseconds

Required_Bandwidth: Minimum bandwidth required (Kbps/Mbps)

Allocated_Bandwidth: Bandwidth assigned by the network (Kbps/Mbps)

Resource_Allocation: Percentage of network resources allocated to the session

Use Cases
Data Analysis: Assess how resource allocation varies by application, signal strength, or latency.

Machine Learning: Train models to predict resource allocation based on network conditions and user/application types.

Service Categorization: Bin resource allocation values into categories ("Low", "Medium", "High") for classification and statistical analysis.

Network Optimization: Support research on dynamic resource allocation strategies in 5G networks for improved QoS.
