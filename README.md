# lcduino
Adafruit sells a variety of LCD screens for the Arduino Uno microcontroller, but the documentation for the 18-pin LCD screen is not as good as that for the 16 pin. This repo should help you wire it and get an image running on the screen.

[Adafruit tutorial](https://learn.adafruit.com/character-lcds/rgb-backlit-lcds)


## Setup
You'll obviously need an Arduino board, the 18 pin LCD screen, a 3-pin potentiometer and the Arduino software on your computer. Using the wiring diagram below, connect the screen to the Arduino, as shown below:

### Fritzing Wiring Diagram
![Fritzing Diagram](https://github.com/mitchpehora/lcduino/blob/master/lcduino_bb.jpg?raw=true)

### Adafruit Wiring 
![Adafruit Wiring](https://github.com/mitchpehora/lcduino/blob/master/lcds___displays_rgblcdtest_t.jpg?raw=true)

From there, you're good to add the hello_world_18lcd_rgb.ino sketch located in the main folder to your Arduino.

## Other Programs
Each of the folders in the main repo represent a different program that I've written for the Arduino that takes advantage of
the LCD Screen. Click on them to get more info.
