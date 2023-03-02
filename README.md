# ZumoSumo
Information for building a Zumo Sumobot

## Parts

The primary robot can be purchased from Pololu and several other resellers. This includes the sensors and a wedge.

[Purchase](https://www.pololu.com/product/2510)

To attach other accessories to the robot I recommend printing a lattice for easy attachment points. The STL and Fusion file can be found in the models folder.

[STL](/models/Sumobot%20Lattice%20v2.stl) | [Fusion](/models/Sumobot%20Lattice%20v2.f3d)


## Programming

The robots are programmed with the Arduino Uno. Its easiest to get started using [Arduino Create](https://create.arduino.cc/).

To talk to the sumo platform you will need an Uno, other Arduino boards are not fully compatible with the Pololu library.

You can find the Pololu library in Create by clicking the libaries tab and searching for ZUMOSHIELD.

### Basics

Sensor return an array of values reading from: 0 - white, 2000 - black, 200-400 white line, 700-900 red line. Each sensor can be address individually for left/right control.
