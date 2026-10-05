# room sensor

A small room sensor that reports temperature and humidity over Wi-Fi.

Parts: ESP32-C6-WROOM-1 module, SHT41 for temperature and humidity, a USB-C receptacle for power and flashing, one addressable status LED, and a tactile button on BOOT.
Power: USB-C 5 V to 3V3 through an LDO, no battery.
Interfaces: I2C to the SHT41, USB-C data to the module's native USB pins, a 4-pin debug header exposing UART.
Constraints: two layers, under 50 by 50 mm, all parts on the top side, JLCPCB basic parts where possible, and keep the antenna keepout clear of copper.
