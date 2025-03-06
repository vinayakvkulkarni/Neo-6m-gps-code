# Neo-6m-gps-code
"Arduino Uno project for real-time GPS tracking using the Neo6M module. Captures and prints raw GPS data to the Serial Monitor via SoftwareSerial (pins 8 and 9). Developed in Arduino IDE."
"This Arduino Uno project reads live GPS data from the Neo6M GPS module using SoftwareSerial on pins 8 and 9. It forwards the raw GPS NMEA sentences to the Serial Monitor for real-time location tracking. Developed in Arduino IDE, with a baud rate of 115200 for monitoring and 9600 for GPS communication."
Here are the connections for your setup:

Neo6M GPS Module to Arduino Uno:

VCC → 3.3V or 5V (Check your module’s voltage rating)
GND → GND
TX → Pin 8 (RX of Arduino)
RX → Pin 9 (TX of Arduino)
Serial Monitor Settings:

Baud Rate: 115200
