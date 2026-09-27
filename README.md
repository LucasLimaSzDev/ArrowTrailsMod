# 🏹 Arrow Trail

<p align="center">
  <strong>A smooth, lightweight and customizable arrow trail system for Minecraft.</strong><br>
  Built for Fabric 1.20.1.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-1.20.1-5A8F29?style=for-the-badge&logo=minecraft&logoColor=white" alt="Minecraft 1.20.1">
  <img src="https://img.shields.io/badge/Loader-Fabric-CB2D6F?style=for-the-badge" alt="Fabric">
  <img src="https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 17">
</p>

---

## ✨ About

**Arrow Trail** replaces the usual vanilla arrow particle effect with a custom-rendered trail that follows arrows during flight.

The goal is simple: make arrows feel faster, cleaner and more visually satisfying without turning the effect into a pile of particles.

The trail dynamically follows the arrow's movement, supports different arrow types and smoothly disappears when the arrow's trajectory ends.

---

## 🎯 Features

- 🏹 Custom continuous trails behind arrows.
- 🎨 Trail colors follow the effect color of tipped arrows.
- ✨ Special visual treatment for spectral arrows.
- 🚫 Vanilla arrow particles are suppressed.
- 🌊 Smooth trail movement during flight.
- ⚡ Designed to remain smooth even with high-speed arrows.
- 💨 Trail retracts toward the arrow when its trajectory ends.
- 🌫️ Smooth fade-out after impact.
- 📏 Controlled trail length and width.
- 🧹 Prevents finished trails from being recreated or left behind.
- 🪶 Lightweight custom rendering instead of relying on vanilla particle spam.

---

## 📦 Installation

### Requirements

- **Minecraft:** 1.20.1
- **Mod Loader:** Fabric
- **Java:** 17
- **Fabric API:** Required

### Steps

1. Install **Fabric Loader 1.20.1**.
2. Install **Fabric API** for Minecraft 1.20.1.
3. Download the desired Arrow Trail release.
4. Place the `.jar` file inside your Minecraft `mods` folder.
5. Launch Minecraft.

> 💡 No special configuration is required for the basic trail system.

---

## 🧪 Releases

Each release represents a specific stage of Arrow Trail's development.

### 🏹 v1.0 — Initial Release

The first version introduces the core custom arrow trail system.

**Highlights**

- Basic custom arrow trails.
- Support for normal arrows.
- Support for spectral arrows.
- Support for tipped arrows.
- Trail colors based on arrow effects.
- Custom rendering replacing vanilla arrow particles.

---

### 🌊 v1.1 — Smooth Trail Update

Improves the movement and visual consistency of the original trail system.

**Highlights**

- Smoother trails during flight.
- Better tracking of arrow movement.
- Improved behavior at different arrow speeds.
- Adjusted trail width and length.
- Improved spectral-arrow visuals.
- Rendering improvements.
- More consistent suppression of vanilla arrow particles.

---

### ✨ v1.2 — Polished Trail System

Introduces a dedicated tracking system for better control over each arrow's trail.

**Highlights**

- Dedicated arrow tracking system.
- Controlled trail length.
- Improved flight stability.
- Smooth trail retraction when the trajectory ends.
- Fade-out after impact.
- Better handling of stopped or removed arrows.
- Improved trail width handling.
- Improved spectral-arrow differentiation.
- Cleaner internal rendering architecture.

---

### 💥 v1.3 — Impact & Trail Lifecycle Update

Focuses on correctly managing the entire lifecycle of a trail, especially when an arrow stops or impacts something.

**Highlights**

- Improved trajectory-end detection.
- Trails correctly finish when arrows stop.
- Smooth retraction after impact.
- Fade-out before complete removal.
- Gradual trail-width reduction while disappearing.
- Fixes for orphaned and duplicated trails.
- Finished arrows no longer recreate their trails.
- Improved handling of inactive arrows.
- More stable overall trail management.

---

## 🛠️ Development

Arrow Trail is built with **Java** and **Fabric** for **Minecraft 1.20.1**.

The project includes the **Gradle Wrapper**, allowing the project to be built without requiring a separate Gradle installation.

```text
ArrowTrailsMod/
├── gradle/
├── gradlew
├── gradlew.bat
├── build.gradle
├── settings.gradle
└── src/
```

Build on Windows:

```bat
On CMD (Administrator):
> cd c:/yourbuild/example
> gradlew.bat build
Once built, go on build/libs and you will find the mod ready to play
Or you can just download the latest release that i already built it for you :D
```

---

## 🧩 Design Philosophy

Arrow Trail is designed around three principles:

### 🌊 Smoothness

The trail should visually follow the arrow instead of looking like disconnected particles.

### 💥 Clean Impact Behavior

When an arrow reaches the end of its trajectory, the trail should retract and disappear rather than remain floating in the world.

### 🧹 Low Visual Clutter

The effect should enhance arrows without covering the screen in vanilla particle effects.

---

## 👤 Credits

**Arrow Trail**  
Created by **NemeCruel**

Minecraft is a trademark of Mojang Studios / Microsoft.  
This project is not affiliated with or endorsed by Mojang Studios or Microsoft.

---

## 📜 License

See the license information included with the corresponding project release.

---

<p align="center">
  <strong>🏹 Shoot farther. Look better.</strong><br>
  <sub>Arrow Trail — Fabric 1.20.1</sub>
</p>
