# ESP32 Smart Web Control

This is a simple IoT project using an ESP32 to control devices (like LEDs, doors, relays, etc.) through a web interface.  
The HTML and CSS files are stored in the SPIFFS filesystem of the ESP32.

##  Features
- Custom web UI served directly from ESP32
- Control devices (LEDs, relays) over Wi-Fi
- No need for internet connection (Access Point mode)
- Easily extendable to sensors or other modules


## 🛠 Requirements
- Arduino IDE
- ESP32 board with USB cable
- Libraries:
  - `ESPAsyncWebServer`
  - `AsyncTCP`
  - `SPIFFS`

##  How to Use
1. Open the `.ino` file in Arduino IDE.
2. Upload the `data/` folder to SPIFFS using the "ESP32 Sketch Data Upload" tool.
3. Upload the sketch to your ESP32 board.
4. Connect to the ESP32's WiFi Access Point (default: `ESP32-WIFI`).
5. Open browser and go to `192.168.4.1`.

##  Preview

##  License
This project is open-source under the MIT License.
