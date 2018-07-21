# SMART WEATHER MONITORING AND ALERT SYSTEM USING IoT
The proposed embedded device is for monitoring Temperature, Humidity, light intensity and in the atmosphere to make the environment intelligent or interactive with the objects through wireless communication. The proposed model is more adaptable and distributive in nature to monitor the environmental parameters.
The implemented system consists of ESP8266 as a main processing unit for the entire system and all the sensor and devices can be connected with the microcontroller. The sensors can be operated by the microcontroller to retrieve the data from them and it processes the analysis with the sensor data and updates it to the internet through Wi-Fi.

# Stages Involved in System:
1.	 Sensing: 
- Various parameters are measured with the help of appropriate sensors; GPS is interfaced with ESP8266 module for gathering location     information whose values are transferred to cloud (ubidots).
2.	Data processing and transferring:
- ESP8266 module is Connected to internet trough Wi-Fi module                                            
- Reading sensor values, uploading / transferring sensor values to web page for storing in database and for Real time remote monitoring.
- Reading GPS (longitude and latitude) values and uploading onto web page and app to store in database for location monitoring
3.	Data Display (Options available on Web Server):
-	Transferred data to database.
-	Continuous display of weather parameters on web page and app includes Humidity, Temperature, Light intensity, Air pressure & Precipitation
-	Display of location details on web page  and app (Map of Location of the system on Google Maps)
-	Display of readings using graphs for prediction analysis.
4.	Power Supply:
- 5V as input to ESP8266.

# System Architecture:
The implemented system consists of ESP8266 (NodeMCU) as the microcontroller as well as a Wi-Fi module for the entire system, with all sensors and devices interfaced on it. The sensors are used to retrieve real-time data which is sent to the circuit board for processing/analysis. Through the internet services these data are sent to the cloud (ubidots) for visual and graphical representation. A designed web page can access data from the cloud. Using ubidots.com (IoT based platform) we have designed an alert system. Integrating ubidots & IFTTT an email or sms notification is sent on crossing the set threshold value of weather parameters. 

# Implementation
Based on the framework shown in figure 2, we have identified a suitable implementation model that consists of different sensor devices and other modules, their functionalities are shown in figure 3. In this implementation model we have used ESP8266 (NodeMCU) with its inbuilt Wi-fi connectivity, having sensors interfaced on the board. The ESP8266 has analog input pin (A0) and digital output pins (D0-D8). The in-built ADC and Wi-fi connectivity of the board helps us to connect the embedded devices to the internet. Sensors are connected to ESP8266 board for monitoring, ADC will convert the corresponding sensor reading to its digital value and from that value the corresponding environmental parameter will be evaluated.    

The Wi-Fi connection has to be established to transfer sensors data to end user and also send it to the cloud storage for future usage.      
All the sensor devices are connected to internet through  Wi-Fi module. The data from the sensors are processed on the ESP8266 (NodeMCU) and sent to the cloud which is an integration of Ubidots and IFTTT. A designed web page will be able to access the data in the cloud as and when required. Depending on the threshold value set for each weather parameter, an alert notification which could be a mail or SMS will be sent for controlling purpose 

# Conclusion
By keeping the embedded devices in the environment for monitoring enables self-protection (i.e., smart environment) to the environment. To implement this need, deploy the sensor devices in the environment for collecting the data and analysis. By deploying the sensor devices in the environment, we can bring the environment into real life i.e. it can interact with other objects through the network. Then the collected data and analysis results will be available to the end user through the Wi-Fi (internet). The smart way to monitor environment and an efficient, low cost embedded system is presented with different models in this paper.   In the proposed architecture functions of different modules were discussed. The weather monitoring system with Internet of Things (IoT) concept experimentally tested for monitoring weather parameters. It also sent the sensor parameters to the cloud (ubidots & IFTTT). This data will be helpful for future analysis and it can be easily shared to other end users.    This model can be further expanded to monitor the developing cities and industrial zones from weather alerts. this model provides an efficient and low-cost solution for continuous monitoring of environment. 
