# Aurora — Camera, Video Editor, Gallery & Live Streaming Suite

Aurora is a complete, offline-first Android camera, video editing, gallery, and live streaming suite. Built with Kotlin, Jetpack Compose, CameraX, and Jetpack Media3, Aurora offers pro-grade camera manual controls, non-destructive video trimming/effects, and an ad-free gallery in one unified application.

---

## 📸 Key Features & Subsystem Breakdown

### 📷 Pro Camera Engine (`camera`)
- **Current**: CameraX manual exposure/ISO/shutter controls, real-time RGB histogram, color eyedropper, focus peaking, and RAW/DNG capture support.
- **Planned / Roadmap**: Multi-camera simultaneous recording, anamorphic lens de-squeeze, HDR video capture, and custom LUT preview.

### ✂️ Video Editor & Timeline (`editor`)
- **Current**: Frame-accurate video trimming, clip splitting, aspect ratio cropping, text overlay, and Media3 Transformer hardware encoding export.
- **Planned / Roadmap**: Multi-track video timeline, transition effects, speed ramping, color grading wheels, and audio track mixing.

### 🖼️ Private Gallery & Vault (`gallery`)
- **Current**: Fast MediaStore media indexing, album organization, EXIF metadata inspector, and image viewer.
- **Planned / Roadmap**: Encrypted media vault, duplicate photo finder, location map view, and automatic document scanner.

### 📡 Live Streaming Studio (`stream`)
- **Current**: RTMP / RTMPS live streaming pipeline with custom screen overlays and audio input selector.
- **Planned / Roadmap**: SRT protocol support, multi-destination streaming, chat overlay integration, and scene presets.

---

## 🏗️ Architecture & Technology Stack

- **Platform**: Android 13+ (minSdk 33, targetSdk 37).
- **UI & Layout**: Kotlin, Jetpack Compose, Material 3, Navigation 3.
- **Media Stack**: CameraX, Jetpack Media3 Transformer, OpenGL ES 3.0 shaders.
- **Licensing**: AGPL-3.0.

---

## 🛠️ Building & Running

```bash
./gradlew assembleDebug
./gradlew installDebug
```

---

## 📜 License

Aurora is released under the **GNU Affero General Public License v3.0** (AGPL-3.0). See [`LICENSE`](LICENSE) for details.
