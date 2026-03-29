# 🔐 Facebook-SSL-Pinning-Bypass
📡 Intercept Facebook network traffic on Android device

## 📌 Latest Tested App Version
- 🎯 Facebook version: **552.1.0.45.68**
- Architecture: **arm64-v8a, X86_64**
- For any inquiries, please contact me on Telegram [https://t.me/DarknessKing999](https://t.me/DarknessKing999)

## 🎥 Evidence
![Facebook Android](assets/v552.jpg)

## ✅ Other Apps
1. [Facebook iOS](https://github.com/shajon-dev/iOS-Facebook-SSL-Pinning-Bypass)
2. [Messenger Android](https://github.com/shajon-dev/Messenger-SSL-Pinning-Bypass)
3. [Messenger iOS](https://github.com/shajon-dev/iOS-Messenger-SSL-Pinning-Bypass)
4. [Instagram Android](https://github.com/shajon-dev/Instagram-SSL-Pinning-Bypass)
5. [Instagram iOS](https://github.com/shajon-dev/iOS-Instagram-SSL-Pinning-Bypass)
6. [Threads Android](https://github.com/shajon-dev/Threads-SSL-Pinning-Bypass)
7. [Threads iOS](https://github.com/shajon-dev/iOS-Threads-SSL-Pinning-Bypass)
8. [Business Suite Android](https://github.com/shajon-dev/Meta-Business-Suit-SSL-Pinning-Bypass)

## 📱 Requirements
1. 🔓 Rooted Android phone or Emulator with root access (ldplayer9 / nox player)
2. 🛠️ ADB tools installed on your computer
3. 🔄 ProxyPin or Reqable App for traffic capture

## 🔧 Setup Process
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

**📂 Free Patched `libcoldstart.so` files are available in the `libs/` folder**
**📜 Consolidated login scripts are available in the `login.sh` file**

## ☕ Donation

If this project helped you, consider buying me a coffee! ❤️

| Coin | Network | Address |
| :--- | :--- | :--- |
| <table border="0" cellpadding="0" cellspacing="0"><tr><td><img src="https://cryptologos.cc/logos/tether-usdt-logo.svg" width="20" /></td><td>&nbsp;<b>USDT</b></td></tr></table> | TRC20 [TRX Network] | `TAsPdCxkX9CeErJ4vw7xBHfZDT6vpdfmwH` |
| <table border="0" cellpadding="0" cellspacing="0"><tr><td><img src="https://cryptologos.cc/logos/ethereum-eth-logo.svg" width="20" /></td><td>&nbsp;<b>ANY Crypto</b></td></tr></table> | ETH / BSC | `0x22d4f314acbf6055b0a37df8df68f9cd40ba889a` |
| <table border="0" cellpadding="0" cellspacing="0"><tr><td><img src="https://cryptologos.cc/logos/bitcoin-btc-logo.svg" width="20" /></td><td>&nbsp;<b>BTC</b></td></tr></table> | Bitcoin Network | `14RYf4pw7v2rtttLxRch2StjFzFAn9ycCE` |


## Looking for leatest version patched `libcoldstart.so`? Contact me on Telegram
<p align="left">
  <a href="https://t.me/DarknessKing999" target="_blank">
    <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
  </a>
</p>
