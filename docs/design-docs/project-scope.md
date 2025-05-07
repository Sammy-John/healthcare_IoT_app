# 📦 Project Scope

## ✅ In Scope

- A Raspberry Pi micro-server to collect and process health-related IoT sensor data.
- A web-based dashboard designed with accessibility and responsive layout in mind.
- Voice interaction for hands-free access to personal health metrics.
- Integration of direct health monitoring devices (e.g., temperature, heart rate).
- Foundational support for future integration with ambient sensors (e.g., fridge, shower) for behavioral monitoring.

``` HIPPA Compliant```

## 🚫 Out of Scope (for MVP)

- Integration with Electronic Health Records (EHR) or insurance platforms.
- Clinical certification or use of medical-grade sensors.
- Full implementation of a distributed multi-user system.
- Native mobile app or smart TV app deployment (only browser-accessible for now).
- Real-time cloud synchronization — all data is processed locally for MVP.

## 🧩 Sensor Overview

ConnectedCare interacts with a variety of IoT-enabled devices to support real-time health monitoring and behavioral analysis. Sensors fall into two primary categories: direct health devices and ambient activity sensors.

### 🏥 Direct Health Monitoring Devices

| Sensor Type             | Data Tracked            | Use Case |
|-------------------------|-------------------------|----------|
| Pulse Oximeter          | SpO₂, Heart Rate        | Respiratory health monitoring |
| Blood Pressure Monitor  | Systolic/Diastolic BP   | Hypertension tracking |
| Glucose Monitor (CGM)   | Blood Glucose           | Diabetes management |
| Smart Thermometer       | Body Temperature        | Infection detection |
| ECG Patch               | Heart Rhythm            | Cardiac health |
| Fall Detector           | Sudden Movement         | Emergency alerting |
| Smart Scale             | Weight Trends           | Nutritional or fluid retention tracking |

---

### 🏠 Daily Activity Sensors (Ambient Home IoT)

| Sensor Type             | Purpose                          | Insight Gained |
|-------------------------|----------------------------------|----------------|
| Fridge Door Sensor      | Tracks food access               | Skipped meals or confusion |
| Shower/Water Sensor     | Monitors hygiene routines        | Signs of neglect or memory lapses |
| Toilet Flush Sensor     | Bathroom activity monitoring     | Dehydration, routine patterns |
| Smart Kettle or Stove   | Tracks meal prep activity        | Meal consistency |
| Bed Pressure Sensor     | Sleep activity tracking          | Sleep patterns, restlessness |
| Entry/Exit Sensor       | Detects unusual exits/wandering  | Cognitive health and safety |
| Motion Sensors          | Room usage and movement patterns | Changes in mobility or habits |

---

### 🧠 Behavioral & Routine Data

In addition to sensor inputs, ConnectedCare may also gather behavioral and usage data to support early detection of cognitive or health changes. These metrics are passive, privacy-conscious, and designed to enhance insight without invasive monitoring.

| Source                  | Data Tracked                     | Application |
|-------------------------|----------------------------------|-------------|
| Voice Assistant Usage   | Frequency, repetition            | Signs of cognitive decline or memory lapses |
| UI Interaction Logs     | Errors, navigation patterns      | Tracks digital literacy and short-term memory issues |
| Smartwatch Integration  | Steps, sleep, HR variability     | Physical activity, energy levels, sleep quality |
| Geofencing (Optional)   | Room-to-room movement            | Wandering, inactivity, or behavior anomalies |
| Medication Dispenser Logs | Usage timestamps              | Prescription adherence tracking |

### For privacy and ethical handling of this data, see [Assumptions and Constraints](./assumptions-and-constraints.md)


