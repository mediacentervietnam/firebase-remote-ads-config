# firebase-remote-ads-config
A plug-and-play Android library to manage AdMob / GAM / Pangle Ads IDs and Networks remotely via Firebase.

# Android Firebase Ads Config SDK

A plug-and-play Android library to manage AdMob / GAM / Pangle Ads IDs and networks remotely using Firebase Remote Config.

## ✨ Features
- Remote config Ads App ID & Ad Unit ID
- Switch ads network without app update
- Enable / Disable ads globally
- Frequency cap & cooldown (anti invalid traffic)
- Debug mode
- Clean architecture – easy to extend

## 🚀 Installation

### JitPack
```gradle
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    implementation "com.github.YOUR_GITHUB:android-firebase-ads-config:1.0.0"
}

