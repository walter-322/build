# Corex Linux

<p align="center">
  <img src="https://img.shields.io/badge/Base-Debian-red?style=for-the-badge&logo=debian" />
  <img src="https://img.shields.io/badge/Desktop-GNOME-blue?style=for-the-badge&logo=gnome" />
  <img src="https://img.shields.io/badge/License-GPL--3.0-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
</p>

> **Corex Linux** — A fast, clean, Debian-based desktop distribution built for everyday use.  
> Forked and fully rebranded from Zenclora OS. Powered by the `crx` package manager.

---

## ✨ Features

- 🏗️ **Debian stable base** — rock-solid foundation
- 🚀 **Performance-tuned kernel** — optimized for desktop responsiveness
- 🖥️ **GNOME desktop** — polished and customized out of the box
- 📦 **`crx` Package Manager** — one command to install anything
- 🎨 **Custom Corex branding** — splash screen, boot theme, MOTD
- 🌐 **Pre-installed apps** — browsers, media, editors, and dev tools

---

## 📦 Included Apps

| Category | Apps |
|---|---|
| Browsers | Firefox, Brave |
| Media | VLC, Rhythmbox |
| Editors | GNOME Text Editor, VS Code (via crx) |
| Productivity | LibreOffice |
| Dev Tools | git, curl, wget, htop, neofetch |
| Utilities | GParted, Timeshift, Synaptic |

---

## 🛠️ CRX Package Manager

`crx` is Corex Linux's unified package manager. It wraps `apt` and adds support for third-party apps with a single command.

```bash
crx install <package>     # Install a package
crx remove <package>      # Remove a package
crx update                # Update system and packages
crx list                  # List available packages
crx help                  # Show help
```

### Example installs

```bash
crx install brave          # Brave Browser
crx install vscode         # Visual Studio Code
crx install spotify        # Spotify
crx install steam          # Steam (gaming)
crx install docker         # Docker with Compose
crx install gaming-pack    # Lutris, Wine, MangoHud, GameMode
```

---

## 🏗️ Building

> Requires a Debian/Ubuntu host system.

```bash
git clone https://github.com/walter-322/build.git
cd build
chmod +x config/build.sh
sudo ./config/build.sh
```

The ISO will be placed in `out/`.

---

## 📋 System Requirements

| Component | Minimum | Recommended |
|---|---|---|
| CPU | 64-bit dual-core | Quad-core or better |
| RAM | 2 GB | 4 GB+ |
| Storage | 20 GB | 40 GB+ |
| Display | 1024×768 | 1920×1080 |

---

## 🤝 Contributing

Pull requests are welcome! Please open an issue first to discuss what you'd like to change.

---

## 📄 License

[GPL-3.0](LICENSE) — This project is free and open source.

---

<p align="center">Made with ❤️ — Corex Linux Project</p>
