# Cybersecurity : CSN150
Project: ESP32 WiFi Scanner

## Purpose
Set up the ESP32-CAM and Arduino environment. Upload and execute the WiFiScanner sketch to detect nearby Wi-Fi networks and analyze signal strength (RSSI).

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation and tools

##### Video 1: 

##### Other Links: 

##### AI GPTs used: ChatGPT

## Steps I followed
1. Connected the ESP32-CAM using a USB data cable.
2.Opened Arduino IDE and selected the ESP32 board.
3.Loaded the WiFiScanner example sketch.
4.Uploaded the sketch to the ESP32-CAM.
5.Opened Serial Monitor to view scan results.
6.Recorded the number of networks detected, strongest signal, and RSSI values.

## Problems and Solutions.
**Problem:** The ESP32-CAM could not detect or communicate with the camera module. Because of this, the board failed to start the camera correctly and showed an error saying the camera was not found. 

**Solution:I fixed the problem by checking the camera connection and making sure the ribbon cable was fully seated and facing the right direction. After reconnecting it properly and restarting the ESP32-CAM, the camera was detected correctly and the error went away.
## Final Report
