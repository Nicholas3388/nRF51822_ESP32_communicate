# nRF51822 sample

This is a sample to show how to create connection between ESP32 and 
nRF51822. In this sample, when ESP32 write to string "on"/"off" to 
the characteristic "6e400002-b5a3-f393-e0a9-e50e24dcca9e", which proviced 
by nRF51, the nRF51 device will turn on/off the LED on board.

The basic service UUID provided by the nRF51 device is 6e400001-b5a3-f393-e0a9-e50e24dcca9e

# Build

The project is built with Keil uVersion4. You can find the Keil project file 
within the following directory: `examples\ble_peripheral\ble_app_uart\pca10028\s110\arm4`
