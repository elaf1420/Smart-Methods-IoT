# Smart-Methods-IoT
Smart-Methods summer training program 2021 - (Internet of Things)
Table of Contents
- about
- Task 1 : chat bot 
- Task 2 : ESP32 Algorithm 
- Task 3 : Web Serial 
- Task 4 : move_arm_speech
- Task 5 : Programming control panels
## About this repository  :
This repository includes my work on the IoT track during my training program at Smart Methods Company
## task 1 : Programming voice chat systems ( chat bot ) 
In this task, the audio is heard in the Arabic language and converted into written speech, and codes that work on this are attached to the files.
## task 2 : Wasdom ESP32 segment operation algorithm 
1. Download the Aurdino IDE
2. We add from the boards a link ESP32
3. We download the ESP32 board
4. After downloading the ESP32, we connect the ESP32 piece to a USB cable
5. When you turn on the ESP light, we go to Examples, then BASICS, then BLINK
6. Play Hardwie Connected with Web API
## Task 3 : Web Serial 
WebSerial is a Serial Monitor for ESP8266 & ESP32 Microcontrollers that can be accessed remotely via a web browser. Webpage is stored in program memory of the microcontroller.
![](![web1](https://user-images.githubusercontent.com/108503091/182034345-ae01e214-9819-4685-9f50-79e31ac1c280.png)
)
# Upgrade to Pro
Checkout the Pro version of the WebSerial library which comes with enhanced & snappy UI, along with 'clear' & 'lock scroll' buttons on the monitor interface. Best of all, it's only 10KB in size compared to 50KB of regular WebSerial.
# Features
- Works on Websockets
- Realtime logging
- Any number of Serial Monitors can be opened on the browser
- Uses Async Webserver for better performance
# How to Install
Directly Through Arduino IDE
Go to Sketch > Include Library > Library Manager > Search for "WebSerial" > Install

Manual Install
For Windows: Download the Repository and extract the .zip in Documents>Arduino>Libraries>{Place "WebSerial" folder Here}

For Linux: Download the Repository and extract the .zip in Sketchbook>Libraries>{Place "WebSerial" folder Here}



Manually through IDE
Download the Repository, Go to Sketch>Include Library>Add .zip Library> Select the Downloaded .zip File.
# Contributions
Every Contribution to this repository is highly appriciated! Don't fear to create pull requests which enhance or fix the library as ultimatly you are going to help everybody.

If you want to donate to the author then you can buy me a coffee
# License
WebSerial is licensed under General Public License v3 ( GPLv3 ).

## Task 4 : move_arm_speech
use javascript seral port and speech to move robot arm
# command
if you have servo you can test the script connect the servo to pin 8 and write this command in seral monitor
> left@
right@
top@
make sure the baudrate is 115200
## Task 5 : Programming control panels
# start 
> php -S 127.0.0.1:8080
# request
> curl  http://localhost:8080/index.php/numbers/list\?limit\=20  
# for post request
> curl --location --request POST 'http://localhost:8080/index.php/numbers/post' \
--form 'number="150"'

## Implemented using :
- HTML-CSS-JS
## Resources :
- https://www.w3schools.com

