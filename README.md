One ESP32 is going to be the server, and the other ESP32 will be the client.
 The BLE server advertises characteristics that contain sensor readings that the client can read.
 The ESP32 BLE client reads the values of those characteristics (temperature and humidity) and displays them on an OLED display.
