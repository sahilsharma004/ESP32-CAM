# ESP32-CAM
This project creates a real-time video streaming server using an ESP32-CAM module (AI Thinker) and displays the live feed over a web browser.

🚀 Features
Live MJPEG video stream from ESP32-CAM

Accessible over Wi-Fi

Works with AI Thinker model

🔧 Requirements
ESP32-CAM (AI Thinker)

Arduino IDE

USB to Serial FTDI adapter

Wi-Fi Network

🔌 Wiring for Upload Mode
Connect GPIO 0 to GND

Press RESET button before uploading code

📡 WiFi Setup
Update these lines in the code:

const char* ssid = "YOUR_SSID";
const char* password = "YOUR_PASSWORD";

💻 Usage
Upload the code to ESP32-CAM.

Open Serial Monitor at 115200 baud.

Find the IP address shown.

Open that IP in your browser to view the live stream.
