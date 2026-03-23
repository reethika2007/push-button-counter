<img width="1920" height="1080" alt="Screenshot (80)" src="https://github.com/user-attachments/assets/60898016-0076-4ad3-8360-8c65ff260a48" />*push button counter*
Task :push button counter 
Name :Reethika J A
Intern ID :CTIS6578
Domain :Embedded system
Description :
The Push Button Counter is an embedded system project designed using an Arduino microcontroller to count the number of times a push button is pressed. This system is simple, cost-effective, and widely used in applications such as digital counters, attendance systems, and industrial monitoring.
The main components used in this project include an Arduino Uno board, a push button, a 16x2 LCD display, resistors, a breadboard, and connecting wires. The push button acts as an input device, while the LCD display shows the count value. The Arduino serves as the brain of the system, processing input signals and updating the output accordingly.
When the push button is pressed, a signal is sent to the Arduino through a digital input pin. The Arduino is programmed to detect the state change of the button (from LOW to HIGH). Each time the button is pressed, the program increments a counter variable. This value is then displayed on the LCD screen in real time. Debouncing techniques may be used in the code to avoid multiple counts due to mechanical noise in the button.
The LCD display is interfaced with the Arduino using either parallel communication or I2C protocol. It continuously updates the current count value, providing a user-friendly interface. Proper connections and power supply ensure stable operation of the system.
The circuit is built on a breadboard, making it easy to assemble and modify. The push button is connected with a pull-down or pull-up resistor to ensure stable input readings. The Arduino is powered via USB or an external power source.
This project demonstrates fundamental concepts of embedded systems such as digital input handling, output display control, and basic programming logic. It is especially useful for beginners to understand how microcontrollers interact with hardware components.

