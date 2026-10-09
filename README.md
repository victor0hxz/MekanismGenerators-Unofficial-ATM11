<!-- CURSEFORGE-DESCRIPTION:START -->
[View this project on CurseForge](https://www.curseforge.com/minecraft/mc-mods/mekanism-generators-version-locked)

### ⚡ Mekanism Generators: Version Locked

![Mekanism: Generators Version Locked logo](https://media.forgecdn.net/attachments/description/null/description_e97fab3e-1533-4e12-909b-d1d1ca6f92e3.png)

An unofficial community-made port of **Mekanism Generators** for Minecraft 26.1.2

This project is **version locked to Minecraft 26.1.2** and will not be updated to newer Minecraft versions.

### ⚠️ Unofficial Project

This project is **not affiliated with, maintained by, or endorsed by the original Mekanism development team**.

**Mekanism Generators** is part of the Mekanism project, originally created by **Aidan C. Brady** and developed with contributions from the Mekanism team and community contributors.

Full credit goes to **Aidan C. Brady and all original contributors** for their work on the original project.

**Original Project:** [Mekanism on GitHub](https://github.com/mekanism/mekanism)

**⚠️ Requirement:** This mod requires [**Mekanism: Version Locked**](https://www.curseforge.com/minecraft/mc-mods/mekanism-version-locked) to function properly. Please make sure you have the correct version installed.

### 📦 Version Locked

* **Minecraft:** 26.1.2
* **Mod Loader:** NeoForge
* **Future Minecraft versions:** Not supported
* **Project Type:** Unofficial community-made port

This project is specifically intended for players who want to use **Mekanism Generators on Minecraft 26.1.2**.

### 🐛 Bugs & Compatibility

This is a community-made port and **may contain bugs, crashes, unexpected behavior, or compatibility issues**.

Some features may not work exactly as they did in the original version, and compatibility with other mods is not guaranteed.

Please keep this in mind when using the project.

### 📜 Credits & License

Full credit goes to **Aidan C. Brady, the original Mekanism developers, contributors, and artists** who worked on the original project.

This project is distributed under the **MIT License**, with the license included in the JAR.

Please support the original Mekanism project and its developers.

### 🧪 ATM11 Compatibility

This mod has been tested with **All the Mods 11 (ATM11) version 0.9.0-beta** and is intended to provide **full compatibility with this version and future versions of the modpack**.

### 🔧 Check out also!

If you are using this addon, check out the other projects adapted for Minecraft 26.1.2:

### ⚙️ [Mekanism: Version Locked](https://www.curseforge.com/minecraft/mc-mods/mekanism-version-locked) — The main Mekanism port for Minecraft 26.1.2

### 🛠️ [Mekanism Tools: Version Locked](https://www.curseforge.com/minecraft/mc-mods/mekanism-tools-version-locked) — Additional tools, weapons, and armor content adapted for Minecraft 26.1.2

### 🧩 [Mekanism Additions: Version Locked](https://www.curseforge.com/minecraft/mc-mods/mekanism-additions-version-locked) — Additional content and features for Mekanism, adapted for Minecraft 26.1.2

> **Important:** These projects are also unofficial community-made ports and may contain bugs or compatibility issues.

<!-- CURSEFORGE-DESCRIPTION:END -->

---

## GitHub build, source and release documentation

# Mekanism: Generators Version Locked

<!-- curseforge-project -->
**CurseForge: [Version Locked fan project page](https://www.curseforge.com/minecraft/mc-mods/mekanism-generators-version-locked).**

<!-- installed-version-locked -->
**Current download: [Mekanism: Generators Version Locked](https://github.com/victor0hxz/MekanismGenerators-Unofficial-ATM11/releases/tag/atm11-instance-2026-10-08)** — [download JAR directly](https://github.com/victor0hxz/MekanismGenerators-Unofficial-ATM11/releases/download/atm11-instance-2026-10-08/MekanismGenerators-Version-Locked-26.1.2-1.0.jar).

This is the Version Locked build copied unchanged from our ATM11 instance, published as an unofficial fan version. Original Mekanism authors and MIT license credits are preserved. This is not endorsed by the upstream authors or the ATM team.

The source snapshot below belongs to the earlier compatibility build and has **not been confirmed to reproduce the Version Locked JAR**. Current release binaries and older source history are distinguished explicitly.

## Matching Version Locked modules

- [Mekanism: Version Locked](https://github.com/victor0hxz/Mekanism-Unofficial-ATM11/releases/tag/atm11-instance-2026-10-08)
- [Mekanism: Additions Version Locked](https://github.com/victor0hxz/MekanismAdditions-Unofficial-ATM11/releases/tag/atm11-instance-2026-10-08)
- [Mekanism: Generators Version Locked](https://github.com/victor0hxz/MekanismGenerators-Unofficial-ATM11/releases/tag/atm11-instance-2026-10-08)
- [Mekanism: Tools Version Locked](https://github.com/victor0hxz/MekanismTools-Unofficial-ATM11/releases/tag/atm11-instance-2026-10-08)

<!-- older-source-snapshot -->
# Mekanism Generators - Unofficial Fan Build (26.1.2)

Adds power generators and advanced energy multiblocks such as turbines and fission/fusion reactors. This is the matching Generators module from the fan-maintained ATM11 compatibility build.

## Unofficial fan build and credits

This adaptation was prepared by **victor0hxz** for the ATM11 compatibility project. It is an **unofficial version made by fans**, not an official release. It is not affiliated with or endorsed by the original authors or the All the Mods team.

Original authors: **Aidan C. Brady and the Mekanism contributors**. [Original source project](https://github.com/mekanism/Mekanism). The original MIT license and copyright notices are preserved. The original mod authors retain credit for the mod and its content.

## Requirements and installation

Minecraft **26.1.2**, NeoForge and **Java 25**. Requires matching Mekanism 10.8.0 for Minecraft 26.1.2.

Replace the older copy of the same mod; do not install the official build and this build together because the mod ID is unchanged. Keep Mekanism modules on matching versions. This older source build is a separate alternative to the Version Locked modules used by the newer Extras tests; mixing them has not been validated. Dependencies are not bundled.

## Validation and release status

Compiled artifact located in the previous ATM11 server correction package. Archive integrity and metadata verified; no new full-pack runtime validation was performed for this publication.

This initial file should be submitted as **Beta**, pending full-pack community gameplay tests. Do not interpret a compiled JAR as a guarantee that every gameplay scenario has been tested.

## Downloads and support

Download the unofficial prerelease JAR from [this repository's releases](https://github.com/victor0hxz/MekanismGenerators-Unofficial-ATM11/releases). Report problems to [this port's issue tracker](https://github.com/victor0hxz/MekanismGenerators-Unofficial-ATM11/issues). Do not direct port-specific support requests to the original authors.

## Build source

This repository preserves the local production source snapshot used by the compatibility project, including the original license. Install Java 25 and use the Gradle wrapper. Torchmaster: `gradlew.bat :neoforge:jar`; Mekanism and modules: `gradlew.bat jar`; SFM: run `gradlew.bat build` inside `platform/minecraft`. Original optional dependency versions remain in the inherited Gradle configuration. An uncached rebuild of this snapshot has not been validated in this publication step.

The core and all companion modules share the original Mekanism source tree. Each module has its own repository and release; this repository distributes only its named module JAR. Do not mix this older source build with Version Locked modules without testing.
