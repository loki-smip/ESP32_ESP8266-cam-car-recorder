The ESP32 Cab modules code is made by s60sc and you can get the code from this link https://github.com/s60sc/ESP32-CAM_MJPEG2SD 

To flats ESP32 I have used esp Web Flasher you can find it in ESP32-CAM_MJPEG2SD Project which is the link above this is the link
https://ldijkman.github.io/async-esp-fs-webserver/ino/ESP32-CAM_Camera_Webserver/BIN/CAM-Flash.html to flash the esp32

To program the ESP8266 I have used Arduino Ide with the program given When I try to upload this program there was an error the websocket in the ESP8266 light berry was not there so I included in the repo

To control the esp8266 and see the camera footage from the ESP32 I have made a html web page which we have to open in the browser in the phone or computer

First we have to connect to the wifi network which the espa to 66 hosts and turn on the esp 32 and we have to include a ssid and password after flashing the ESP32 cam module connect to its Wi-fi and enter the username and password that you have entered in the esp8266 program after completing the process restart both of the modules they should connect to each other then we can use the html file to access both the camera feed and the esp8266 control panel
