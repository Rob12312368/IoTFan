# IoTFan
I use LM35 to detect the indoor temperature. If it is above 31 degrees celsius, the fan turns on, and it shuts down when the temperature is below 31. The temperature is shown on a LCD.

# Goals
The fan turns on and off automatically based on a temperature threshold and can be cotrolled remotely.

# Tools
+ C++ (for writing code on ESP8266)

# Demo

In the video, I use my hand to heat up LM35 to make the temperature rise above 31 degrees celsius.


https://github.com/Rob12312368/IoTFan/assets/56261402/eb89abd0-070d-4816-ac78-f952f8b2c455



This image shows the fan turns on when the temperature is above 31.
![fan on](/images/fan_on.PNG)

This image shows the fan turns off when the temperature is below 31.
![fan off](/images/fan_off.PNG)
