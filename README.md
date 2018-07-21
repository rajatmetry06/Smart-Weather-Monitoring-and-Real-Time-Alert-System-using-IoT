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

