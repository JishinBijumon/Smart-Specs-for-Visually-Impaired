# Third year mini project by our team- NEXUS4

# Smart Specs for the Visually Impaired

This is a wearable device built using the ESP32-CAM to assist visually impaired people by detecting nearby objects and announcing them through audio feedback.

## 👓 Features

- Real-time object detection using ESP32-CAM
- Audio output for detected objects
- Battery-powered wearable design
- Alerts the user

## 🔧 Hardware Used

- ESP32-CAM
- Rechargeable Li-ion Battery(3000Mah)
- Charging module (TP4056)
- Booster module(MT3608)
- Mini Audio Amplifier (MAX98357A)
-  Speaker(4ohm 5W)
- OLED Display (optional)

## 💻 Software & Tools

- Arduino IDE
- Edge Impulse (for object detection model)
- GitHub
- Libraries used:
  WiFi.h 
 WebServer.h (or ESPAsyncWebServer.h) 
 esp_camera.h
 esp_timer.h etc..


## 🛠️ How It Works

1. The ESP32-CAM captures video input.
2. A custom-trained model detects objects in real-time.
3. The detected object's name is sent to an amplifier and played through a speaker.

## 📈 Future Enhancements:

Raspberry Pi Integration for enhancing processing power, enabling real-time object detection, facial recognition, and OCR-based text reading.

Integration with ultrasonic or LiDAR sensors for depth perception.

Uses YOLO, Edge Impulse, and cloud-based AI for better accuracy and real-time scene understanding.

Bluetooth connectivity for real-time updates via smartphone.

Onboard AI for enhanced scene understanding and environment description.

Converts Braille text into speech using OCR and multilanguage text-to-speech(TTS).

GPS Navigation for providing voice-guided directions, obstacle alerts, and emergency SOS features for out-door mobility

## 🙏 Acknowledgements
Special thanks to our guide Prof.Agi George and Ms. Therese Yamuna Mahesh for constant support and technical mentorship throughout this project.
