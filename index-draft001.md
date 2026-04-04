# MichinakaMap – User Guide
Welcome to the official user guide for MichinakaMap.


**Version:** 1.0.202  
**Platform:** Windows 10 / 11 (64-bit)  
**Map Data:** © OpenStreetMap contributors

## Privacy Policy
👉 [View the Privacy Policy](privacy-policy)




## 1. Introduction
**MichinakaMap** is a specialized telemetry visualizer designed for GoPro users and GPS data analysts. It synchronizes GPS5 metadata with video playback, providing a high-speed (150fps) rendering of your journey on a dynamic map.

## 2. Quick Start
1. **Launch:** Run `michinakamap.exe`.
2. **Import:** Drag and drop your video file (`.mp4` or `.lrv`) directly onto the main window.
3. **Analyze:** Use the seek bar to navigate. The map cursor will move in perfect sync with the video.
4. **Window Management:** Toggle the "Master/Slave" mode in the `Role` menu to keep the map or video window on top.

## 3. Features
- **High-FPS Rendering:** smooth 150fps map updates for professional-grade analysis.
- **GoPro Proxy Support:** Native support for `.LRV` files, allowing fast seeking even on lower-spec hardware.
- **Ant Path Visualization:** Animated trajectory rendering for clear path identification.
- **State Persistence:** Automatically saves and restores map-window positions, sizes, and last-used folders via `settings.ini`.

## 4. Troubleshooting
- **Black Screen on Video:** Ensure your Windows Media Foundation is up to date. This app uses native Windows codecs; no 3rd-party codec packs are required.
- **Map Connection:** An internet connection is required to load map tiles from OpenStreetMap.
- **Port Conflict:** This app uses local port `18088` for internal rendering. If prompted by your firewall, please allow "Local Access Only".

## 5. Credits & Licenses
- **Map Data:** [OpenStreetMap](https://www.openstreetmap.org/copyright) (ODbL)
- **Path Animation:** [leaflet-ant-path](https://github.com/rubenspgcavalcante/leaflet-ant-path) (MIT)
- **Compression:** [zlib](https://zlib.net/) (zlib License)
- **Video Engine:** Windows Media Foundation (Microsoft)

## 6. Disclaimer
GOPRO and HERO are trademarks or registered trademarks of GoPro, Inc. This software is an independent utility and is not affiliated with, authorized, or endorsed by GoPro, Inc.

----
© 2026 thspec@outlook.com . All rights reserved.
