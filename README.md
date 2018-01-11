# Object-Tracking-Camera-System

A Guide to set up and run the project

==========================================================================================

1. Connect the webcam to laptop/desktop

2. Connect the Arduino to laptop/desktop

==========================================================================================

Run the following command in linux terminal.
3. roslaunch usb_cam usb_cam-test.launch

==========================================================================================

4. cd <Directory in which the code resides>

5. python computer_node.py

==========================================================================================

6. Upload Arduino code to board from Arduino IDE.

Run the command below in linux terminal
7. rosrun rosserial_python serial_node.py /dev/ttyUSB0 _baud:=57600

==========================================================================================

8. We're in business!!
