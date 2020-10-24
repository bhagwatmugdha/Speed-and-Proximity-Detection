# Speed and Proximity Detection Application

<div style="clear: both; ">
  <div style="float: left; margin-right 1em; ">
    <img src="UI Screenshots/SPD.png" align="left">
  </div>
    <p align="right">
    Speed and Proximity Detection System is a coming of age idea that can help change the way the current road security and law enforcement operate. The main bjective behind this project is to make Indian roads safer and disciplined, by monitoring the speeds at which each vehicle is travelling. This project encompasses the use of speed detection to notify drivers of any speeding violations. A proximity unit is also used to alert the driver incase he is driving too close to any vehicle, can also be used while parking.
    </p>
</div>

<br>
<br>

## Getting Started
<hr>

SPD includes two main use cases:
1. Speed Detection using ADXL 335 Accelerometer mounted on Arduino and its wireless transmission using Raspberry Pi to a database. The application detects overspeeding and abnormalities in driving. and send alerts to the driver via text and email.

2. Proximity Detection using HC SR04 Proximity Sensor mounted on Arduino.

### Prerequisites 

#### Flask Application
To run the User Application run the following commands to install the required:

<code>
 sudo apt-get install python-pip
 
 pip install flask

 sudo apt-get install mysql-server libmysqlclient-dev

 pip install flask-mysqldb

 pip install Flask-WTF

 pip install passlib
</code>

Run the Admin Dashboard

<code>
cd SPD_Web_Application/admin
python app.py
</code>

Run the User Page

<code>
cd SPD_Web_Application/user
python app.py
</code>

#### Arduino Code
To run the sensors code, install Arduino IDE and run the files in SPD_Arduino_Code after connecting the sensors to the Arduino

<img src="UI Screenshots/CktDigSpeedDetection.png">

<img src="UI Screenshots/CktDigProximityDetection.png">

#### Database 
Import the databse files in /Database/SQL_Database_Files directly using SQL Workbench
OR
Install MySQL and run all the queries listed in /Database/queries.txt  

### Application UI

<img src="UI Screenshots/UIStory.png">

<img src="UI Screenshots/AboutUsPage.png">

<img src="UI Screenshots/RegistrationPage.png">

<img src="UI Screenshots/LoginPage.png">

<img src="UI Screenshots/Dashboard.png">

<img src="UI Screenshots/SpeedGraph.png">