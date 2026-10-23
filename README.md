# NetPulse Hotspot Sentinel - Android 8.1+ (API 27 - 35)

This is the complete native Android Kotlin project to track data usage of connected hotspot devices, throttle bandwidth based on activity, and automatically disconnect devices that exceed custom quotas.

## 🚀 How to build the APK

### Method 1: Using Android Studio (Recommended)
1. Extract this ZIP file on your computer.
2. Open Android Studio -> **File > Open** -> Select this project folder.
3. Wait for Gradle sync to complete.
4. Connect your Android phone via USB (with USB Debugging enabled) or use an emulator.
5. Click the green **Run (Play)** button, or go to **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. The compiled APK is saved at:
   `app/build/outputs/apk/debug/app-debug.apk`

### Method 2: Command Line (Gradle)
Run the following in the project directory:
```bash
chmod +x gradlew
./gradlew assembleDebug
```
The APK will be generated at `app/build/outputs/apk/debug/app-debug.apk`.

### Method 3: GitHub Actions (Free Cloud Build without PC)
1. Push this folder to a GitHub repository.
2. The included `.github/workflows/build-apk.yml` will automatically compile the APK.
3. Go to the **Actions** tab on your GitHub repository, click the latest run, and download the **NetPulse-Hotspot-Debug-APK** artifact directly onto your phone!

## 📲 How to Install the APK on Your Android 8.1+ Phone
1. Transfer the `app-debug.apk` file to your Android phone (via USB, Google Drive, WhatsApp, or browser download).
2. On your phone, tap the `app-debug.apk` file in your **Files** / **Downloads** app.
3. If prompted with *"For your security, your phone is not allowed to install unknown apps from this source"*:
   - Tap **Settings**.
   - Enable **Allow from this source**.
   - Tap back and tap **Install**.
4. Open **NetPulse Hotspot Sentinel** and start your hotspot!
