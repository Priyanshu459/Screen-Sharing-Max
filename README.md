# Screen Sharing Max User Guide

Welcome to **Screen Sharing Max**, a high-performance, zero-delay Android screen mirroring application for Windows PCs.
This guide will walk you through installing the application and setting up your Android device for mirroring.

---

## 1. Installation

1. **Locate the Installer**: Find the **Screen Sharing Max** installer file (e.g., `Screen Sharing Max.msi` or `.exe`) that you downloaded.
2. **Run the Installer**: Double-click the file to launch the setup wizard.
3. **Follow the Prompts**:
   - Give Windows permission to run the installer if prompted.
   - Click **Next** and follow the on-screen instructions.
   - The application will be installed in your `Program Files` directory by default.
4. **Finish Setup**: Once the installation is complete, a shortcut named **Screen Sharing Max** will be created on your Desktop.

---

## 2. Setting Up Your Android Phone

To allow the application to capture your phone's screen, you must enable **USB Debugging** on your Android device:

1. Open the **Settings** app on your phone.
2. Scroll down and tap on **About phone**.
3. Locate the **Build number** and tap it **7 times** quickly. You should see a message saying "You are now a developer!".
4. Go back to the main Settings menu and search for **Developer options** (or find it under System).
5. Open **Developer options**, scroll down, and turn on the switch for **USB Debugging**.
6. When prompted to "Allow USB debugging?", tap **OK**.

---

## 3. First Use

1. **Connect via USB**: Connect your Android device to your PC using a high-quality USB data cable.
2. **Allow Access**: A prompt will appear on your phone asking "Allow USB debugging for this computer?". Check "Always allow from this computer" and tap **Allow**.
3. **Launch the Application**: Run **Screen Sharing Max** from your Desktop shortcut or Start Menu.
   - *Note: On its very first run, the application requires an internet connection to download essential components (`scrcpy` binaries) in the background. It will notify you when it's ready.*
4. **Configure Settings**: Once the status shows "Ready", you can customize the stream:
   - **Resolution**: Pick up to 4K (Uses H.265 encoding for ultra-high quality).
   - **Bitrate & FPS**: Leave on "Original" or limit if you experience stuttering.
   - **Zero Delay**: Keep enabled for the absolute lowest possible latency (disables audio).
5. **Start Mirroring**: Click the **Start Mirroring** button. Your phone's screen should instantly appear on your PC monitor!

---

## Troubleshooting

- **"scrcpy not found" or "Downloading Error"**: Ensure your PC is connected to the internet during your first launch so it can fetch the necessary background dependencies.
- **"Device disconnected" or black screen**: Ensure your phone is unlocked, connected properly via USB, and that you accepted the USB debugging permission popup on the phone's screen.
- **Lag or stuttering**: If your USB cable is older, try lowering the Resolution to 1080p and the Bitrate to 8 Mbps or 4 Mbps.
