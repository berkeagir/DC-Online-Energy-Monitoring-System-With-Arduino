# Online-Energy-Monitoring-System-With-Arduino
This code aims to gather energy datas such as current, voltage values as remote and it calculates the energy.
All of these datas are storing into SD card by means of datalogger shield.
To obtain current values, ACS-712 current sensor is used.
For calculating Voltage values, 1x47k ohm resistor and 1x2.5k ohm resistor are connected as serial. In that way, DC voltage values are obtained by means of Superposition theorem. 
All of the datas that gathered can seeing on the LCD panel as monitoring in real time.
Thanks to Wi-fi module which is ESP8266 , gathered datas can be transfered to desired website or applications as online. In that case, thingspeak.com is used to send datas.
In that project, 1X Datalogger Shield, 1X I2C Led Shield, 1X Arduino Uno, 1X ESP8266 Wi-fi module, 1x ACS712 current sensor is used.
