<div align="center">

<img src="Docs/Images/pocket_corsa_logo_transparent.png" alt="POCKET CORSA Logo" width="640"/>

<br/>

**English** | [日本語 (Japanese)](README.ja.md)

</div>

---

<div align="center">

### Gameplay Video (YouTube)

<a href="https://www.youtube.com/watch?v=EA9pSfgaaV4" target="_blank" rel="noopener noreferrer">
  <img src="https://img.youtube.com/vi/EA9pSfgaaV4/0.jpg" alt="Play Assetto Corsa MODs on Android! POCKET CORSA" width="560"/>
</a>

</div>

<br/>

# POCKET CORSA Quick Start Guide

This is a basic user guide for running Assetto Corsa MODs natively on Android mobile devices with **POCKET CORSA**.

> **⚠️ Notice (Zero Bundled MOD Content)**  
> This application does not include any car or track data. Please supply and place your legally acquired Assetto Corsa MODs on your device storage before playing.

---

## 1. Download (Coming Soon)

Currently preparing for public release (Coming Soon).  
※ The APK distribution will be available on the GitHub [Releases](https://github.com/Five-GT/PocketCorsa/releases) page once ready.

---

## 2. System Requirements

Since Assetto Corsa MODs are high-fidelity assets originally created for PC, a capable mobile device is required to run them smoothly.

| Component | Minimum Requirements (Low Settings) | Recommended Requirements (Standard ~ High) |
| :--- | :--- | :--- |
| **OS** | Android 10.0 or later (64-bit required) | Android 12.0 or later |
| **SoC (CPU/GPU)** | **Antutu 600k – 800k class**<br>(Snapdragon 7s Gen 2 / 778G or equivalent) | **Antutu 1.0M – 1.5M+ class**<br>(Dimensity 7400-Ultra / Snapdragon 8 Gen 1 ~ Gen 2 or higher) |
| **RAM (Memory)** | **6GB or more** | **8GB – 12GB or more** |
| **Storage** | 5GB+ free space (for MOD files) | 10GB+ free space |

> **⚠️ Important Notice on Performance & Device Environment**  
> - Because PC-grade MODs are not optimized for mobile hardware, **even on devices with 1M+ Antutu scores, high-poly cars or large complex tracks may cause significant performance drops**.  
> - Depending on your individual device environment (background apps, memory availability, thermal throttling, etc.), **the app may not operate smoothly or may close unexpectedly even if system requirements are met**.  
> - If you experience stuttering or frame drops, adjust `MOD TEXTURE QUALITY` and `SMALL OBJECT DRAW DISTANCE` in the **SETTINGS** menu to lower settings.

---

## 3. Initial Setup (Permissions, Folder Creation, Path Config)

### Step 1: Grant Storage Permission
1. When you launch the app for the first time, Android's permission dialog/settings screen will automatically appear.
2. Follow the on-screen prompt and allow **"All files access"** (Manage External Storage).  
   *(※This permission is strictly required to scan and load MOD files from your device storage)*

### Step 2: Create Folders & Place MODs
Using a file manager app on your phone (such as Files) or via USB connection to a PC, create three folders in any preferred location (e.g., inside the `Download` folder):

- **Cars Folder** (e.g., `cars`)
- **Tracks Folder** (e.g., `tracks`)
- **Replays Folder** (e.g., `replays`) *(Empty folder where driving logs are automatically saved)*

> **💡 Important: Always Extract/Unzip MODs Before Copying**  
> Compressed archive files (`.zip`, `.rar`, `.7z`, etc.) **cannot be loaded directly**.  
> Always extract them first, and place the extracted folder (the directory containing `.kn5`, `ui/`, `data.acd`, etc.) into each respective folder.

### Step 3: Configure Paths in App Settings
1. Open **"SETTINGS"** from the top menu.
2. Select and browse to your created **Cars**, **Tracks**, and **Replays** folders respectively.
3. Once paths are set, the app will scan and load your MODs.

---

## 4. Options & Settings (SETTINGS)

In **"SETTINGS"** on the main menu, you can configure paths as well as performance and visual options:

- **MOD Path Settings**:
  - `CAR / TRACK / REPLAY PATH`: Change paths for cars, tracks, and replays
  - `RE-SCAN MODS`: Refresh and reload MOD lists after adding or removing files
- **Replay Settings**:
  - `ENABLE REPLAY RECORDING`: Toggle automatic driving log recording ON / OFF
  - `OTHER CARS (ONLINE)`: Set recording frequency of other players during online sessions
- **Graphics & Performance (For Smoother Gameplay)**:
  - `SMALL OBJECT DRAW DISTANCE`: Adjust rendering distance of small props (poles, signs, fences)
  - `MOD TEXTURE QUALITY`: Switch texture resolution and quality
  - `STREET LIGHTS`: Number of active real-time street lights (set to OFF for better performance)
- **System Settings**:
  - `VIBRATION`: Toggle haptic feedback on collisions and curb strikes ON / OFF

---

## 5. Car Selection, Skins & Driving Tuning

1. Tap **"CAR"** on the main menu to choose your vehicle.
2. **Skin Selection**: Switch liveries, colors, and visual variants.
3. **TUNING (Physics & Handling Adjustments)**:  
   Fine-tune your vehicle's physics to match your driving style:
   - **ACCEL MODEL**: Toggle between **"REAL"** (closely reflects the original MOD characteristics) and **"ARCADE"** (exhilarating and accessible handling)
   - **POWER**: Scale acceleration and engine output (30% to 400%)
   - **AIR DRAG**: Adjust aerodynamic drag affecting top speed and acceleration (25% to 200%)
   - **LATERAL GRIP**: Tune tyre side-grip and drift slide characteristics (50% to 150%)
   - **BRAKE CURVE**: Adjust pedal curve and braking sensitivity
   - **Presets**: Reset instantly with **"RESET TO DEFAULT"** (standard real values) or **"RESET TO ARCADE"** (easy handling)  
   *(※Online multiplayer automatically enforces REAL baseline settings for fair competition)*

---

## 6. Track & Layout Selection
1. Tap **"TRACK"** on the main menu.
2. Choose a track from your installed MOD collection.
3. If a track contains multiple layouts (drift layout, reverse, short circuit, etc.), you can select your preferred layout.

---

## 7. Driving Controls & Universal Operations

These controls apply to both Single Player and Online Multiplayer:

- **Steering Wheel**:  
  Swipe the steering wheel on the left side of the screen (up to 900° rotation with smooth counter-steer assist).
- **Multi-Slider Pedal (Throttle, Brake, Handbrake)**:
  - **Slide Up**: Throttle (Acceleration)
  - **Swipe Left**: Foot Brake (Deceleration / Stop)
  - **Swipe Right**: Handbrake (E-brake / Drift initiation)
  - **Slide Down**: Reverse gear
- **Transmission**:  
  Toggle between **AT (Automatic)** and **MT (Manual)**.
- **Lights & Horn**:
  - **LIGHTS**: Turn headlights and taillights ON / OFF
  - **< TURN / TURN >**: Left / Right turn indicators
  - **HAZARD**: Hazard warning flashers
  - **HORN**: Press and hold the dedicated HORN button to sound the horn
- **Camera View**:  
  Switch between Chase Cam, Driver Cockpit View (NeckFX-style dynamic G-force head movement), and Free Orbit Camera.

---

## 8. Single Player (Free Drive)
- Select your car and track, then tap **"DRIVE"** to enter the track immediately.
- Practice drifting, test grip lines, or learn tracks freely in solo mode.

---

## 9. Online Multiplayer
Connect to unofficial Assetto Corsa servers (**acServer / AssettoServer**) and drive with other players.

1. **Preparation**: Install the exact car and track MODs specified by the server with identical folder names.
2. Tap **"ONLINE"** in the menu, enter the server IP and HTTP port, and tap **"GET INFO"**.
3. Choose an available slot/skin and tap **"JOIN"** to connect.

> **🔗 One-Tap Join via Deep Link URLs**  
> Simply tapping an Assetto Corsa server join link (e.g. `acmanager://...` or `https://acstuff.ru/s/...`) shared in Discord or websites will launch POCKET CORSA and fill in the server details automatically.

4. **Online Features**:
   - **CHAT**: Send and receive text messages (supports `/` server commands)
   - **VIEW**: Spectate other players in real-time
   - **TIMES**: Live leaderboard and lap timing

> **⚠️ Notice**  
> When joining an online server, please always strictly respect and follow the rules established by each server.

---

## 10. Replay System
Record, review, and preserve your driving sessions.

- **Playback**:  
  Watch replays right after a run or access saved replays anytime from the **"REPLAY"** menu.
- **Dynamic Camera Angles**:  
  Inspect your drift angles and lines from onboard views, dramatic **Trackside TV Cameras**, or **Free Orbit Cam**.
- **Playback Controls**:  
  Adjust playback speed (slow motion / fast forward) and scrub through the timeline.

---

## 11. Notice & Disclaimer

- ※ This application does not contain any copyrighted car models, track meshes, textures, sounds, or commercial game data.
- ※ This application dynamically loads and runs user-provided MOD files located on device storage.
- ※ This application is a completely original, standalone project built from scratch using Unity (with zero code derived from Assetto Corsa or any other applications). Therefore, vehicle physics and behavior naturally differ from official Assetto Corsa.
- ※ This is an unofficial, non-profit community project created by individuals and is not affiliated with, endorsed by, or associated with Kunos Simulazioni, Digital Bros, or 505 Games.
- ※ All MODs are created for Assetto Corsa by third-party creators. The authors of this app and individual MOD creators have no affiliation with each other. Please do not contact MOD authors regarding this application.
- ※ The developers and contributors assume no liability or responsibility for any damages, losses, or troubles arising from the use (or inability to use) of this application. Use at your own risk.

---

### Credits
- **Planning & Development**: [ファイヴ](https://github.com/Five-GT)
- **Technical Assistance**: [Noel “Excël” Minamino](https://github.com/NoelMinamino)

Copyright 2026 ファイヴ
