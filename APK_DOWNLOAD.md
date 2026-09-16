# Jeevanix Android App - Automated APK Build

## ✅ GitHub Actions से APK Build हो रहा है!

हर बार जब आप code push करते हैं, automatically APK build होगी।

### APK Download करने के लिए:

#### **Method 1: Releases से Download करें (सबसे आसान)**
1. GitHub repo खोलें
2. Right side में "Releases" पर click करें
3. Latest release खोलें
4. **Jeevanix-app-debug.apk** download करें ✅

#### **Method 2: Actions से Download करें**
1. Repository खोलें
2. "Actions" tab पर click करें
3. Latest build को खोलें
4. "Artifacts" section में "app-debug" download करें

#### **Method 3: सीधे Link से Download करें**
```
https://github.com/arvbihar88/Arvind-kumar-/releases
```

## Build Status:
- **Workflow:** Build APK
- **Trigger:** हर push पर automatic build
- **Output:** APK file in Releases

## APK को Phone पर Install करें:

### Windows/Mac से:
```bash
adb install Jeevanix-app-debug.apk
```

### या सीधे Phone में:
- APK file को Phone में transfer करें
- File manager में खोलें
- Install करें

## Current Build Info:
- **App Name:** Jeevanix
- **Package Name:** com.example.jeevanix
- **Min SDK:** 21
- **Target SDK:** 33
- **Version:** 1.0

---

**🎉 APK अब automatically build हो रहा है! GitHub Releases से download करें।**
