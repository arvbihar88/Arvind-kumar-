# Jeevanix Android App - Build Instructions

यह एक sample Android app project है। APK file बनाने के लिए निम्नलिखित steps follow करें:

## Requirements:
- Android Studio (latest version)
- Android SDK (API Level 33+)
- Java Development Kit (JDK 8+)
- Minimum 2GB RAM

## APK बनाने के steps:

### 1. Android Studio में Open करें:
- Android Studio खोलें
- File → Open
- इस project को select करें
- "Open" पर click करें

### 2. Build APK:
- **Menu में जाएं**: Build → Build Bundle(s) / APK(s) → Build APK(s)
- या keyboard shortcut: `Ctrl + Shift + B` (Windows/Linux) या `Cmd + Shift + B` (Mac)

### 3. APK location:
- APK यहाँ मिलेगी: `app/build/outputs/apk/debug/app-debug.apk`

### 4. Release APK (Optional):
- Build → Build Bundle(s) / APK(s) → Build Bundle(s)
- फिर release APK generate करने के लिए Google Play Console में upload करें

## Folder Structure:
```
Jeevanix/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/jeevanix/
│   │   │   │   └── MainActivity.java
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml
│   │   │   │   └── values/
│   │   │   │       ├── strings.xml
│   │   │   │       └── themes.xml
│   │   │   └── AndroidManifest.xml
│   ├── build.gradle
│   └── proguard-rules.pro
├── build.gradle
├── settings.gradle
└── gradle.properties
```

## Troubleshooting:

### Error: "Failed to find Build Tools"
- SDK Manager खोलें और Android Build Tools (33.0.0+) install करें

### Error: "Gradle sync failed"
- File → Sync Now करें
- या project को clean करें: Build → Clean Project

### Error: "Could not find com.android.application"
- settings.gradle और build.gradle files को check करें

## Notes:
- यह एक basic sample app है
- अपनी जरूरत अनुसार customize कर सकते हैं
- APK को Android devices पर install करने के लिए: `adb install app-debug.apk`
