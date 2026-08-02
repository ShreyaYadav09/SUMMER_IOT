LED Blink Project
Project Title
LED Blink with Potentiometer Speed Control

Hardware Required
Arduino Uno
LED
220Ω Resistor
Potentiometer (10kΩ)
Breadboard
Jumper Wires
USB Cable
Circuit Diagram Description
Connect the LED anode (long leg) to Arduino pin 13 through a 220Ω resistor.
Connect the LED cathode (short leg) to GND.
Connect one side of the potentiometer to 5V.
Connect the other side of the potentiometer to GND.
Connect the middle pin (wiper) of the potentiometer to analog pin A0.
How to Upload Code
Connect the Arduino Uno to the computer using a USB cable.
Open Arduino IDE.
Open the led_blink.ino file.
Select Tools → Board → Arduino Uno.
Select the correct COM Port under Tools → Port.
Click the Upload button.
Open the Serial Monitor at 9600 baud to view the blink count.
Expected Output
The LED blinks continuously.
The potentiometer changes the blink speed.
The Serial Monitor displays:
Blink count: 1
Blink count: 2
Blink count: 3
Rotating the potentiometer makes the LED blink faster or slower.
Troubleshooting Tips
Check that the correct COM port and Arduino board are selected.
Verify all circuit connections, especially the LED polarity and potentiometer wiring.
Ensure the Serial Monitor baud rate is set to 9600.
