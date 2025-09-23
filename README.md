# Facebook-SSL-Pinning-Bypass
Intercept Facebook network traffic on Android device

## Latest Tested App Version
- Facebook App version: **531.0.0.47.76**
- Architecture: **arm64/aarch64**
---
![headers](https://raw.githubusercontent.com/SHAJON-404/Facebook-SSL-Pinning-Bypass/refs/heads/main/IMAGE/v531.jpg)
---

## Requirements for Mobile Phone
 1. Rooted Andriod Phone [possible non root also]
 2. ProxyPin or Reqable App

## Requirements for Emulator
1. Windows PC with Reqable/ Burpsuit/ Mitmproxy installed  
2. Android emulator (Nox/LDPlayer)  
3. Root access on emulator  

## Process
 1. replace patched `libcoldstart.so` with `/data/data/com.facebook.katana/lib-compressed/libcoldstart.so`
 2. Command  ```adb push D:\patched\libcoldstart.so /data/data/com.facebook.katana/lib-compressed/libcoldstart.so```
 3. run proxypin or reqable app to capture traffic :)

## Looking for leatest version patched `libcoldstart.so` contact me
<p align="left">
  <a href="https://t.me/DarknessKing999" target="_blank">
    <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
  </a>
</p>
