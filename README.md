# IST615_Project
Scripts and code for Azure based datacenter environmental monitoring project. 

Our project utilized cloud services to track and log the temperature and humidity of a fictional server room as a proof-of-concept solution to these problems. Whenever the temperature or humidity exceeds set thresholds, an alert will be created and sent out via email with details on the current status to notify personnel of the dangerous conditions. The data will is simulated since we don’t have access to a live server room and to allow for straightforward testing. The data was logged and saved in the cloud permanently for reference and possible long-term trend analysis, although that is currently out of the scope of this project. Microsoft Azure services were primarily utilized for this project. By actively monitoring the status of a server room and utilizing the versatility, power, and scalability of the cloud, this project will serve as a proof of concept solution for organizations struggling to monitor the environmental status of their critical infrastructure.

Services used: Azure IoT Hub, Service Bus, Stream Analytics, Table Storage, PowerBI, and Logic Apps.
