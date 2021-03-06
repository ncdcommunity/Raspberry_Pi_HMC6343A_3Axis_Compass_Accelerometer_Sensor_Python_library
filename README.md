[![HMC6343A](HMC6343A_I2C.png)](https://store.ncd.io/product/hmc6343-3-axis-compass-module-accelerometer-i2c-mini-module/).

# HMC6343A

The Honeywell HMC6343 is a fully integrated compass module that includes firmware for heading computation and calibration for magnetic distortions.The module combines three-axis magneto-resistive sensor, three-axis MEMS accelerometer, analog and digital support circuits, a microprocessor and algorithms required for heading computation.
This Device is available from www.ncd.io

[SKU: HMC6343A]

(https://store.ncd.io/product/hmc6343-3-axis-compass-module-accelerometer-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface HMC6343A 3Axis compass module accelometer sensor With Raspberry Pi :

1. <a href="https://store.ncd.io/product/hmc6343-3-axis-compass-module-accelerometer-i2c-mini-module/">HMC6343A 3Axis compass module accelometer sensor</a>

2. <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>

3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python

Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python HMC6343A.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
