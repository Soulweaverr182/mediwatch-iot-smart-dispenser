# MediWatch & Smart Medicine Dispenser Ecosystem

An integrated IoT healthcare solution designed to automate medication adherence and provide real-time patient telemetry. The system combines an ESP32-based wearable smartwatch, an automated pill-dispensing unit, and an Android mobile application for clinical and caregiver oversight.

---

## System Architecture

Wearable Node (ESP32) --> BLE gateway --> Android App --> Wi-Fi / MQTT --> Smart Dispenser

---

## Tech Stack & Hardware

* Firmware: ESP32, C, C++, BLE, FreeRTOS
* Mobile: Android (Java/Kotlin BLE GATT API)
* Dispenser: Stepper/Servo Motor Dosage Control & Sensor Validation

---

## Contributors

* Pavel De La Rosa
* Isaí Mojica
* Wenerr Pacheco
