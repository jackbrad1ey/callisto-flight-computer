# Callisto (work in progress)
Callisto is a flight computer designed for usage in hobby rocketry. The PCB was designed using Altium designer and the firmware was written in Rust, with the novel combination being used as a means for me to become more familiar with the two.

Callisto features an RP2040 microprocessor to handle all onboard computation, an RFM95W LoRa module for radio communication with ground station and a GPS, barometer and IMU for sensing the location, orientation and speed of the vehicle.
It also includes a flash chip for the purpose of logging data from the mentioned sensors 

Additionally, connectors for two servo motors with optional feedback are included with the hope of the board being used in the future for developing a thrust vector controlled low powered rocket.
