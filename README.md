# Arduino Security System

This Arduino-based security system project allows users to input an ID using a keypad and verify it against a stored ID. It utilizes an Arduino board, a keypad, and an LCD display.

## Features

- Input ID using a 4x4 keypad.
- Display entered ID on a 16x2 LCD display.
- Compare entered ID with a stored ID.
- Give access according to the compared id using servo motor 
  

## Components Required

- Arduino board (e.g., Arduino Uno)
- 4x4 keypad
- 16x2 LCD display
- LED
- push Button
- servo Motor
- Jumper wires

## Installation and Setup

1. Connect components to the Arduino board according to the provided schematic.
2. Upload the Arduino code to the board using the Arduino IDE.
3. Power up the system.

## Usage

1. Enter the ID using the keypad.
2. Press push button 1 to confirm the entered ID.
3. If the entered ID matches the stored ID, the system will display Access Granted and the servo will rotate 90 degrees as a doo simulation
4. If the entered ID does not match the stored ID, the system will prompt you to enter a new ID.
5. You can use the second push button as delete key

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project is based on the Arduino keypad and LCD tutorials.
- This project is able to be edited and improved in  future to make it more interactive
- Thanks to the Arduino community for their valuable contributions.

## Author

Hadi Yaghi

