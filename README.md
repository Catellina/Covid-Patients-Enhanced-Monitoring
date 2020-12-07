# Covid-Patients-Enhanced-Monitoring
NUS EE2028 final assignment: Covid Patients Enhanced Monitoring. An Armv7-M project written by NUS electrical engineering undergraduates: Yi Ming and Feng Yuanyuan.
<br/>

## Hardware Requiremants
* ARMv7-M Architecure
<br/>

## Software Environment
* STM32CubeIDE 1.4.0
<br/>

## Detailed description
* Sensor used<br/>
  ACCELEROMETER: 3D accelerometer LSM6DSL
  GYROSCOPE: 3D gyroscope LSM6DSL
  HUMIDITY_SENSOR: capacitive digital sensor HTS221
  TEMPERATURE_SENSOR: capacitive digital sensor HTS221
  LED: Green LED2
  MAGNETOMETER: high-performance 3-axis magnetometer LIS3MDL
  PRESSURE_SENSOR: 260-1260 hPa absolute digital output barometer LPS22HB
  MODE_TOGGLE & WARNING_CLEAR: USER Button (blue), read using interrupts
  CHIPACU: Terminal program (Tera Term) on a personal computer/laptop displaying Telemetry
  DEBUG_DEBUG_CONSOLE: The debug DEBUG_CONSOLE in STM32CubeIDE where printf() and other messages appear. These messages have to be disabled as soon as we start using CHIPACU
  WIFI/BLUETOOTH: Telemetry messages to the cloud via WiFi/Bluetooth (This is not confirmed. We will give you more details later, in case WiFi/Bluetooth is made a requirement.     This shouldn't affect your design/programming at this point of time.)
