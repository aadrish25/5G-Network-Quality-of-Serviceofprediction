📡 5G Quality of Service (QoS) Dataset and Analysis
📌 Overview

This project provides a dataset and analysis pipeline for evaluating Quality of Service (QoS) in 5G networks.
The dataset captures resource allocation and service metrics across various applications such as video calls, streaming, emergency services, gaming, IoT, and web browsing.

The goal is to study how different user scenarios impact network performance and resource management.

📂 Dataset Description

The dataset (Quality-of-Service-5G.csv) contains time-stamped observations with the following fields:

⏱ Timestamp – Date and time of the record

👤 User_ID – Unique identifier for each user/session

📱 Application_Type – Type of network use (e.g., Video Call, Streaming, Emergency Service, Gaming, IoT, Web Browsing)

📶 Signal_Strength – Received signal strength (dBm)

⏳ Latency – End-to-end network latency (ms)

📊 Required_Bandwidth – Minimum bandwidth required (Kbps/Mbps)

📊 Allocated_Bandwidth – Bandwidth allocated by the network (Kbps/Mbps)

⚡ Resource_Allocation – Percentage of network resources assigned to the session

🚀 Use Cases

Data Analysis → Study how resource allocation varies by application type, signal strength, and latency

Machine Learning → Train supervised models to predict resource allocation given network conditions and user/application type

Service Categorization → Bin Resource_Allocation into categories (e.g., Low, Medium, High) for classification tasks

Network Optimization → Support research on dynamic resource allocation strategies in 5G networks to improve QoS

📈 Example Applications

Predicting QoS levels (Good / Moderate / Poor) using supervised ML

Analyzing bandwidth allocation fairness across application types

Building dashboards to visualize 5G performance trends
