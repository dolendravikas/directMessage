# directMessage

<img src="Images\logo.MOV" alt="logo"/>

A custom piece of hardware that communicates with the other same device over a secure 865MHz (EU868/US915/AU915/KR920/IN865) channel using the Lora E5 SOC from the Seeed Studios.

---

## Motivation

Everyone knows how interconnected 21st-century life is and the ubiquity of the internet. There's no privacy in this current century. You can’t even communicate privately with your friend by bypassing the network service provider or a 3rd person who is interested in you with the traditional way of communicating channels. So I planned to design and develop a device using the LoRa E5 SOC from the Seeed Studios which can establish a secure communication channel where the 3rd person can’t even predict the frequency of the channel that you are using to communicate. Yes, it’s retro time, This device is something like a two-way pager with advanced features like live navigating and sharing location, altitude, and attitude but has a limited range in the order of very few hundred meters.

---

## Hardware Features

The following are the **Hardware features** of first version of the directMessage (hereinafter referred as "dM").

- **Display :** 1.8” LCD display (ST7735) have been used as the user interface with the dM. This display communicates with the Lora E5 MCU over the SPI communication protocol.

- **Vibration Motor :** Surface Mount Vibration Motor that vibrates when the device have something to notify the user.

- **Location sharing :** POT GPS module (Quectel L80) have been used for the location acquisation of the user. This module has very less power consumption (in the order of 20mA) during both acqisition and tracking. This also has a reacquisition time of less than 1sec which makes dM acquire the user loaction very quick (nearly 1 sec).

- **Lora chatting :** peer-to-peel local communication channel can be created using the LoRa P2P feature to establish Lora chatting.

- **Altitude :** Pressure sensor (BME280) will be used as an altimeter. The same sensor can be used to measure the Humidity.

- **Attitude :** 9DOF IMU (MPU9250) is used to measure the attitude of the device. User can view the roll, pitch, and yaw of the dM's over the display. The same IMU has the accelerometer, 

## PCB top & bottom layer

<p align = "center">
    <img src="Images\toplayer.png" alt="toplayer" height="500"/>
    <img src="Images\bottomlayer.png" alt="bottomlayer" height="500"/>
</p>

## Device Front & Back view

<p align = "center">
    <img src="Images\front.png" alt="front" height="500"/>
    <img src="Images\back.png" alt="back" height="500"/>
</p>
