# Wallpaper Studio

> A sleek, cross-platform wallpaper discovery and management application built with React Native and Expo.

[![React Native/Expo](https://img.shields.io/badge/React%20Native-Expo-blue)](https://expo.dev)
[![Tauri](https://img.shields.io/badge/Tauri-Desktop-orange)](https://tauri.app)

---

## 📱 Overview

### ✨ Key Features

- **Curated Wallpaper Library** – Browse a vast selection of high-quality, handpicked wallpapers.  
- **Category-Based Organization** – Explore wallpapers by themes such as Nature, Abstract, Minimalist, and more.  
- **Favorites System** – Save your preferred wallpapers for quick and easy access.  
- **Live Preview** – Preview wallpapers on your device before setting them as background.  

---

## 🚀 Getting Started

![Screenshot](./assets/images/desktop-screenshot.PNG)

### 🧩 Prerequisites

Ensure the following are installed on your system:

- **Node.js** v22 or newer  
- **npm** package manager  
- **Expo CLI** (automatically installed with dependencies)  
- **For Desktop Builds (Windows only):**  
  - Visual Studio Build Tools  
  - Rust  
  - WebView2  

---

### 🎥 Demo

- [Figma Design](https://www.figma.com/design/WnHFPfZ7uW2vxy4sHqtb12/MOBILE-WALLPAPER-SELECTOR?node-id=0-1&p=f&t=PR89JrUj7x5b5vNS-0)
- [Video Demo](https://drive.google.com/file/d/1d03D8NPeELyK4K9WwN--MT3W9hIEQPLc/view?usp=drive_link)  
- [Live Preview](https://mobile-wallpper-desktop-v2-app-r67h.vercel.app)  

---

### ⚙️ Installation

```bash
# Clone this repository
git clone https://github.com/Promisead/mobile_wallpper_desktop_v2_app.git
cd wallpaper-studio

# Install project dependencies
npm install

# Start the development environment
npm start
```

---

### 🧭 Running on Multiple Platforms

```bash
# Run on Android
npm run android

# Run on iOS (macOS required)
npm run ios

# Run in the browser
npm run web

# Run desktop build (requires Rust)
npm run tauri:dev
```

---

## 🎨 Tech Stack

### 🌐 Frontend

- **[Expo + TypeScript](https://expo.dev)** – Framework for universal React Native apps.  
- **[React Native](https://reactnative.dev)** – Core framework for mobile UI development.  
- **[NativeWind](https://www.nativewind.dev)** – Tailwind CSS integration for React Native styling.  

### 💻 Desktop

- **[Tauri](https://tauri.app)** – Lightweight desktop framework for multi-platform apps.  
- **[Rust](https://www.rust-lang.org)** – System-level programming language powering Tauri.  

---

## 📦 Production Build

### 📱 Mobile Builds

```bash
# iOS (macOS required)
npm run build:ios
# Outputs a build for the Apple App Store

# Android
npm run build:android
# Outputs APK or AAB for Google Play
```

---

### 🌍 Web Build

```bash
npm run web:build
# Generates static files in the dist/ directory
# Ready for deployment to Netlify, Vercel, or any static host
```

---

### 🖥️ Desktop Build

```bash
# Build desktop version for your OS
npm run tauri:build

# Example output:
# Windows: src-tauri/target/release/bundle/msi/
```

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Promise Champion**  
*Developer & Project Creator*  
- [GitHub](https://github.com/Promisead)  
- [Portfolio](https://ai-promise.vercel.app)

---

## 🙏 Acknowledgments

- Mentors and peers from **HNG** for continuous guidance.  
- Wallpaper resources sourced from [Unsplash](https://unsplash.com).  
- UI inspiration drawn from modern wallpaper applications.  
- Built using [Expo](https://expo.dev) and [Tauri](https://tauri.app).  

---

> Made with ❤️ by [Promise Champion](https://ai-promise.vercel.app)
