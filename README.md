# CS-360-AccelerometerApp
Android app that uses the device accelerometer via SensorManager to display real-time X, Y, and Z motion values using Kotlin and Jetpack Compose.
# Accelerometer App 📱

This Android application demonstrates how to use the **SensorManager** to access and display real-time accelerometer data. The app reads motion values along the X, Y, and Z axes and updates the UI dynamically using Jetpack Compose.

---

## 📌 Features
- Real-time accelerometer tracking
- Live updates of X, Y, and Z axis values
- Built using Android SensorManager
- Jetpack Compose UI
- Lifecycle-aware sensor registration

---

## ⚙️ How It Works

The app uses Android’s `SensorManager` system service to access the device’s built-in accelerometer sensor. A `SensorEventListener` is registered to listen for changes in motion data.

Whenever movement is detected, the `onSensorChanged()` method updates the UI in real time with the latest sensor values.

---

## 🧠 Concepts Demonstrated
- SensorManager usage
- Accelerometer sensor integration
- SensorEventListener implementation
- Real-time UI updates with Jetpack Compose
- Activity lifecycle management (`onResume`, `onPause`)

---

## 📊 Use Cases
- Fitness tracking apps (step/motion detection)
- Mobile games using tilt controls
- Motion-based security or detection apps
- Educational sensor data visualization

---

## 🛠️ Tech Stack
- Kotlin
- Android SDK
- Jetpack Compose
- SensorManager API

---

## 🚀 Author
Created as part of SNHU CS 360 Mobile Architecture & Programming coursework.
