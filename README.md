# Notes for ESP23-cam

## USB TTL connection:
https://i1.wp.com/dronebotworkshop.com/wp-content/uploads/2020/05/ESP32-CAM-hookup.jpeg?w=768&ssl=1

- **FTDI** connections (set to 5V)
- VCC to 5V
- TX to U0R
- RX to U0T
- GND to GND

Rather use 5V and switch from 3.3V input to the ESP32 to the 5V input on the other side (pin 0)

## Brownout prevention
Add a 10uF cap across the powersupply

## Arduino IDE
- Board URL at https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json.
- Board is: `AI-Thinker ESP23-cam`
