# Sensors
C-Code with basic functions to communicate with several sensors



Basic functions to use a Si7020 I2C temperature and humidity sensor.

Tested with MSP430F5x and MSP430G2x Microcontrollers.

Implemented functions:

//Use heater for defined time with specified current void si7020_heat(uint8_t current, uint32_t ms);

//Read Humidity (in %) uint8_t si7020_getHum();

//Read Temperature (in °C*100) int16_t si7020_getTemp();
