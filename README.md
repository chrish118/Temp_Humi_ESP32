# Temp_Humi_ESP32
# ESP32 Room Monitoring & IoT Dashboard System

A real-time room monitoring and IoT dashboard system built using an ESP32, DHT11 sensor, OLED display, and buzzer alert system.

The project measures temperature and humidity, displays the readings locally on an OLED screen, and hosts a live WiFi dashboard accessible through a browser.

---

# Features

- Real-time temperature monitoring
- Real-time humidity monitoring
- OLED display output
- WiFi-enabled web dashboard
- Automatic webpage refresh
- Buzzer alert system for high temperatures
- Live sensor integration
- HTML/CSS dashboard interface
- Fully documented project workflow

---

# Components Used

- ESP32
- DHT11 Temperature & Humidity Sensor
- SSD1306 OLED Display
- Active Buzzer
- Breadboard
- Jumper Wires

---

# Technologies Used

- Arduino IDE
- Embedded C++
- HTML/CSS
- WiFi Networking
- I2C Communication
- Git & GitHub

---

# Folder Structure

```text
01_ProjectLog      -> Daily development logs
02_Code            -> Arduino/ESP32 source code
03_Wiring          -> Wiring documentation
04_Photos&Videos   -> Project images and demo videos
05_TestingData     -> Testing results
06_FinalReport     -> Final report and reflections
```

---

# System Functions

## OLED Display
Displays:
- Temperature
- Humidity
- System status

## Web Dashboard
Displays:
- Live temperature
- Live humidity
- Alert status

Accessible through the ESP32 local IP address.

## Buzzer Alert
Triggers automatically when the temperature exceeds the predefined threshold.

---

# Key Concepts Learned

- ESP32 WiFi communication
- Local web server hosting
- Embedded systems workflow
- I2C communication
- Sensor integration
- Hardware debugging
- HTML/CSS integration with embedded systems
- GitHub project organization

---

# Challenges Faced

- OLED display distortion
- WiFi connectivity issues
- Browser refresh problems
- Sensor debugging
- Integrating multiple hardware outputs together

---

# Testing

System testing included:
- Temperature threshold testing
- Buzzer activation testing
- Web dashboard refresh testing
- OLED display verification
- Full system integration testing

---

# Future Improvements

- JavaScript live updates
- Responsive mobile dashboard
- Cloud data logging
- Graphs/charts
- Remote hardware control
- Better UI/UX design
- TFT display integration

---

# Project Outcome

Successfully developed a fully integrated ESP32-based room monitoring and IoT dashboard system capable of:
- monitoring environmental conditions
- displaying live local data
- serving data over WiFi
- generating alert notifications
- integrating hardware and web technologies together

---

# Note

This project was built as a practical learning project to improve understanding of embedded systems, IoT concepts, networking, debugging, and hardware/software integration.

I’m still learning embedded systems and C++, and used ChatGPT throughout the project as a learning/debugging assistant while making an effort to properly understand the logic, workflow, and hardware integration behind the system.