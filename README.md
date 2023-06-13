Density Based Traffic Light Controller Using Arduino

The working of the project is divided into three steps

If there is traffic at all the signals, then the system will work normally by controlling the signals one by one.
If there is no traffic near a signal, then the system will skip this signal and will move on to the next one. For example, if there is no vehicle at signal 2, 3 and currently the system is allowing vehicles at signal 1 to pass. Then after signal 1, the system will move on to signal 4 skipping signal 2 and 3.
If there is no traffic at all the 4 signals, system will stop at the current signal and will only move on the next signal if there will be traffic at any other signal.

The components used for this project are as follows

Arduino Mega 2560
4 X HC-SR04 ultrasonic sensors
4 X Red LEDs
4 X Green LEDs
4 X Yellow LEDs
12 X 220 ohm resistors
Jumper cables
Breadboards
