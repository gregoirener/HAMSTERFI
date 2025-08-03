# 🐹 HamsterFi

**HamsterFi** is a lightweight, terminal-based wireless auditing tool — inspired by [Wifite](https://github.com/derv82/wifite2) — designed for automated Wi-Fi attacks such as handshake and PMKID capture.

Built for ethical hackers and pentesters, HamsterFi sniffs out vulnerable networks, flips on monitor mode, and goes hunting — all in a few keystrokes.

> ⚠️ HamsterFi is for **authorized use only**. Never use it on networks you don’t own or have permission to test.

---

## ⚡ Features

- 🔍 Auto-scans nearby Wi-Fi networks
- 📡 Monitor mode support via `airmon-ng`
- 🧠 Captures WPA/WPA2 handshakes
- 🔓 PMKID-based attack support
- 🛠️ Modular + customizable attacks
- 🐚 Clean and interactive TUI (Terminal UI)
- 🐧 Built for Debian-based systems, packaged as `.deb`

---

## 📦 Installation


sudo dpkg -i hamsterfi.deb

If dependencies are missing, fix them with:

sudo apt --fix-broken install

🚀 Usage

Just launch and let HamsterFi do the work:

sudo hamsterfi

Follow the on-screen instructions. You’ll be guided through network selection and attack modes.
🧠 Dependencies

HamsterFi relies on a few essential Linux tools:

    aircrack-ng

    airmon-ng

    hcxdumptool

    hcxpcapngtool

    python3

Install them via:

sudo apt install aircrack-ng hcxdumptool python3

👑 License

This project is licensed under the MIT License. You’re free to use, modify, and share — just keep the credit.

© 2025 Greg (a.k.a. creator of HamsterFi)

🛡️ Disclaimer

HamsterFi is a tool for ethical penetration testing, education, and research. The author is not responsible for misuse. Use responsibly — don't be that guy.
📫 Contribute / Contact

Found a bug? Have an idea? Submit a pull request or open an issue.
Want to reach out directly? Message me on GitHub or your preferred channel.
🐭 HamsterFi — small, fast, and deadly in the Wi-Fi jungle.
