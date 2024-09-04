RGB LED Controller
This project allows you to control RGB LEDs using an ESP8266 microcontroller. The project includes both hardware and software components to create a versatile LED controller with various lighting effects.

Features
Solid Color Control: Set the RGB LEDs to a solid color.
Fade: Smoothly transition through colors.
Flash: Flash the LEDs in the selected color.
Rainbow Cycle: Cycle through a rainbow of colors.
Pulse: Create a pulsing effect with the selected color.
Strobe: Rapidly blink the LEDs with the selected color.
Blink: Blink the LEDs on and off.
Hardware
ESP8266 Microcontroller: Controls the RGB LEDs.
RGB LEDs: Connect to the ESP8266 and are controlled via PWM.
Software
The ESP8266 runs a web server that provides an interface to control the LEDs. The web interface allows you to:

Choose colors using a color picker.
Select different lighting modes.
Trigger various effects with a simple button press.
Installation
Clone the Repository:

sh
Copy code
git clone https://github.com/srijonbasak/RGB-LED-Controller.git
Upload the Code:

Open the RGB-LED-Controller.ino file in the Arduino IDE.
Select the ESP8266 board and port.
Upload the code to your ESP8266.
Connect to the ESP8266:

After uploading, connect to the ESP8266 Wi-Fi network named The IoT Projects.
Open a web browser and navigate to http://192.168.1.5 to access the web interface.
Web Interface
The web interface provides the following features:

Color Picker: Choose an RGB color to set for the LEDs.
Control Buttons: Apply various lighting effects by clicking the buttons.
Usage
Select a Color: Use the color picker to choose a color. The LEDs will change to the selected color.
Apply Effects: Click the buttons to apply different lighting effects.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
Created by Srijon Basak. Feel free to reach out with any questions or feedback.
