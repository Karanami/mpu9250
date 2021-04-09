# MPU9250 9-axis Inertial Measurement Unit

![Licence](https://img.shields.io/badge/License-GPL--3.0-orange)

The MPU-9250 is a 9 degree of freedom (DOF) inertial measurement unit (IMU) used to read acceleration, angular velocity, and magnetic field in all three dimensions.

 ## InvenSense MPU9250 IC Pinout
![Sensor](https://i.pinimg.com/originals/81/bf/30/81bf303177cdc60588ac92b4c350f6c4.png)

## Application Notes
- SCL and SDA buses must be pulled up to 3.3V rail with 4.7k resistor before using it. Otherwise device cannot be accessed!
- Device address can be changed due to AD0/SDO pin state.
    - `0xD0` when AD0 grounded.
    - `0xD2` when AD0 pulled to VDD.


## About
This library is created for STM32 development environment and can be used only with STM32F series microcontrollers. Example files will be added soon.



License
----

GNU General Public License v3.0
