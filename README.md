
# 🌤️ Weather App 🇱🇷

A modern, intuitive, and responsive **weather forecast app** built with Flutter.  
It automatically detects the user’s location (with permission) and displays real-time weather data, including **hourly and weekly forecasts**.  
Also works offline by using locally cached data.

---

## 📸 Visual Demo

| Home Screen | Loading | Weekly Forecast | City Search |
|-------------|----------|-----------------|-------------|
| ![Screen 01](flutter_01.png) | ![Screen 02](flutter_02.png) | ![Screen 05](flutter_05.png) | ![Screen 07](flutter_07.png) |

---

## 📱 Features

- 📍 Automatic city detection via GPS  
- 🔍 Manual city search with validation  
- 🌡️ Current weather with animated icon & temperature  
- 📊 Extra details: humidity, pressure, wind speed  
- ⏱️ Hourly forecast with icons & temperature  
- 📅 Weekly forecast with min/max temperatures  
- 📦 Offline mode with local cache  
- 🎨 Dynamic gradient UI with smooth animations  
- 🧊 Search screen with glassmorphism effect  
- 💬 Fun facts & tips shown while loading  
- ⏳ Timeout alert if connection takes over 40s  
- ❌ Error screen with “Try Again” button  

---

## 🛠️ Tech Stack

| Technology         | Purpose                              |
|--------------------|--------------------------------------|
| Flutter            | Main framework                       |
| GetX               | State management & navigation        |
| GetStorage         | Local storage                        |
| Geolocator         | Device location access               |
| Geocoding          | Convert coordinates into city names  |
| Dio                | HTTP requests                        |
| Intl               | Date formatting                      |
| Google Fonts       | Custom typography                    |
| Weather Icons      | Themed weather icons                 |
| Mocktail / Mockito | Mocks for unit testing               |
| Integration Test   | Integration testing                  |
| CI/CD (Pipeline) | Build, test and release automation |

## 🧪 Automated Tests

- ✅ Unit tests with `flutter_test`, `mocktail`, `mockito`  
- 🧪 Integration tests with `integration_test`  
- 📊 Code coverage via `flutter test --coverage`  

---
[Download do APK](https://github.com/emanoelsg/weather_app/actions)


