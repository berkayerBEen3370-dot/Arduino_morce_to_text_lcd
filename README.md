# Arduino_morce_to_text_lcd
Arduino and I2C LCD based Morse code translator
# 📻 Arduino Morse Code Decoder with I2C LCD

This project is an Arduino application that continuously decodes Morse code (dots and dashes) entered using two buttons, converts it into characters, and displays it on an I2C LCD screen.

## Attributes
- Button 1: Dashes (`-`) appends. (Turns on red led).
- Button 2: Dot (`.`) appends (Turns on blue led).
- Pressing Two Buttons Simultaneously: Cleans memory and screen.
- Auto Decode: If the button is not pressed for 1 second, it converts Morse code to letters.
- Software Debounce :Prevents multiple detections when the button is pressed.

## Used Compenets:
- Arduino Uno
- 16x2 I2C LCD Screen
- 2x Push Button
- 1x common catode RGB led
- 2x 220Ω Resistors
- Some jumper wires
