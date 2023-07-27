# Stacker Arcade
 The "Stacker Arcade Game" is an exciting course project that aims to recreate the classic arcade game experience in a digital form using Arduino. The game is developed For Hardware design Course Project.

## Hardware Requirements
* Arduino Board (e.g., Arduino Uno)
* MAX7219 LED Matrix Display Module
* Breadboard and jumper wires
* Pushbuttons (at least two)
* Resistors (for button debouncing)
*  USB cable for Arduino power and programming
## Libraries Used
* LedControl.h
## Installation and Setup
1. Clone or download this repository to your local machine.
2. Install the LedControl library into your Arduino IDE. Instructions can be found in the library's documentation.
3. Connect the components as per the schematic diagram provided in the 'schematic' folder.
4. Connect your Arduino board to your computer using the USB cable and upload the sketch (main.ino) to the Arduino.
## How To Play
* In the beginning user can select level of game, which decides difficulty of the game. 
* For selecting the level user can press the key at desired level from a toggling menu.
* After selecting game shall start.
* you can use same push button to control glowing row 
* After game end user must be able to see their score, high score and level they were playing at.
## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
## Circuit Diagram 
A circuit diagrams is provided in the 'circuits' folder to help you wire the components correctly.
![matric circuit](https://github.com/s-brajendra/Stacker-Arcade/assets/80635193/a0bb59f7-6222-4c68-9b1c-bf47770ca5d3)

## Algorithm FlowChart
* Top Level

![top level](https://github.com/s-brajendra/Stacker-Arcade/assets/80635193/fa001a8c-5bc0-4ccf-a02c-136da1e44cc4)

* Set GameLevel
![set game level algo flow chart](https://github.com/s-brajendra/Stacker-Arcade/assets/80635193/52ac5807-3bac-4d0c-ac3b-778ca2f4a614)

* main gameplay
![main gameplay flowchart](https://github.com/s-brajendra/Stacker-Arcade/assets/80635193/f1192166-79f1-43c3-82c5-b7366c1d63c6)




## Acknowledgments
I am grateful to our instructor Dr Ribhu who guided 
me through the project. Also, I am thankful to modern 
technological advances which made gathering 
knowledge, debugging and procuring components very 
easy
## License
No need

