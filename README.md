Event Networking App

An Android mobile application designed to foster student interaction by centralizing university event discovery and networking.

Project Overview
This application addresses the challenge of fragmented campus communication by providing a single platform where students can discover, discuss, and register for university events. It features real-time backend integration for seamless user data management.

Key Features
* Event Feed: Real-time list of upcoming campus activities.
* User Registration: Secure student sign-up and profile management.
* Interactive Discussions: (Optional: Add if true, e.g., "Comments or chat features for events").
* Backend Integration: Cloud-based data storage for reliability.

## Tech Stack
* Language: Java (Android Native Development)
* Backend: Firebase (Realtime Database / Firestore, Authentication)
* Build Tool: Gradle

## Setup & Installation
1.  Clone the Repo
    ```bash
    git clone [https://github.com/Ahmad-Ayman-Yousef/Event-Networking-App.git](https://github.com/Ahmad-Ayman-Yousef/Event-Networking-App.git)
    ```
2.  Open in Android Studio
    * Open Android Studio -> File -> Open -> Select this project folder.
    * Let Gradle sync the dependencies.
3.  Firebase Configuration
    * *Note: For security, the `google-services.json` file is not included.*
    * Create a new project in the [Firebase Console](https://console.firebase.google.com/).
    * Download your own `google-services.json` and place it in the `app/` directory.
4.  Run the App
    * Connect an Android device or start an Emulator.
    * Click the "Run" button (Green Play Icon).
