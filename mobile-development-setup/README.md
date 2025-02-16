# Mobile Development Setup

## Introduction
This repository documents the setup process for a React Native mobile development environment using Expo, TypeScript, and NativeWindCSS. The goal is to ensure a smooth development experience for cross-platform mobile applications.

## Prerequisites
Before proceeding, ensure you have the following installed:

- **Node.js LTS** (Check version: `node -v`)
- **VS Code** (Recommended IDE)
- **Expo CLI** (Install globally using `npm install -g expo-cli`)
- **A compatible OS** (Windows, macOS, or Linux)
- **Expo Go** installed on a physical device (Android/iOS)

## Steps to Set Up the Environment

### 1. Install Node.js LTS
Download and install the latest LTS version of Node.js from [Node.js official site](https://nodejs.org/). Verify installation:
```sh
node -v
```

### 2. Install VS Code
Download and install [VS Code](https://code.visualstudio.com/). Recommended extensions:
- ES7+ React/Redux/React-Native snippets
- Prettier (for code formatting)
- Tailwind CSS IntelliSense (for NativeWindCSS support)

### 3. Install Expo CLI
Expo CLI simplifies React Native development. Install it globally:
```sh
npm install -g expo-cli
```
Verify installation:
```sh
expo --version
```

### 4. Install Expo Go on Your Device
Expo Go allows you to test your app on real devices:
- **Android:** Install from the [Google Play Store](https://expo.dev/go)
- **iOS:** Install from the [Apple App Store](https://expo.dev/go)

After installation, open Expo Go and sign in or create an account.

### 5. Create a New Expo Project
Navigate to your preferred directory and create a new Expo project:
```sh
npx create-expo-app myApp --template
cd myApp
```

### 6. Start the Development Server
Run the following command to start the development server:
```sh
npx expo start
```
Scan the QR code using Expo Go to run the app on your physical device.


## Conclusion
Your mobile development environment is now set up! 🚀 You can now proceed with building and testing React Native applications using Expo, TypeScript, and NativeWindCSS.

---
