# 🚀 Time Tracking App (Flutter + Firebase)

A modern Time Tracking Application built using Flutter, Firebase, and Riverpod Architecture. This app helps users manage jobs, track work entries, and generate daily reports with real-time cloud sync.

## 📱 Preview

🌐 Live Demo (Web):
https://starter-architecture-flutter.web.app

## ✨ Features

* 🔐 User authentication (Email & Password)

* 🧭 Simple onboarding flow

* 💼 Job management (Create, Edit, Delete)

* ⏱️ Time entry tracking per job

* 📊 Daily reports with total hours & earnings

* 🔄 Real-time sync using Cloud Firestore

* 🧩 Clean architecture using Riverpod

## 🏗️ Tech Stack

* Flutter

* Firebase Auth

* Cloud Firestore

* Riverpod

* GoRouter

* RxDart

* Intl

## 📂 Project Structure
lib/
  * features/
  * services/
  * routing/
  * common_widgets/
  * utils/

Architecture follows Riverpod + Repository Pattern for scalability and maintainability.

## ⚙️ Getting Started
✅ Prerequisites

* Flutter SDK installed

* Firebase account

* Firebase CLI

* FlutterFire CLI

## 🔥 Firebase Setup (Recommended)

* Create a Firebase project

* Enable:

  * Authentication → Email/Password

  * Cloud Firestore

* Run:

firebase login
flutterfire configure
flutter pub get
flutter run
## 🛠️ Manual Setup (Alternative)

If not using FlutterFire CLI:

* Add Android app → download google-services.json → place in android/app

* Add iOS app → download GoogleService-Info.plist → place in ios/Runner

## 📌 Roadmap

 * Add unit & widget tests

 * Improve responsive UI

 * Add localization

 * Migrate fully to latest Firebase UI

 * Refactor remaining controllers

## 🤝 Contributing

* Contributions are welcome!

* Fork the repo

* Create your feature branch

* Commit your changes

* Push to the branch

* Open a Pull Request

