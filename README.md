# 🩸 Rakta-Vahini AI

Rakta-Vahini AI is an Android healthcare application built using Kotlin + Jetpack Compose for blood donation and emergency blood request management.

## Features

### 🩸 Blood Donor Registration
- Donor registration form
- Store donor details:
  - Name
  - Email
  - Phone
  - Blood Group
  - District

### 🔍 Search Donor
- View registered donors
- Filter donors by blood group
- Show:
  - Name
  - Blood Group
  - Phone
  - District
  - Email

### 🚨 Emergency Blood Request
- Raise emergency blood requests
- Emergency feed support

### 🤖 AI Blood Assistant
- Blood donation assistant
- Healthcare guidance

### 🌍 Multi Language Support
Supported languages:
- English
- Kannada
- Hindi

### 🗺 Donor Map
- Donor location support

### 🏆 Ranking System
- Donor ranking page

---

# Tech Stack

- Kotlin
- Jetpack Compose
- Firebase Authentication
- Firebase Realtime Database
- Firebase Firestore
- Navigation Compose
- Room Database
- OkHttp

---

# Project Structure

```plaintext
com.raktavahiniai
│
├── model
│   └── Donor.kt
│
├── repository
│   └── DonorRepository.kt
│
├── navigation
│   ├── AppNavigation.kt
│   └── NavRoutes.kt
│
├── ui
│   └── screens
│       ├── login
│       ├── register
│       ├── donor
│       ├── home
│       ├── emergency
│       ├── request
│       ├── ai
│       └── profile
