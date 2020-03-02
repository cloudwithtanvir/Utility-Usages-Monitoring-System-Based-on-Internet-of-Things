# Utilies usages monitoring system based on IoT (Netduino Hackster.io project 2018).
## Summary
The main idea for this project is, building a dashboard for monitoring the utilities usages such as water, gas, electricity. The system is helpful for prepaid users, since prepaid users need to buy credits before use them. Its really difficult for users to check the usages and tracking the remaining credits regularly. The prepaid utility system automatically cut the line if the remaining credits goes zero. This project helps users to prevent cut off situation by monitoring the usages regularly. The system also provides sms based push notification to users if the credits goes low (This part is left for future work). The postpaid users also get benefited from this system. postpaid users able to know the usages amount, which is helpful for excess bills. The utility companies remotely monitor their meters by using this system which is helpful for preparing the postpaid bills. Additional features may be added depending the user’s/company’s needs.
![The block diagram of the system.](/figure/block_diagram.jpg)
## Things you need
- Netduino 3 Ethernet version.
- Current sensor.
- Water and Gas flow sensor.
- Android Device
- Internet connection
- Jumper wire.
- CAT5 cable.
- soldering Iron.
- Android Application Development platform.
- IoT Cloud Platform (thinger.io is used here).
- Visual Studio 2015.
- Portable battery or power supply.
## Circuit diagram
The circuit diagram is given bellow:
![circuit diagram-02.](/figure/water_flow.jpg)
The Water and gas flow sensor have three pin.
- Red wire (for VCC).
- Black wire for GND.
- Yellow wire for signal.
Connect the signal wire with netduino D3 and D4 pin respectively for GAS and Water sensor. The more details about those sensors are available in [SeeedStudio](https://www.seeedstudio.com/G1&2%22-Water-Flow-Sensor-p-635.html). Please refer their wiki page.
![circuit diagram-01.](/figure/current.png)

The circuit diagram shows; how current sensor is used for determining the load.
## IoT Cloud
Thinger.io IoT cloud platform is used here for building the project. An account is mandatory for connecting the device with thinger.io. please refer the [thinger.io](http://docs.thinger.io/arduino) documentation section for more details about device connectivity and others.
## Mobile Apps
A mobile application for remotely monitoring the utilities usages is also developed. The application is directly connected with iot-cloud and it visualizes the real-time information of every meter. Refer the demonstration section for more details. An open-source android application development platform is used for developing the apps.
</br>**The APK file is available in my git repository** 
## Demo
[video Demo](https://youtu.be/kCX88yjWsZo)
## Setting up Netduino with Visual studio 2015
Check the Hackster.io </br>
[Getting started guide](https://www.hackster.io/salahuddin/real-time-utilities-usage-monitoring-system-based-on-iot-4e5988)
