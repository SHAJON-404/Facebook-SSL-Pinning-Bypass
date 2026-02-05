# 🔐 Facebook-SSL-Pinning-Bypass
📡 Intercept Facebook network traffic on Android device

## 📌 Latest Tested App Version
- 🎯 Facebook version: **547.0.0.24.68**
- Architecture: **arm64-v8a, X86_64**

## 🎥 Evidence
![Facebook Android](https://raw.githubusercontent.com/shajon-dev/Facebook-SSL-Pinning-Bypass/refs/heads/main/IMAGE/v547.jpg)

## Other Apps
1. [Messenger Android](https://github.com/shajon-dev/Messenger-SSL-Pinning-Bypass)
2. [Messenger iOS](https://github.com/shajon-dev/iOS-Messenger-SSL-Pinning-Bypass)
3. [Instagram Android](https://github.com/shajon-dev/Instagram-SSL-Pinning-Bypass)
4. [Threads Android](https://github.com/shajon-dev/Threads-SSL-Pinning-Bypass)
5. [Business Suite Android](https://github.com/shajon-dev/Meta-Business-Suit-SSL-Pinning-Bypass)
6. [Instagram iOS](https://github.com/shajon-dev/iOS-Instagram-SSL-Pinning-Bypass)
7. [Facebook iOS](https://github.com/shajon-dev/iOS-Facebook-SSL-Pinning-Bypass)
8. [Threads iOS](https://github.com/shajon-dev/iOS-Threads-SSL-Pinning-Bypass)

## 📱 Requirements
1. 🔓 Rooted Android phone/tablet (root access required)
2. 🛠️ ADB tools installed on your computer
3. 🔄 ProxyPin or Reqable App for traffic capture

## 🔧 Patching Existing Installation Process
 1. 🔧 **Replace patched `libcoldstart.so`** with the original file at: `/data/data/com.facebook.katana/lib-compressed/libcoldstart.so`
 2. 📲 **Use ADB command** to push the patched library:
    ```
    adb push D:\patched\libcoldstart.so /data/data/com.facebook.katana/lib-compressed/libcoldstart.so
    ```
 4. Use any packet capture tool to monitor Facebook network traffic.

## 📦 For Demo - Download Official APKs
**📥 Download Facebook 500.0.0.57.50 from official sources:**

- **🔧 arm64-v8a (64-bit):** [https://www.apkmirror.com/apk/facebook-2/facebook/facebook-500-0-0-57-50-release/facebook-500-0-0-57-50-22-android-apk-download/](https://www.apkmirror.com/apk/facebook-2/facebook/facebook-500-0-0-57-50-release/facebook-500-0-0-57-50-22-android-apk-download/)

- **🔧 x86_64 (64-bit emulator):** [https://www.apkmirror.com/apk/facebook-2/facebook/facebook-500-0-0-57-50-release/facebook-500-0-0-57-50-15-android-apk-download/](https://www.apkmirror.com/apk/facebook-2/facebook/facebook-500-0-0-57-50-release/facebook-500-0-0-57-50-15-android-apk-download/)

**📂 Patched `libcoldstart.so` files are available in the `so_files` folder**

## Looking for leatest version patched `libcoldstart.so`? Contact me on Telegram
<p align="left">
  <a href="https://t.me/DarknessKing999" target="_blank">
    <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
  </a>
</p>
