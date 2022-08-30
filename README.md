# Masters Research Project 
## Data Center Energy Management @ ENEA Portici Research Center, Italy
## Awarded best Master Thesis Award :trophy: at 6th IFAC Symposium on Telematics Applications (Nancy, France)

* Introduction
  ------------

This project is Master thesis research conducted at ENEA Portici Research Center. The data is obtained from the HPC CRESCO6 cluster at ENEA Portici Research Center. The aim is to identify energy consuming areas within the data center. In this project, real-time dataset from ENEA Portici Research Center is used. Since the research is in collaboration with the organization, the dataset cannot be shared publicly as it is against the organization’s policy. There are several techniques implemented including big data analytics and AI technology. The research is divided into 4 phases. 

1.	First phase provides exploratory data analysis of dataset which involves data collection, data transformation, descriptive analysis and inferential statistical analysis. Since, the data cannot be made publicly available, the experiments for this phase are not provided. 

2.	Second phase analysis the thermal characteristics of the IT room in data center. Machine learning classification is used to identify the thermal conditions of the IT room. 

3.	Third phase uses deep learning modelling for advance prediction of resource utilization which includes CPU, memory and network utilization. 

4.	Forth phase future forecast the active energy consumption and energy waste by jobs execution in the data center.

The methodology can be implemented on different datasets of other data centers. 

* Requirements
  ------------
1.	The provided codes works in all python versions above 3.7.0. 

2.	The dataset used in this project was quite large, So Google Colab Pro is used. Otherwise any Python IDEs can be used.


* Installation
  ------------
There are few python packages and libraries that need to be installed which are provided in the python codes. 

* Tools Used
  ------------
  1. Google Colab Pro
  2. Python language
  
* Dataset Info
  ------------
  1. Sensor Data: obtained from compute node (server) sensors and it consists of timestamp, cpu, memory, network utilization, fan speed, node temperature etc.
  2. Jobs Data: data about jobs submitted to servers for processing and it consists of timestamp, job start time, job end time, job status etc. 
  3. Cooling Data: collected from cooling machines (AC) in IT room. It consists of data such as timestamp, cooling machine status, temperature etc.
  4. Environment Data: collected from different temperature and humidity sensors installed in IT room and it consists of room temperature and humidity for both hot and cold aisles. 
  
* Python Files Description
  ------------
  
  1. Coversion of seconds data to hourly data: python code on transformation of seconds data to hourly data using sampling method. 
  2. IT Room Thermal Data Classification: provides machine learning classification of IT room thermal data onto multiple classes such as low, medium, high temperature as per ASHRAE Recommendations. 
  3. LSTM_for_Prediction_of_Resource_Utilization: python code for advance prediction of resources utilization in DC using LSTM. 
  4. Future Forecast of Energy Consumption and Waste: python code for future forecast of active energy consumption and energy waste based on the job status using SARIMA modelling. 
  
  
 I hope this code helps :smiley:
