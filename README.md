Cre: https://github.com/MYusufY/lvgl-gemini.git

# ESP32 CYD with LVGL: Display Gemini
Chat with Gemini on ESP32-2432S028 CYD (cheap yellow display)
This project uses LVGL and Gemini API, its a simple AI project with ESP32-2432S028

## Examples:
![](https://github.com/MYusufY/lvgl-gemini/blob/main/examples/example_1.gif)
![](https://github.com/MYusufY/lvgl-gemini/blob/main/examples/example_2.gif)
## YouTube video:
[You can watch it here.](https://www.youtube.com/watch?v=O8mf3UPJdV8)

## My version:
![20250721_213804 (2)](https://github.com/user-attachments/assets/78441705-a1ab-4600-8fac-2659f7c5c71b)


# How to: Build and Upload!
## Setup Libraries
The requried libraries with their configuration files are given under the "arduino_lib" folder. Change the libraries path in platformio.ini file to the path of arduino_lib folder.

## Building & Uploading in Platformio (please clone the [authour github](https://github.com/MYusufY/lvgl-gemini.git))
1. Setup libraries like shown above. 
2. Open the "platformio_project" project folder in platformio.
3. Change your wifi ssid, password and api key settings in main.ino
4. Upload
5. Done!

## Building & Uploading in ArduinoIDE
1. Copy files in arduino libs into your library Sketchbook location, default in ~\Documents\Arduino\libraries
2. Open main.ino
3. Change your wifi ssid, password and api key settings in main.ino
4. Upload
5. Done

# What it does?
You can send messages to Gemini using the textarea on top of the screen, and get answers quickly!


