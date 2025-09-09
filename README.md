# Neopixel Ring with Sound Sensor

## Description
This project uses a 24-LED Neopixel ring and a sound sensor to create a dynamic light display. The LEDs display a continuous rainbow pattern, and their brightness increases in response to detected sounds.

## Components Used
- 24-LED Neopixel Ring
- Arduino Board
- Sound Sensor Module
- Jumper Wires
- USB Cable

## Circuit Diagram
The circuit was designed using Tinkercad. Since the platform does not support sound sensors, a temperature sensor was used as a placeholder.

![image](https://github.com/user-attachments/assets/971a7b15-2a13-44e8-95bf-d69d412a1c94)

## Code Functionality
The code generates an infinite rainbow animation using the HSV color space. The brightness of the LEDs is normally low but increases when the sound sensor detects noise above a certain threshold.

### First Version
- LEDs display a rainbow animation.
- When sound is detected, the brightness increases significantly.
- This version creates a chaotic but visually appealing effect.

### Second Version
- Introduces a structured effect where an independent white LED follows the rainbow when sound is detected.
- Includes a startup animation where LEDs light up sequentially when the program starts.

## Demonstrations
Several demo videos were created using different songs to showcase the LED effects in action (View videos in pptx file).



