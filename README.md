# TTbasic_Arduino_Zero
Modified version of Toyoshiki Tiny Basic supporting Arduino M0 (Atmel SAMD21G18A).
This program supports I2C OLED display output with serial key input.
New Arduino related command "dwrite" and "wait" are added.
"dwrite pin# 0 or 1" working pin# low or high.
"wait 100" will wait 100 ms, same as delay function of TinyBasicPlus.
Not only BASIC source, Adafruit_SSD1306 library related files should
be replaced with the files above for SAMD21G18A (Arduino M0) operation.
Also, please replace "samd21_device.c" in your Arduino cores directory
for correct serial operation.
