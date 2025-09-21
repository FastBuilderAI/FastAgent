Here’s a clean **README.md** draft to introduce your public release binaries. It explains what FastAgent is, what the binaries do, and how to install/use them across platforms.

---

# FastAgent by FastBuilder.AI

FastAgent is a cross-platform desktop agent that connects to **FastBuilder.AI** and helps automate tasks on your computer. It integrates directly with your operating system, listens for objectives, and executes them by controlling applications, browsing, and handling workflows with the help of AI models.

---

## ✨ Features

* **Cross-platform support**: Windows, macOS, Linux
* **System tray integration** with quick controls (start, stop, reconnect)
* **Real-time socket connection** with FastBuilder.AI servers
* **Agentset management** for deploying and running agent flows
* **Task automation**: executes tasks using GPT-4o, Gemini, Claude-3, LLaVA, etc.
* **OCR & Vision support**: AI reads your screen and interacts intelligently
* **Secure authentication** via unique codes and tokens

---

## 📦 Downloads

You can download binaries for your platform:

* **Windows** – `.exe` installer
* **macOS** – `.dmg` (notarized and signed)
* **Linux** – `.AppImage` or `.deb` (depending on your distribution)

*(See the [Releases](./releases) page for the latest version.)*

---

## 🚀 Installation

### Windows

1. Download the `.exe` installer.
2. Double-click and follow the prompts.
3. After installation, FastAgent will run in the system tray.

### macOS

1. Download the `.dmg` file.
2. Drag **FastAgent.app** to your Applications folder.
3. On first run, macOS may ask for permissions (screen recording, accessibility). Grant them for full functionality.

### Linux

1. Download the `.AppImage`.

   ```bash
   chmod +x FastAgent-x86_64.AppImage
   ./FastAgent-x86_64.AppImage
   ```

   Or install via `.deb` if provided.
2. The tray icon will appear when running.

---

## 🔑 First-time Setup

1. When launched, FastAgent generates a unique link/code.
2. This link opens in your browser and connects the agent to your **FastBuilder.AI** account.
3. Once authenticated, the agent is ready to process tasks.

---

## ⚙️ Usage

* Control FastAgent via the **system tray menu**:

  * **Enable / Disable** agent
  * **Skip Task**
  * **Reconnect** if disconnected

* Tasks are received from FastBuilder.AI and executed automatically.

* Logs and actions are reported back to the server in real time.

---

## 🔒 Security & Privacy

* FastAgent communicates only with **FastBuilder.AI** servers (`https://app.fastbuilder.ai`) .
* Authentication is token-based and requires user approval.
* Clipboard and screen access are used only to complete assigned tasks.

---

## 🛠 Support

* Website: [https://fastbuilder.ai](https://fastbuilder.ai)
* Email: [help@fastbuilder.ai](mailto:help@fastbuilder.ai)
* Community: Join us on [X/Twitter](https://x.com)

---

Would you like me to also generate a **short "Quick Start" version** of this README (1–2 pages, end-user friendly), or keep this as a **developer-oriented README** with all technical details?
