# 🤖 JARVIS AI Assistant

**A personal AI-powered voice assistant for Windows with a futuristic dashboard and desktop automation.**

JARVIS is a desktop assistant project designed to make everyday computer interactions easier through voice commands, AI-powered responses, and automation.

This repository contains a modified version of the original **MARK 56 — JARVIS** project by FatihMakes.

---

## ✨ Features

- 🎙️ **Voice Interaction** — Interact with the assistant using voice commands.
- 🧠 **AI-Powered Responses** — Connect to a supported AI provider for conversational responses.
- 🖥️ **Desktop Dashboard** — Use a futuristic interface to interact with JARVIS.
- 🌐 **Web Automation** — Open websites and perform supported web-related actions.
- 📂 **File and Folder Access** — Intended to support file and folder operations where configured and permitted.
- 🔊 **Text-to-Speech** — Hear spoken responses from the assistant.
- 🎵 **Media Interaction** — Support for compatible media-related commands.
- 🐍 **Python-Based** — Built using Python and supporting libraries.
- ⚙️ **Customizable** — Modify the interface, commands, and supported integrations.

> Feature availability depends on the installed version, configuration, connected AI provider, and operating system permissions.

---

## 🛠️ Technologies Used

- Python
- Eel
- OpenCV
- SpeechRecognition
- PyAudio
- pyttsx3
- PyAutoGUI
- Pygame
- PyWhatKit
- HTML, CSS, and JavaScript

Some features may require additional packages, credentials, or system dependencies.

---

## 💻 System Requirements

- Windows 10 or Windows 11
- Python version compatible with the project's dependencies
- Microphone for voice commands
- Speakers or headphones for spoken responses
- Internet connection for online services and web-related features
- Additional credentials for AI services, if required

---

## 📥 Installation

### 1. Clone the Repository

Open Command Prompt and run:

```bash
git clone https://github.com/mjakbar1210-warrior/JARVIS-AI-ASSISTANT.git
```

### 2. Open the Project Directory

```bash
cd JARVIS-AI-ASSISTANT
```

### 3. Create a Virtual Environment

```bash
py -3.11 -m venv .venv
```

Activate it:

```bash
.venv\Scripts\activate
```

If Python 3.11 is not installed, install a compatible Python version based on the project's dependencies.

### 4. Install Dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

If a dependency fails to install, consult its documentation and the project's setup instructions.

### 5. Configure Credentials

Configure any required API keys or service credentials using the project's supported configuration method.

**Security reminder:** Never upload API keys, passwords, access tokens, or private credentials to GitHub.

### 6. Run JARVIS

If the project uses `main.py` as its entry point:

```bash
python main.py
```

Alternatively, if the project provides a launcher:

```bash
start_jarvis.bat
```

Use the startup method documented for your installed version.

---

## 🎙️ How to Use

1. Start the JARVIS application.
2. Allow microphone access if prompted.
3. Wait for the voice-recognition system to initialize.
4. Speak a supported command.
5. Listen to the assistant's response.
6. Use the dashboard to access the features available in your installation.

Examples of intended commands include:

- Open a supported website.
- Ask a general question.
- Request a supported desktop action.
- Perform a supported media-related action.

The exact commands depend on the implemented features and configuration.

---

## 📂 Project Structure

The project may contain the following components:

```text
JARVIS-AI-ASSISTANT/
│
├── actions/        # Desktop and system actions
├── config/         # Application configuration
├── core/           # Core assistant functionality
├── dashboard/      # User interface
├── memory/         # Assistant memory components
├── plugins/        # Optional integrations
├── providers/      # AI provider integrations
├── main.py         # Main application entry point
├── start_jarvis.bat
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

The actual folder structure may vary by version.

---

## 🔒 Privacy and Security

- Keep API keys and credentials private.
- Review file-access and desktop-automation permissions.
- Avoid granting unnecessary administrator privileges.
- Review commands before allowing the assistant to modify or delete files.
- Be careful when using third-party AI services that may process your prompts or data.
- Check `.gitignore` before committing project files.

---

## 🚧 Limitations

- Voice recognition may be affected by background noise and microphone settings.
- Some features require an active internet connection.
- AI-provider availability and usage limits may affect responses.
- Certain desktop actions may require additional configuration.
- Compatibility depends on the operating system, Python version, and installed dependencies.

---

## 🔮 Future Improvements

Potential areas for further development include:

- Improved voice recognition and response speed.
- More reliable file and folder operations.
- Expanded desktop automation.
- Better conversation memory.
- Offline AI integration.
- Android phone integration.
- Customizable dashboard themes.
- Additional plugins and productivity tools.

These are potential improvements and are not necessarily implemented in the current version.

---

## 🙏 Credits and Attribution

This repository is based on the original **MARK 56 — JARVIS** project by **FatihMakes**.

The original project identifies its license as **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.

Original license information:

https://creativecommons.org/licenses/by-nc/4.0/

Please review the original project's license and attribution requirements before redistributing the project or publishing modifications. Commercial use is not permitted under CC BY-NC 4.0 unless separately authorized.

---

## 📜 License

Refer to the [`LICENSE`](LICENSE) file for the applicable license terms.

---

## 👨‍💻 Maintainer

**JARVIS AI Assistant**

GitHub: https://github.com/mjakbar1210-warrior/JARVIS-AI-ASSISTANT

---

⭐ If you find this project interesting, consider starring the repository on GitHub.
