






# Nodemcu-configuration-and-testing.


# Install ESP8266 NodeMCU Add-on in Arduino IDE 2.

1. In the Arduino IDE 2, go to File > Preferences.
2. 
![image](https://github.com/dennisngugiwambui/Nodemcu-configuration-and-testing/assets/112067611/3649a553-5221-45a0-a5f2-d01d866e3abf)


3. Copy and paste the following line to the Additional Boards Manager URLs field.

```http://arduino.esp8266.com/stable/package_esp8266com_index.json```

![image](https://github.com/dennisngugiwambui/Nodemcu-configuration-and-testing/assets/112067611/6ce345ce-2334-4ac5-a417-3971dc792360)


~if you already have the ESP32 boards URL, you can separate the URLs with a comma, as follows:

```http://arduino.esp8266.com/stable/package_esp8266com_index.json,```
```https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json```

3. Open the Boards Manager. You can go to Tools > Board > Boards Manager… or you can simply click the Boards Manager icon in the left-side corner.

![image](https://github.com/dennisngugiwambui/Nodemcu-configuration-and-testing/assets/112067611/0381d895-769f-4b1c-8509-ff64ad356821)

4. Search for ESP8266 and press the install button for esp8266 by ESP8266 Community

![image](https://github.com/dennisngugiwambui/Nodemcu-configuration-and-testing/assets/112067611/34975b63-d6e2-4ffd-9654-3b1e4140e234)


#Testing the Installation


```
void setup() {
  pinMode(D4, OUTPUT);
}

void loop(){
  digitalWrite(D4, HIGH);
  delay(1000);
  digitalWrite(D4, LOW);
  delay(1000);
}

```


# The output should look this way

![WhatsApp Image 2024-03-13 at 4 19 49 AM (1)](https://github.com/dennisngugiwambui/Nodemcu-configuration-and-testing/assets/112067611/2ed11c1a-be20-493d-bf64-5c5a8940f0bc)

![WhatsApp Image 2024-03-13 at 4 19 49 AM](https://github.com/dennisngugiwambui/Nodemcu-configuration-and-testing/assets/112067611/f7146970-03cc-4df4-86ba-f2c528782067)

![WhatsApp Image 2024-03-13 at 4 19 37 AM](https://github.com/dennisngugiwambui/Nodemcu-configuration-and-testing/assets/112067611/c3918e25-09b6-4ad1-8be9-85f1a8231094)



# You should also understand the GPIO pins of the esp8266 which are as follows

![image](https://github.com/dennisngugiwambui/Nodemcu-configuration-and-testing/assets/112067611/e3b166b2-5acb-470a-969e-774aa76d6b17)




