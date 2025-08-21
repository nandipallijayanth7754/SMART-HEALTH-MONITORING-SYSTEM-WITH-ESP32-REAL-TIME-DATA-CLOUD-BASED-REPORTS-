# Smart Health Monitoring System with ESP32  
**Real-Time Data & Cloud-Based Reports**

##  Project Overview
This project presents the design and development of a **Smart Health Monitoring System** using the **ESP32 microcontroller**. The system continuously measures and monitors key health parameters such as:

-  Heart Rate  
-  ECG (Electrocardiogram)  
-  SpO₂ (Oxygen Saturation)  
-  Body Temperature  
-  Room Temperature & Humidity  

All collected data is processed in real-time and transmitted to a **cloud platform** via Wi-Fi for secure storage, analysis, and visualization. The platform also supports **remote monitoring**, automated reports, and health trend analysis.

---
##  Circuit Diagram
Below is the **circuit connection diagram** of the Smart Health Monitoring System:  

---

![Circuit Diagram](circuit(2).png)

##  Objectives
- Provide **low-cost, portable, and efficient** health monitoring.  
- Enable **real-time tracking** of vital signs.  
- Store and analyze data on the **cloud** for accessibility.  
- Support **telemedicine and remote healthcare applications**.  
- Trigger **alerts** in case of abnormal readings.  

---

##  Components Used
- **ESP32 Dev Board** – main controller (Wi-Fi + Bluetooth enabled)  
- **AD8232 ECG Sensor** – ECG signal acquisition  
- **MAX30102 Pulse Oximeter** – Heart rate & SpO₂ measurement  
- **Pulse Sensor** – Heartbeat monitoring  
- **DS18B20 Temperature Sensor** – Body temperature  
- **DHT11 Sensor** – Humidity and ambient temperature  
- **16x2 LCD / OLED Display** – Displaying real-time values  
- **Cloud Platform** – ThingSpeak  

---

##  System Architecture
1. **Data Acquisition** – Sensors collect health parameters.  
2. **Processing** – ESP32 filters, processes, and analyzes signals.  
3. **Display** – Real-time readings shown on LCD/OLED.    
4. **Cloud Storage** – Data sent to cloud for monitoring & reports.  
5. **Remote Access** – Doctors/guardians can track patient health remotely.  

---

##  Features
- Continuous **real-time monitoring** of health vitals.  
- **IoT integration** for remote healthcare.  
- **Automated medical reports** & **diet suggestions**.  
- **Low power consumption** with ESP32 deep sleep modes.  
- **Affordable & scalable** for personal and clinical use.  

---

##  Results
- Accurate monitoring of ECG, SpO₂, heart rate, and temperature.  
- Successful transmission of data to cloud dashboards.  
- Remote visualization of health trends through **graphs and reports**.  
- Automated medical reports & diet suggestions.
---

##  Future Scope
- Integration with **mobile app dashboards** for patient & doctor use.  
- AI/ML algorithms for **early disease prediction**.  
- Support for **wearable devices** (smart bands/watches).  
- Enhanced **data security & privacy measures**.  

---

##  Author
**Nandipalli Jayanth Prasad**  
Electronics & Communication Engineering  
Sanketika Vidya Parishad Engineering College  

---

