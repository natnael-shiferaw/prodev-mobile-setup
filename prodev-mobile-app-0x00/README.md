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

## Creating Your First Mobile App

### 1. Navigate to Your Project Directory
```sh
cd prodev-mobile-setup
```

### 2. Set Up Your Project
Initialize a new Expo project using the latest Expo Router template:
```sh
npx create-expo-app@latest .
```

### 3. Modify the Home Screen
Open `app/(tabs)/index.tsx` and locate the default text `Welcome!`. Change it to:
```tsx
** First App Created **
```

### 4. Run and Test Your Application
Start the Expo development server:
```sh
npx expo start
```
- **For iOS Devices:** Scan the QR code in the terminal using your phone’s Camera app.
- **For Android Devices:** Scan the QR code using the Expo Go app.

### 5. Reset the Application
Run the reset command and observe its effects:
```sh
npm run reset-project
```

### Observations from Resetting the Project
- The reset command clears cached files and resets dependencies.
- It removes `node_modules` and `package-lock.json`, ensuring a fresh installation.
- If any dependencies were outdated or incorrectly installed, they are reinstalled.
- The project returns to a clean state, similar to a fresh installation.

## Challenges and Resolutions
| Issue | Resolution |
|-------|-----------|
| `expo command not found` | Ensure Node.js and npm are installed. Run `npm install -g expo-cli` again. |
| App not loading on Expo Go | Ensure your device and PC are on the same Wi-Fi network. Restart Expo. |
| `Permission Denied` error | Try running `sudo npm install -g expo-cli` (Linux/macOS) or open terminal as Administrator (Windows). |

## Conclusion
Your mobile development environment is now set up! 🚀 You have successfully scaffolded your first Expo Router project, modified the home screen, tested your app, and reset the project.

---
**Repository Structure:**
```
prodev-mobile-setup/
  ├── mobile-development-setup/
  │   ├── README.md (this file)
  │   ├── ... (other setup files)
  ├── prodev-mobile-app-0x00/
  │   ├── README.md
  │   ├── app-example/
  │   │   ├── app/(tabs)/index.tsx
  │   │   ├── constants/Colors.tsx
```
