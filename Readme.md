# Budget Tracking App

## Introduction

Welcome to the Budget Buddy App, a real-world budget management application built with SQLite and Expo 50. This project demonstrates the power of developing local-first applications that manage complex data structures with instant performance for CRUD operations.

### About the App

This app is designed to help users manage their finances effectively using the robustness of SQLite for data management. With its user-friendly interface and powerful backend, Budget Buddy makes budgeting simple and efficient.

Watch the app in action on my YouTube channel: [Budget Buddy App Demo](https://youtu.be/dl74XgJYK1A)

## Features

- User-friendly budget tracking
- Instant performance for CRUD operations
- Local-first data management with SQLite
- Built with TypeScript and Expo 50

## Technologies Used

- **Language:** TypeScript
- **Framework:** Expo 50
- **Database:** SQLite
- **Project Type:** Mobile

## Getting Started

To get started with this project, clone the repository and install the required dependencies.


## Step 1: Install Node.js (with npm)

Download Node.js: Visit the official Node.js website (Node.js download page) and download the LTS (Long Term Support) version for your operating system. The LTS version is more stable and is recommended for most users.
On Windows: Download the .msi installer and run it. Follow the setup wizard which will also install npm.
On macOS: Download the .pkg installer and run it. (Alternatively, you can use Homebrew with the command brew install node if you prefer.)
Install Node.js: Run the installer you downloaded and accept the defaults. This will install Node and npm on your system. (If you used a package manager or nvm, the install command will handle this for you.)
Verify the installation: After installation, open a new terminal (Command Prompt/PowerShell on Windows, Terminal on Mac/Linux) and check the versions to ensure everything is set up correctly:
```bash
node -v    # shows Node.js version
npm -v     # shows npm version
```
## Step 2: Install Expo CLI (Command Line Interface)
```bash
npm install --global expo-cli

```
## Step 3: Clone the Project Repository
```bash
git clone https://github.com/yoyoweiii/Budget-Tracking-App-Expo.git
cd Budget-Tracking-App-Expo
```
## Step 4: Install Project Dependencies
```bash
npm install
```
## Step 5: Start the Expo Development Server
```bash
expo start
```
## Step 6: Install the Expo Go app on your Android device

To run the app on your Android phone, you will use Expo Go – an app provided by Expo that can run your project’s JavaScript bundle on the phone without needing a full native build.
Download Expo Go: On your Android phone, open the Google Play Store and search for “Expo Go” (by Expo Project/650 Industries). Install the Expo Go app on your device like you would install any other app.
Launch Expo Go: Once installed, open the Expo Go app on your phone. The app will likely show a home screen with options to scan a QR code, along with any projects you might have recently opened (if any).
Sign in (optional): Expo Go does not strictly require an account to run apps in development, especially if your computer and device are on the same network. However, it might prompt you to sign in or create an Expo account (Expo accounts are free) for certain features or if you choose to use the tunnel connection. You can go ahead and create an account or sign in if you want, but for simply scanning the QR code on a local network, you should be able to continue without signing in. (If you do sign in on the Expo Go app, it must match the account you use with expo login in the CLI, but again, this isn’t necessary for LAN scanning.)
Permissions: The first time you use Expo Go to scan a QR code, it will ask for camera access (so it can use the camera to scan the code). Grant this permission. On newer Android versions, you might also need to allow Expo Go to access your local network if prompted.

## Step 7: Scan the QR code and run the app on your Android phone

Now comes the exciting part – launching the app on your phone:
Connect to the same network: Make sure your Android phone and your development computer are on the same Wi-Fi network. This is important because Expo’s default connection mode (LAN) requires both devices to communicate over the local network
docs.expo.dev
. (If you’re at home, this usually means both are on your home Wi-Fi. If you’re on a public network or your computer is on ethernet and phone on Wi-Fi, ensure the networks are bridged or use the tunnel option explained below.)
Open the scanner: In the Expo Go app on your phone, tap “Scan QR Code” (it might be a button on the home screen of Expo Go). This will open up your camera within the app.
Scan the QR code: Point your phone’s camera at the QR code displayed in your terminal (from Step 5). Align it so the QR code is fully visible and wait a moment. Expo Go should recognize the QR code, which contains a special URL for your local dev server. 📷 Tip: If your terminal text is small, you can zoom your terminal or open the Expo DevTools in the browser to see a larger QR code.
Launch the app: After scanning, Expo Go will likely prompt with a message like “Open project in Expo Go?”. Confirm any prompt to open the app. Then, the Expo Go app will connect to your development server and begin loading the JavaScript bundle. You’ll see a loading screen in Expo Go while it fetches the bundle from your computer. This may take a minute the first time. Once loading completes, the Budget Tracking App will appear on your phone! 🎉
Interact with the app: You can now use the app on your device. Any changes you make in the code will auto-refresh on the device (this is called Fast Refresh). For example, try making a simple text change in the code and watch it update live.
Troubleshooting connection issues: If scanning the QR code does nothing, or the app fails to load:
Double-check that the phone and PC are on the same network (this is a common issue)
docs.expo.dev
.
If you are on a restricted network (like a work network or public Wi-Fi that blocks device-to-device communication), the LAN connection might not work. Expo provides a workaround: restart the Expo server in tunnel mode. In your terminal, stop the current server (Ctrl+C) and run:
```bash
expo start --tunnel
```

💡 Find more resources at [codewithbeto.dev](https://codewithbeto.dev)
