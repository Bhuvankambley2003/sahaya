# SAHAYA

**SAHAYA** is our solution for **GDSC 2024**, aiming to address several United Nations Sustainable Development Goals, including:

- **Sustainable Cities and Communities**
- **No Poverty**
- **Quality Education**
- **Zero Hunger**

Our app provides a one-stop solution with the following features:

- Gadget Donation
- Food Donation
- Government Schemes
- AI Edu-bot
- Community Platform
- E-library

## Prerequisites

Before running the app, ensure the following prerequisites are met:

1. **Flutter and Dart**  
   Make sure Flutter and Dart are installed and set up on your machine. You can check this by running the command `flutter --version` in your terminal/command prompt. If Flutter is not installed, follow the instructions [here](https://flutter.dev/docs/get-started/install).

2. **Suitable IDE**  
   Use an IDE that supports Flutter. Popular options include [Android Studio](https://developer.android.com/studio) and the recommended [VS Code](https://code.visualstudio.com/Download).

3. **Flutter and Dart Plugins (Android Studio)**  
   If using Android Studio, ensure the Flutter and Dart plugins are installed. Go to `File -> Settings -> Plugins`, search for Flutter and Dart, and install them.

4. **Flutter Extension (VS Code)**  
   If using VS Code, install the Flutter extension by going to the Extensions view (`Ctrl+Shift+X`), searching for the Flutter extension, and installing it.

5. **Device/Emulator**  
   Ensure you have a device to run the app on, either a physical Android/iOS device or an emulator/simulator. If using an emulator/simulator, ensure it is properly set up.

6. **Run Flutter Doctor**  
   Before starting, run the `flutter doctor` command to check for any missing dependencies and complete your setup.

   ```bash
   flutter doctor
   ```
   
## Installation and Running

## Follow these steps to install and run the app:

## Clone the repository:
```bash
git clone https://github.com/Hemanpmanny/GDSC_SAHAYA.git
```
## Navigate to the project directory:

```bash
cd GDSC_SAHAYA-master
```
## Install dependencies:
```bash
flutter pub get
```
## Run the app:
The app may take approximately 4 minutes to start.

```bash
flutter run
```

Important Notes
⚠️ Caution:
GitHub is actively scanning the code for API tokens. If any are detected, they will be reported to OpenAI for invalidation. Therefore, ensure that your OpenAI API key has available credits, and add it to the appropriate location for the chatbot to work correctly.

Add your OpenAI API key here:

GDSC_SAHAYA-master/lib/ChatBot/api_key.dart
