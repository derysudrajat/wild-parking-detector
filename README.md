# wild-parking-detector
Wild Parking Dector is IOT device which can detected vehicle tat stops carelessly Using ADXL 354 Acceleromater module and Wemos D1

## Setup
* Install [Adafruit ADXL 354 Module](https://github.com/adafruit/Adafruit_Sensor) or you can find it on Arduino IDE `Sketch > Include Library > Manage Libraries...` and search the libaray with key **"Adafruit"** and go to find library with name `Adafruit ADXL345 by Adafruit` and install it.
* Install [ESP8266 Board](https://github.com/esp8266/Arduino) which include Wemos D1 Board also, or or you can find it on Arduino IDE `Tools > Board > Boards Manager...` and find with key **"ESP8266"** and go to find board library with name `esp8266 by ESP8266 Community` and install it.
* Install [Firebase Arduino](https://github.com/FirebaseExtended/firebase-arduino) library for push and read data from Firebase, or you can find it on Arduino IDE `Sketch > Include Library > Manage Libraries...` and search the libaray with key **"Firebase"** and go to find board with name `FirebaseArduino` and install it.

## Configure
* Make sure you already install ESP8266 Board and select LOLIN (WEMOS) D1 R2 & mini for your main board
* Make Sure your port is Connected cek it on `Tools > Port` and select your active port

## Calibrate Sensor
* Download project in folder `main > detection > detection.ino` open it on Arduino IDE
* Upload code to Board and waiting until 100%
* Open serial monitor or serial plot to calibrate it by select `Tools > Serial Monitor` or `Tools > Serial Plot` make sure your upload serial is equal with on code is `9600 baud`

and Enjoy :)
