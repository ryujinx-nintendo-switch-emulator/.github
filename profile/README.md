<p align="center">
  <img src="https://github.com/user-attachments/assets/ad44c4aa-f7e5-412e-8101-2376894ce525" alt="Logo" width="120" />
</p>

<h1 align="center">Ryujinx — Nintendo Switch Emulator</h1>

<p align="center">
  <em>An experimental, open-source Nintendo Switch emulator written in C#, <br>focused on accuracy, performance, and game preservation.</em>
</p>

<p align="center">
  <a href="https://share.google/PXFlvB0qx5vIgvy6A">
    <img src="https://github.com/user-attachments/assets/d2496228-e7c4-4061-8f4f-fe9865535558" alt="Latest Release" />
  </a>
</p>

<br>

## Table of Contents

- [About Ryujinx](#about-ryujinx)
- [Key Features](#key-features)
- [System Requirements](#system-requirements)
- [How to Use](#how-to-use)
- [Compatibility](#compatibility)
- [Important to Know](#important-to-know)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)
- [Keywords](#keywords)

---

## About Ryujinx

<img align="right" width="520" src="https://github.com/user-attachments/assets/e1115c66-7dc0-4223-baeb-304a2d94edff" alt="Screenshot" />

**Ryujinx** is an experimental, open-source emulator for the Nintendo Switch, written in C#. It aims to provide accurate emulation of the console's hardware — CPU, GPU, audio, and input — so that supported games run faithfully on PC.

The project is built around a custom CPU emulator, a GPU translation layer, and a modular architecture that makes it easy to debug, profile, and extend. Whether you're a developer curious about console emulation internals or a user looking to play your legally owned games on desktop, Ryujinx is designed to be approachable and transparent.

Development is community-driven and open, with regular releases, detailed logs, and per-game configuration options.

### Key Features

- **Custom CPU emulator** — high-level ARM64 emulation with JIT compilation
- **GPU emulation** — Vulkan and OpenGL backends for broad hardware support
- **Audio emulation** — accurate audio output with configurable backends
- **Input support** — keyboard, gamepad, and motion controls
- **Per-game settings** — tune resolution, vsync, and accuracy per title
- **Cross-platform** — Windows, Linux, and macOS builds
- **Detailed logging** — built-in diagnostics for troubleshooting
- **Active development** — regular updates and community contributions

<br clear="right" />

---

## System Requirements

- **OS:** Windows 10+, modern Linux distro, or macOS 12+
- **CPU:** x64 with AVX support (ARM64 supported on Apple Silicon)
- **GPU:** Vulkan 1.1+ or OpenGL 4.5+ capable card
- **RAM:** 8 GB minimum, 16 GB recommended
- **Storage:** SSD recommended for game loading
- **Runtime:** .NET runtime (bundled in releases)

---

## How to Use

1. **Download** the latest release for your platform from the Releases page.
2. **Extract** the archive to a folder of your choice.
3. **Launch** the emulator executable.
4. **Add your game directory** in *Options → Settings → General*.
5. **Configure input** in *Options → Settings → Input*.
6. **Select a game** from the list and press Play.
7. **Tune per-game settings** if needed (resolution, vsync, accuracy).

> You must dump your own games and system firmware from a console you own. Ryujinx does not provide games or keys.

---

## Compatibility

Compatibility varies by title. The emulator tracks per-game status across the community:

| Status | Meaning |
| :--- | :--- |
| Playable | Runs at full speed with minor or no issues |
| In-game | Boots and runs, but with glitches or performance issues |
| Broken | Does not boot or crashes early |

Check the community compatibility list before reporting issues.

---

## Important to Know

- **You need your own game dumps and firmware.** Ryujinx does not distribute copyrighted content.
- **Performance depends on hardware.** A strong CPU and Vulkan-capable GPU matter more than raw GPU power.
- **Not every game works.** Emulation is ongoing — some titles are playable, others are not.
- **Logs help developers.** When reporting bugs, include the emulator log and your system specs.
- **Updates are frequent.** Keep the emulator and your GPU drivers up to date.

---

## Frequently Asked Questions

**Do I need a Nintendo Switch to use Ryujinx?**
You need to dump your own games and firmware from a console you own. The emulator itself does not include them.

**Which GPU backend should I use?**
Vulkan is generally recommended for performance and compatibility. Try OpenGL if you hit Vulkan-specific issues.

**Why is my game running slowly?**
Check CPU single-core performance, enable shader cache, and try lowering resolution scale. Some titles are simply demanding.

**Does it support save files?**
Yes — saves are stored per-game in the emulator's data directory and can be backed up or transferred.

**Is online play supported?**
No official online services are supported. Local wireless and LAN may work in some cases.

**Is this legal?**
Emulation itself is legal in many jurisdictions, but you must own the games and firmware you use. Do not download copyrighted content.

---

## Troubleshooting

| Problem | Suggested Fix |
| :--- | :--- |
| Game won't boot | Verify game dump and firmware version; check the log |
| Crashes on launch | Update GPU drivers and .NET runtime |
| Low FPS | Lower resolution scale, enable shader cache, close background apps |
| Audio crackling | Try a different audio backend in settings |
| Controller not detected | Reconfigure input in settings; check driver |

---

## Contributing

Contributions are welcome — bug reports, compatibility updates, and code. Please read the contributing guidelines before opening a pull request, and include logs when reporting issues.

---

## Disclaimer

Ryujinx is an open-source emulator intended for development, testing, and preservation purposes. It does not include games, keys, or firmware. You are responsible for complying with the laws in your jurisdiction and for using only content you legally own.

---

## Keywords

`nintendo switch emulator` · `ryujinx` · `switch emulation` · `open source emulator` · `c# emulator` · `vulkan emulator` · `arm64 emulation` · `game preservation` · `switch games on pc` · `emulator for windows` · `emulator for linux` · `emulator for macos` · `custom cpu emulator` · `gpu emulation` · `per-game settings` · `switch firmware` · `homebrew` · `emulation accuracy` · `emulator troubleshooting` · `ryujinx compatibility`
