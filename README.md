# 🌡️ Digital Temperature and Humidity Display

An Arduino-based project that measures real-time temperature and humidity using a **DHT22 sensor** and displays the readings on a **16x2 LCD**.

## 📌 Features

- 🌡️ Real-time temperature monitoring
- 💧 Real-time humidity monitoring
- 📺 Live display on a 16x2 LCD
- 🔄 Automatic updates every 2 seconds
- 🛠️ Beginner-friendly Arduino project

## 🛠️ Components Used

- Arduino Uno
- DHT22 Temperature & Humidity Sensor
- 16x2 LCD (HD44780)
- Jumper Wires
- Breadboard (optional)

## 🔌 Circuit Connections

### DHT22

| DHT22 | Arduino Uno |
|--------|-------------|
| VCC | 5V |
| GND | GND |
| DATA | Digital Pin 8 |

### 16x2 LCD

| LCD Pin | Arduino Uno |
|---------|-------------|
| VSS | GND |
| VDD | 5V |
| VO | GND (or Potentiometer) |
| RS | Pin 12 |
| RW | GND |
| E | Pin 11 |
| D4 | Pin 5 |
| D5 | Pin 4 |
| D6 | Pin 3 |
| D7 | Pin 2 |
| A | 5V |
| K | GND |

## 📂 Libraries Required

Install the following libraries using the Arduino IDE Library Manager:

- DHT Sensor Library
- LiquidCrystal Library

## 🚀 How It Works

1. The DHT22 sensor measures the surrounding temperature and humidity.
2. Arduino reads the sensor values.
3. The readings are displayed on the 16x2 LCD.
4. The display refreshes every 2 seconds.

## 📸 Output

```
Temp: 28.5°C
Hum : 65.3%
```

## 💻 Software Used

- Arduino IDE
- Wokwi Simulator

## 📁 Project Structure

```
Digital-Temperature-and-Humidity-Display/
│
├── Digital-Temperature-and-Humidity-Display.ino
├── diagram.json
├── libraries.txt
├── README.md
└── LICENSE
```

## 🎯 Learning Objectives

- Learn Arduino programming
- Interface a DHT22 sensor
- Display sensor data on an LCD
- Work with external libraries
- Build beginner IoT projects

## 🔮 Future Improvements

- Add a buzzer for high-temperature alerts
- Add LEDs for temperature status indication
- Store data on an SD card
- Send data to the cloud using ESP8266/ESP32
- Display maximum and minimum temperature
- Add a cooling fan controlled by a relay

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a star!
