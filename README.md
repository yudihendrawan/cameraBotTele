# Camera Bot Tele
Camera Bot Telegeram Using ESP 32 Cam
is a program that can make your own CCTV camera at home, and also has a feature that will take a photo if there is movement using the __PIR__ sensor

---

# What You Need
- ESP32 Cam
- Pir Sensors
- Bread Board
- FTDI USB to TTL
- Jumper Cable
- Bot Telegram
  - Telegram bots can be made at @BotFahther and Chat ID can be obtained at @myidbot

# How to Use
* because the esp32 cam doesn't have a USB port then we need FTDI. Connect the FTDI to the esp 32 cam as shown.

<p align="center" width="100%">
    <img width="70%" src="https://user-images.githubusercontent.com/78086681/222943474-6b73fb47-329a-4d88-b8fc-c934ab8ba647.png"
"> 
</p>


| ESP32-CAM | FTDI     |
| --------- | ----     |
| GND       | GND      |
| 5V        | VCC (5V) |
| U0R       | TX       |
| U0T       | RX       |
| GPIO 0    | GND      |



* Upload the code file that is on [Source Code](https://github.com/yudihendrawan/cameraBotTele/blob/master/index.cpp).


```
const char* ssid = "...";  // your ssid wifi
const char* password = "..."; // your password wifi
```

```
String BOTtoken = "....."; // your Bot Token (Get from Botfather)
String CHAT_ID = "..."; // your ID chat
```

> after the upload process is complete, don't forget to unplug the `GPIO 0` `GND` cable and press restart button on ESP 32 Cam 

* Connect the FTDI to the esp 32 cam and PIR Sensors

<p align="center" width="100%">
    <img width="70%" src="https://user-images.githubusercontent.com/78086681/222945784-ef0296c3-f5b3-4f2c-984c-e081374aae46.png"
"> 
</p>

* open the telegram chat that you have made run / start

<p align="center"> display will be like this </p>

<p align="center" width="100%">
    <img width="20%" src="https://user-images.githubusercontent.com/78086681/222946090-1ee4c03c-3c8b-45f7-ada4-7256d90242d6.jpg"
"> 
</p>




<p align="center" > Happy Dizzy :grinning: </p>

