# Make a Buzz Wire Game with an Arduino
 
- Arduino is very popular for building hobby projects and games, and we have previously used Arduino to build Snake game, Ping pong game, Space race game, etc. Today we are building one more popular game using Arduino- Buzz wire game or Steady hand game.

- For this project, we will use an Arduino Uno, Buzzer, and two Aluminum wires. A 16x2 LCD is also interfaced to display the game status. Both the ends of the maze wire will be connected to the digital pin 2 & 3 of Arduino, and the handle wire is connected to the Ground pin of Arduino. The digital pins are defined as INPUT_PULLUP pins. So when the handle wire touches the maze wire, it changes the digital pins state to low, and the buzzer makes a sound.

- A diode is connected at the end of the maze wire, so when you go past to that diode and touch the maze wire with round handle wire, only one pin (Pin 3) will go low. In that condition, a congratulation text (Well done) will be displayed on LCD.

- Components Required
- Arduino Uno
- Aluminium Wire
- 16x2 LCD
- I2C Module
- Breadboard
- Buzzer
- Diode
