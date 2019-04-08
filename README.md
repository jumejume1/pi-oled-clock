# pi-oled-clock
Raspberry Pi OLED 0.96" 128x64 I2C Display Clock current date and time

How to setup OLed 128x64 I2c Library for Raspberry Pi Video tutorial
https://youtu.be/uJRpIqpYeL8

Adafruit  Python OLED Display SSD1306 Library
https://github.com/adafruit/Adafruit_...

Install library command
sudo python -m pip install --upgrade pip setuptools wheel

git clone 
https://github.com/adafruit/Adafruit_...

cd Adafruit_Python_SSD1306

sudo python setup.py install

type the following command to see all the connected devices i2c
sudo i2cdetect -y 1
