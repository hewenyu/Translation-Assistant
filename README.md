# Translation Assistant

## Overview
Translation Assistant is an Android application designed to facilitate translation and voice synthesis using advanced AI models, Whisper and SenseVoice. The app provides a user-friendly interface for translating text and speech in real-time.

## Features
- Speech recognition and translation using the Whisper AI model.
- Voice synthesis capabilities with the SenseVoice AI model.
- Intuitive user interface for seamless interaction.
- Support for multiple languages.

## Project Structure
```
translation-assistant
├── app
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   └── com
│   │   │   │       └── translationapp
│   │   │   │           ├── activities
│   │   │   │           │   └── MainActivity.kt
│   │   │   │           ├── models
│   │   │   │           │   └── TranslationModel.kt
│   │   │   │           ├── services
│   │   │   │           │   ├── WhisperService.kt
│   │   │   │           │   └── SenseVoiceService.kt
│   │   │   │           └── utils
│   │   │   │               └── AudioUtils.kt
│   │   │   └── res
│   │   │       └── layout
│   │   │           └── activity_main.xml
│   ├── build.gradle
│   └── proguard-rules.pro
├── docs
│   ├── architecture.md
│   └── api-integration.md
├── gradle
├── build.gradle
├── gradlew
└── README.md
```

## Setup Instructions
1. Clone the repository:
   ```
   git clone [repository-url]
   ```
2. Open the project in Android Studio.
3. Sync the Gradle files.
4. Run the application on an Android device or emulator.

## Usage
- Launch the app and select the source and target languages.
- Use the microphone button to record speech for translation.
- View the translated text and listen to the synthesized voice output.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.# Translation-Assistant
