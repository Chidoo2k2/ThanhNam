🌡️ SMART TEMPERATURE & HUMIDITY MONITORING APP
This Android application enables real-time monitoring of temperature and humidity, along with remote LED control using Firebase. It’s an ideal solution for smart home and IoT automation projects.
1. 🔥 FEATURES

📡 Real-time Monitoring: Track temperature and humidity from ESP32 sensors.
💡 Remote LED Control: Turn the LED on/off via the app interface.
☁️ Firebase Integration: Synchronize data with Firebase Realtime Database.
🏠 Smart Home Ready: Easily adaptable to IoT systems.

2. 📱 APP DEMO



App UI
Firebase Database
ESP32 & Sensor



[Displays temperature, humidity, and LED status]
[Stores temperature, humidity, and LED status data]
[DHT11/DHT22 sensor and LED]


🎥 Demo Video: Watch on YouTube📦 Download APK: Click to download
3. 🛠️ TECHNOLOGIES USED

Android: Kotlin, Jetpack Compose
Hardware: ESP32, DHT11/DHT22 sensor, LED
Firebase: Realtime Database
Arduino IDE: Integrated with Firebase library
Project Management: Gradle Kotlin DSL

4. ⚙️ HOW TO BUILD & RUN
4.1. Requirements:

Android Studio (Electric Eel or later)
Firebase project with Realtime Database enabled
ESP32 board, DHT11/DHT22 sensor, LED
Android device (API 21 or higher)

4.2. Steps:

Clone the repository:  git clone https://github.com/0862897614/smart-temp-humidity-app.git


Open the project in Android Studio (File > Open).
Connect to Firebase: Replace the google-services.json file with the one from your Firebase project.
Run the app on an Android device (API 21+).
Upload the ESP32 code from the ESP32SensorProject folder using Arduino IDE.

5. 🔌 HARDWARE CONNECTION TABLE



Component
ESP32 Pin



DHT11/DHT22 (Signal)
D4


LED (Anode)
D2


GND
GND


VCC (3.3V/5V)
3.3V


6. 📄 LICENSE
This project is licensed under the MIT License. Feel free to use and modify it with proper attribution.
