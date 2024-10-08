# Flutter To-Do App with Firebase



This repository contains a simple Flutter to-do app that utilizes Firebase for backend services. The app allows users to create, manage, and organize their to-do tasks seamlessly. Firebase is integrated for real-time data synchronization, authentication, and cloud storage.

## Features

- **User Authentication:** 
  - The app supports user registration and authentication using Firebase Authentication.
  
- **Real-time Data Sync:** 
  - To-do tasks are synchronized in real-time across multiple devices.

- **Add and Edit Tasks:** 
  - Users can add new tasks and edit existing ones with ease.

- **Mark as Complete:** 
  - Tasks can be marked as complete, with a visual indication for completed tasks.

- **Delete Tasks:** 
  - Users can delete tasks they no longer need.

- **Task Categories:** 
  - Tasks can be organized into different categories or projects.

## Getting Started

### Prerequisites

- [Flutter](https://flutter.dev/docs/get-started/install)
- [Firebase Account](https://firebase.google.com/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/flutter-to-do-app.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd flutter-to-do-app
   ```
3. **Install dependencies:**
   ```bash
   flutter pub get
   ```
4. **Set up Firebase:**
   - Go to the [Firebase Console](https://console.firebase.google.com/), create a new project, and configure it for both iOS and Android.
   - Download the `google-services.json` file for Android and `GoogleService-Info.plist` file for iOS, and place them in their respective directories as per the Firebase setup instructions.
   
5. **Run the app:**
   ```bash
   flutter run
   ```

## Firebase Setup Guide

For a detailed guide on setting up Firebase with Flutter, refer to the official [Firebase Documentation](https://firebase.flutter.dev/docs/overview).

