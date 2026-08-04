🌐 **Read in:** [English](#) | [日本語 (Japanese)](michinakamap_manual_ja.md)

---

# MichinakaMap User Manual (`michinakamap_manual.md`)

This document provides instructions on how to perform basic operations within the application.

---

## 1. Context Menu (Right-Click Menu)

Right-clicking anywhere on the screen displays the following context menu options:

| Menu Item | Shortcut | Description |
| :--- | :--- | :--- |
| **Open File** | - | Opens and plays MP4 or LRV video files. |
| **Next File** | - | Advances to and plays the next MP4 or LRV file. |
| **Aspect Ratio** | - | Adjusts the resolution and aspect ratio of the viewport. |
| **Slow Down** | - | Decreases the playback speed. |
| **Speed Up** | - | Increases the playback speed. |
| **Info Overlay Location** | - | Sets the screen position where detailed information is displayed. |
| **Switch View Role** | - | Toggles the foreground and background positions between the map and video views. |
| **Options** | - | Opens application settings and preferences. |
| **TimeZone Offset** | - | Configures the time difference relative to Coordinated Universal Time (UTC). |
| **Use GPS Speed** | - | Toggles between 2D speed and 3D speed calculation modes. |
| **Speed Unit** | - | Switches the speedometer display unit between km/h and mph. |
| **Purchase Full Version** | - | Opens the store/checkout page to upgrade to the full featured version. |
| **About** | - | About MichinakaMap Application. |
| **Exit** | - | Closes and exits the application. |

---

## 2. Keyboard Shortcuts

A reference guide for keyboard operations across different application windows.

### 2.1 Video Playback Window (MP4 / LRV)

| Key | Function |
| :--- | :--- |
| `Space` | Toggle playback (Play / Pause). |
| `.` | Step forward by 1 frame and pause. |
| `Home` | Jump to the beginning of the video (0s). |
| `End` | Jump to the last frame of the video. |
| `Up Arrow (↑)` | Skip forward by 10 seconds. |
| `Down Arrow (↓)` | Skip backward by 10 seconds. |
| `Right Arrow (→)` | Skip forward by 1 second. |
| `Left Arrow (←)` | Skip backward by 1 second. |

---

### 2.2 Map Window (GPS5 / GPS9 Leaflet Antpath)

| Key | Function |
| :--- | :--- |
| *(None)* | *(No custom keyboard shortcuts assigned)* |

---

## 3. Notes & Remarks

* **TimeZone Offset**: The application detects daylight saving time (`TIME_ZONE_ID_DAYLIGHT`) dynamically using the `GetTimeZoneInformation` API. In the latest version, `TimeZone Offset` configuration settings are no longer stored in an external `config` file.