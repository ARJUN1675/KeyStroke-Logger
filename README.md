# KeyStroke-Logger
# 🔑 Keystroke Logger

A lightweight, Python-based keystroke logger with a GUI interface — built for educational and controlled monitoring purposes.

> **Project by:** Thatikonda Arjun  
> **AICTE ID:** STU68edc85df2a941760413789  
> **Institution:** GITAM University

---

## 📌 Problem Statement

Existing keystroke monitoring tools are often complex, heavyweight, or difficult to use. This project provides a simple, accessible alternative that records keyboard activity in both plain text and structured JSON formats, wrapped in an easy-to-use GUI — designed strictly for educational and controlled use.

---

## 📖 Project Description

This is a Python-based Keystroke Logger that captures and logs all keyboard events in real time. When the user clicks **"Start Keylogger"**, the application begins listening to keyboard activity — detecting when a key is **Pressed**, **Held**, or **Released** — and simultaneously saves the data to two output files.

**Output Files:**
- `logs.txt` — Plain text log of all keystrokes
- `logs.json` — Structured JSON log for programmatic use

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Programming Language | Python 3 |
| GUI Framework | Tkinter |
| Keyboard Listener | Pynput |
| Data Storage | JSON (`logs.json`) + Plain Text (`logs.txt`) |
| IDE | Python IDLE |
| OS Platform | Windows |

---

## 👥 Target Users

- **Parents** — Monitor children's keyboard activity and ensure online safety
- **Employers / IT Administrators** — Track activity on company-owned systems
- **Cybersecurity Students & Researchers** — Learn how keyloggers work for ethical hacking and defensive security education
- **Forensic Analysts** — Retrieve keystroke evidence during digital investigations
- **System Administrators** — Audit and troubleshoot user behaviour on monitored systems

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/keystroke-logger.git
   cd keystroke-logger
   ```

2. **Install dependencies**
   ```bash
   pip install pynput
   ```
   > `tkinter` comes bundled with Python 3. No separate install needed.

3. **Run the application**
   ```bash
   python keylogger.py
   ```

---

## 🚀 Usage

1. Launch the application — a GUI window will appear.
2. Click **"Start Keylogger"** to begin recording.
3. All keystrokes are logged in real time to:
   - `logs.txt` (human-readable plain text)
   - `logs.json` (structured JSON)
4. Click **"Stop Keylogger"** to end the session.

---

## ⚠️ Disclaimer

This tool is built **strictly for educational and authorized monitoring purposes**. Unauthorized use of keystroke loggers to monitor individuals without their knowledge or consent is **illegal and unethical**. The author and institution are not responsible for any misuse of this software.

---

## 🙏 Acknowledgements

- **GITAM University** for academic support
- **AICTE** for the project initiative
- Open-source libraries: [pynput](https://pypi.org/project/pynput/), [tkinter](https://docs.python.org/3/library/tkinter.html)
