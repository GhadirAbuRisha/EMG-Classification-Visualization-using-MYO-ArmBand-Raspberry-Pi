# This Project is Created on Raspberry-Pi Using MYO ArmBand with Open-Myo
Python module to get data from a Myo armband using a generic Bluetooth LE interface.

## Installation and usage of [Open-MYO](https://github.com/Alvipe/Open-Myo)

This module works with generic Bluetooth LE antennas (e.g. CSR V4.0, Cambridge Silicon Radio or the Bluetooth interface integrated in the Raspberry Pi 3/Raspberry Pi Zero W). This module does not work with the Bluetooth antenna included with the Myo armband because it uses a propietary protocol from Bluegiga. 

This module requires the [bluepy](https://github.com/IanHarvey/bluepy) Python module to work. To install it, run:

``$ sudo pip install bluepy``

All code using the bluepy module must run with root permissions. To run the example code, execute:

``$ sudo python GP.py``

The Open Myo module **only works on Linux**, as the bluepy module is only available for Linux.

## Installation  PyQt4
 ```python
 sudo apt update
 sudo apt install pyqt4-dev-tools
 ```
### Screenshots
![GitHub Logo](https://github.com/hananabilabd/EMG-Classification-Visualization-using-MYO-ArmBand-Raspberry-Pi/blob/master/screenshot1.PNG)
![](https://github.com/hananabilabd/EMG-Classification-Visualization-using-MYO-ArmBand-Raspberry-Pi/blob/master/screenshot2.PNG)
![alt text](https://github.com/hananabilabd/EMG-Classification-Visualization-using-MYO-ArmBand-Raspberry-Pi/blob/master/screenshot3.PNG)
