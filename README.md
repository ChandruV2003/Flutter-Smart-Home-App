### Flutter Smart Home App
A smart home application built with Flutter to control and monitor IoT devices.

## 🚀 Installation & Setup

### Prerequisites
```markdown

- Flutter SDK: (version 3.27.4 or newer)
- Git: installed
- IDE: Android Studio/Xcode (for mobile development) or VS Code
- Physical device: or emulator/simulator
 ```
### Steps to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/ChandruV2003/Flutter-Smart-Home-App.git
   cd Flutter-Smart-Home-App
    ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Upgrade Flutter** (if needed)
   ```bash
   flutter upgrade
   ```

4. **Generate splash screen** (required)
   ```bash
   flutter pub run flutter_native_splash:create
   ```

5. **Run the app**
   ```bash
   flutter run
   ```

## 🔧 Troubleshooting

- If you see package version warnings:
  ```bash
  flutter pub upgrade
  ```

- If you encounter Xcode/Android Studio issues:
  - Ensure you have accepted licenses:
    ```bash
    flutter doctor --android-licenses
    ```
  - Run:
    ```bash
    flutter doctor
    ```
    and resolve any reported issues

- For iOS build issues:
  - Ensure CocoaPods is installed:
    ```bash
    sudo gem install cocoapods
    ```

## 📱 Supported Platforms
- iOS
- Android
- Web
- macOS

Made with ❤️ by ChandruV2003
```

Key features:
1. Clear prerequisite list
2. Step-by-step installation guide
3. Specific troubleshooting section
4. Includes splash screen generation step
5. Platform compatibility list
6. Simple structure for easy scanning

The README focuses on essential setup steps while including common troubleshooting commands that appeared in your logs. The splash screen generation step is included as it's required for proper app initialization.
