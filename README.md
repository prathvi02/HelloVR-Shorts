# HelloVR-shorts
HelloVR-shorts is a Kotlin app that leverages Firebase Realtime Database and Cloud Storage to provide a seamless video viewing experience. The app uses ViewPager for smooth navigation through a collection of videos.

## Features
- Firebase Integration: Connects to Firebase Realtime Database and Cloud Storage.
- ViewPager: Implements a ViewPager for an intuitive video browsing experience.
- Video Adapter: Utilizes a FirebaseRecyclerAdapter for efficient loading of video data.
- Favorite Functionality: Allows users to mark videos as favorites.

## Dependencies
The app relies on the following Firebase and Firebase UI dependencies:
implementation("com.google.firebase:firebase-database:20.3.0")
implementation("com.google.firebase:firebase-storage:20.3.0")
implementation("com.firebaseui:firebase-ui-database:8.0.2")
implementation("com.firebaseui:firebase-ui-storage:8.0.2")

## How to Use
- Clone the repository to your local machine.
- Open the project in Android Studio.
- Connect the app to your Firebase project by adding your google-services.json file.
- Build and run the app on an Android device or emulator.

## Demo
For a visual overview of the app, check out the demo video.
[Screen_recording_20240225_235839.webm](https://github.com/prathvi02/HelloVR-Shorts/assets/73091532/85eef79e-2841-4998-be6b-08d4cc4cd164)

## Screenshots

![Screenshot_20240225_235949](https://github.com/prathvi02/HelloVR-Shorts/assets/73091532/fe53a89c-ec5a-44e3-832f-e84e1fdb2730)
![Screenshot_20240226_000009](https://github.com/prathvi02/HelloVR-Shorts/assets/73091532/f03e77e5-cb6e-499d-83c1-792dfc1a5e9b)

