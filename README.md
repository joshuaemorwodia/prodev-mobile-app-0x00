# prodev-mobile-app-0x00

## 📱 Project Setup

1. Created project directory:
   ```bash
   mkdir prodev-mobile-setup && cd prodev-mobile-setup
# 📱 First Expo Router App Setup

## 🧩 Project Setup Steps
1. Navigated to `prodev-mobile-setup`
2. Ran: `npx create-expo-app@latest .`
3. Selected Expo Router (TypeScript) template
4. Modified `app/(tabs)/index.tsx` to display "** First App Created**"
5. Ran the app with `npx expo start`
6. Scanned QR code using Expo Go on [Android / iOS]

## 🔁 Reset Project Observation

- Ran `npm run reset-project`
- Prompt: *Do you want to move existing files to /app-example instead of deleting them?*
- I chose: [Y / n]
- Observed:
  - Old files moved to `app-example` folder
  - A fresh Expo Router project was created
  - It reset the `app` folder to a clean state

## ✅ Status

Everything works. App is running on my phone. Project reset successfully.

# prodev-mobile-app-0x00

## 🚀 Scaffolding Steps
- Ran `npx create-expo-app@latest .` inside the directory.
- Selected template: **Blank**
- Confirmed that package.json and app folder were created.

## 🧪 Home Screen Modification
- Opened `app/(tabs)/index.tsx`
- Changed the `<Text>` inside the return to:
  ```tsx
  <Text style={styles.title}>** First App Created **</Text>

