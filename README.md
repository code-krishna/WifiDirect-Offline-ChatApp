# WifiDirect Offline Chatting Application

**Offline Chatting Application** is a simple messaging app that allows users to communicate with each other using **Wi-Fi Direct** and **Socket Programming**. This app enables peer-to-peer communication without the need for an internet connection, making it ideal for scenarios where the internet is unavailable or when users want to chat without consuming mobile data.

## Features

- **Wi-Fi Direct Communication**: Chat with other devices over Wi-Fi Direct, no internet required.
- **Socket Programming**: Utilizes socket programming to establish connections between devices for real-time communication.
- **User-friendly Interface**: Simple and clean design for easy chatting.
- **Multiple Device Support**: Supports multiple users on the same network, each connected via Wi-Fi Direct.
- **Instant Messaging**: Send and receive messages instantly.

## Folder Structure

The project is organized as follows:
```
WifiDirect-Offline-ChatApp/
├── app/                            # Main app module
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/               # Java source code
│   │   │   │   └── com/
│   │   │   │       └── example/
                        └── android_final_proj/ # Package for all app classes
│   │   │   ├── res/                # Resources
│   │   │   │   ├── layout/         # XML layout files
│   │   │   │   ├── drawable/       # Image resources
│   │   │   │   └── values/         # Styles, colors, strings, etc.
│   │   │   └── AndroidManifest.xml # App configuration and permissions
├── build.gradle                    # Project-wide build configuration
├── settings.gradle                 # Gradle settings
└── gradle/                          # Gradle wrapper files
```
## Prerequisites

- **Android Studio** (latest stable version)
- **Android SDK** (minimum version: API 21)
- **Wi-Fi Direct Enabled Device**: The app works by connecting devices directly via Wi-Fi Direct, so ensure your device supports this feature.

## Setup Instructions

1. **Clone the Repository**:
   Clone the repository to your local machine:
   ```git clone https://github.com/your-username/WifiDirect-Offline-ChatApp.git```

2. **Open the Project**:
Open the project in Android Studio.

3. **Configure the Project**:
Make sure you have the necessary Android SDK and build tools installed. Sync the Gradle files and build the project.

4. **Run the App**:
Connect an Android device or start an emulator. The app requires Wi-Fi Direct to work, so use a physical device to test. Click on the “Run” button in Android Studio to launch the app.

How It Works
	1.	Wi-Fi Direct: The app leverages Wi-Fi Direct to establish a connection between devices. Wi-Fi Direct is a feature that allows devices to connect directly to each other without the need for a traditional router or access point.
	2.	Socket Programming: Once devices are connected via Wi-Fi Direct, the app uses socket programming to establish a communication channel. This allows messages to be sent and received in real-time between connected devices.
	3.	Message Exchange: Once the connection is established, users can send messages to each other instantly. The chat interface is simple, with a text input box and a message display area.

Dependencies
	•	Android SDK (minimum version: API 21)
	•	Socket.IO for real-time messaging (optional, if used for socket communication)
	•	Wi-Fi Direct enabled devices

You can find the full list of dependencies in the build.gradle files.

Contributing

Contributions are welcome! If you’d like to contribute to the development of the Offline Chatting Application, follow these steps:
	1.	Fork the repository.
	2.	Clone your fork locally.
	3.	Create a new branch for your changes.
	4.	Make your changes and commit them.
	5.	Push your changes to your fork.
	6.	Submit a pull request with a description of your changes.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
	•	Wi-Fi Direct for making peer-to-peer communication possible.
	•	Open source libraries used in this project.

