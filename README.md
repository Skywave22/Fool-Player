# Fool Player

A native Android video/audio player app combining the best features from VLC, MPV, MPC-HC, and MX Player.

## Project Status

### Phase 1 - Skeleton ✅
- Empty Android project structure
- App name "Fool Player"
- Basic navigation shell (Home/Browse screen → Player screen)
- Jetpack Compose UI framework
- Min SDK: 24 (Android 7.0), Target SDK: 34

## Tech Stack
- Language: Kotlin
- UI: Jetpack Compose
- Min SDK: 24, Target SDK: 34
- Build System: Gradle with Kotlin DSL

## Build Instructions

### Prerequisites
- Android Studio Hedgehog (2023.1.1) or later
- JDK 8 or higher
- Android SDK with API 34

### Building the APK
1. Open the project in Android Studio
2. Wait for Gradle sync to complete
3. Build > Build Bundle(s) / APK(s) > Build APK(s)
4. The APK will be located at `app/build/outputs/apk/debug/app-debug.apk`

Or using command line:
```bash
./gradlew assembleDebug
```

## Planned Features

### Phase 2 - Core Engine
- Integrate libmpv via JNI
- Play local files
- Basic play/pause/seek controls

### Phase 3 - Local Media Browser
- Folder/file scanning
- Thumbnail grid view
- MediaStore API integration

### Phase 4 - Mobile Gesture Layer
- Swipe seek controls
- Volume/brightness gestures
- Pinch to zoom

### Phase 5 - Network Sources
- HTTP/HTTPS streaming
- SMB/FTP support
- RTSP/RTMP protocols

### Phase 6 - Advanced Playback Controls
- Frame stepping
- A-B repeat
- Audio/subtitle delay
- Stats overlay

### Phase 7 - Subtitle System
- ASS/SSA rendering
- External subtitle loading
- Auto-match by filename
- Online subtitle search

### Phase 8 - PiP, Equalizer, Settings
- Picture-in-Picture mode
- Audio equalizer
- Advanced mpv.conf settings
- Resume position persistence

## License
This project is for educational purposes. Do not implement DRM-protected content playback or circumvention of any kind.
