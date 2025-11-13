# EmotionHelper 😊

An **accessibility-focused** Android app that helps people with autism and social communication difficulties understand facial emotions in real-time.

## 🎯 Purpose

EmotionHelper is designed as an assistive technology tool to:
- Help individuals with autism spectrum disorder (ASD) recognize emotions
- Provide visual and audio feedback about detected emotions
- Support social skills development in a safe, controlled environment
- Offer educational descriptions of each emotion

## ✨ Features

- 📸 **Real-time Face Detection**: Uses Google ML Kit for accurate face recognition
- 😊 **Emotion Recognition**: Detects 6 primary emotions (Happy, Sad, Angry, Surprised, Tired, Neutral)
- 🔊 **Voice Feedback**: Text-to-speech announces detected emotions
- ♿ **Accessibility First**: Large buttons, high contrast, clear typography
- 🎓 **Educational**: Provides descriptions for each emotion to aid learning
- 🔒 **Privacy**: All processing happens on-device; no data sent to servers

## 📱 Technical Details

- **Platform**: Android (API 24+)
- **Language**: Kotlin
- **Camera**: CameraX for modern camera handling
- **ML**: Google ML Kit Face Detection API
- **Architecture**: MVVM pattern with ViewBinding

## 🚀 Getting Started

### Prerequisites

- Android Studio (latest version)
- Android SDK 24 or higher
- Physical Android device with camera (recommended for testing)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/janetelite3-png/EmotionHelper.git
   ```

2. Open the project in Android Studio

3. Sync Gradle files

4. Run on your device or emulator

### File Structure

```
app/
├── src/main/
│   ├── java/com/emotionhelper/
│   │   └── MainActivity.kt
│   ├── res/
│   │   ├── layout/
│   │   │   └── activity_main.xml
│   │   └── AndroidManifest.xml
│   └── build.gradle
```

## 🎮 How to Use

1. Launch the app and grant camera permissions
2. Position a face in front of the camera
3. Tap "DETECT EMOTION" button
4. The app will:
   - Show an emoji representing the detected emotion
   - Display the emotion name and description
   - Speak the emotion aloud

## 📋 Detected Emotions

| Emotion | Emoji | Description |
|---------|-------|-------------|
| Happy | 😊 | Smiling, content expression |
| Sad | 😢 | Downturned features, low energy |
| Angry | 😠 | Furrowed brows, tense expression |
| Surprised | 😮 | Wide eyes, open mouth |
| Tired | 😴 | Closed or drooping eyes |
| Neutral | 😐 | Relaxed, calm expression |

## 🛡️ Privacy & Ethics

- **On-device Processing**: All emotion detection happens locally
- **No Data Collection**: No images or data are stored or transmitted
- **Ethical Use**: Designed solely for accessibility and education
- **Not for Deception**: Cannot be used for lie detection (scientifically invalid)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for:
- Bug fixes
- New emotion categories
- Improved accessibility features
- Documentation improvements

## ⚠️ Disclaimer

This app is an assistive tool and should not be used as:
- A medical diagnostic tool
- A definitive measure of someone's emotional state
- A lie detection system (not scientifically valid)

Always consult qualified professionals for medical or psychological assessments.

## 🙏 Acknowledgments

- Google ML Kit for face detection capabilities
- The autism community for feedback and guidance
- Open-source contributors

## 📧 Contact

For questions or support, please open an issue on GitHub.

---

Made with ❤️ to support accessibility and inclusion
