
# Flutter Camera App

This Flutter Camera App provides an easy-to-use interface for capturing photos and videos on Android and iOS devices. The app leverages the device's camera and includes features for taking pictures, recording videos, and customizing camera settings.

## Features

- *Capture Photos:* Take high-quality photos with a simple interface.

- *Record Videos:* Record videos with sound using the device's camera.

- *Switch Camera:* Toggle between front and rear cameras.

- *Flash Control:* Enable or disable the camera flash for better photo quality.

- *Gallery Access:* View captured photos and videos in the device's gallery.

- *Zoom Functionality:* Pinch to zoom in and out while using the camera.


## Requirements

Flutter SDK (version 3.x or above)

Dart 2.x

Android SDK (for Android devices)

Xcode (for iOS devices)


## Installation

1. Clone the Repository:

```
git clone https://github.com/josevbrito/flutter-camera-app.git
```

2. Navigate to the Project Directory:

```
cd flutter-camera-app
```

3. Install Dependencies: Run the following command to install all necessary packages.

```
flutter pub get
```

4. Run the App: Connect your device or use an emulator, and run the app using:

```
flutter run
```

## Usage

1. Taking a Photo:

- Open the app and point the camera at your subject.

- Tap the capture button to take a picture.

- The photo will be saved automatically to your gallery.



2. Recording a Video:

- Switch to video mode by tapping the video icon.

- Tap the record button to start and stop recording.

- The video will be saved automatically to your gallery.




## Project Structure


```
lib/
├── main.dart           # App entry point
├── camera_screen.dart  # UI for camera interaction
└── gallery_screen.dart # UI for viewing photos and videos
```

## Contributing

Feel free to open issues or contribute to this project by submitting pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

