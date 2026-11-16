# 📱 Portal Kampus - WebView App (Prototype 1: MIT App Inventor)

A mobile WebView prototype built using **MIT App Inventor** to display the campus portal of **Universitas Langlangbuana (UNLA)** (`https://www.unla.ac.id/`).

This repository represents **Prototype 1 (Proof of Concept)**, created with visual block-based programming prior to the native implementation in **Prototype 2 (React Native Fabric)**.

---

## 📌 Project Overview

This project was developed for the **Mobile Programming (Pemrograman Mobile)** coursework to evaluate rapid prototyping tools versus full-stack cross-platform frameworks.

* **Prototype 1 (This Repository):** Built with **MIT App Inventor** (No-code / Block-based visual framework).
* **Prototype 2:** Built with **[React Native Fabric (New Architecture)](https://github.com/luthfimeteor/TugasWebViewFabric)** with advanced navigation controls, custom top/bottom bar, and TypeScript.

---

## ✨ Features (Prototype 1)

- 🏛️ **UNLA Campus Portal**: Loads the official Universitas Langlangbuana portal (`https://www.unla.ac.id/`).
- 🌐 **WebViewer Component**: Standard webview rendering on Android using native WebKit / Chromium engine.
- 📦 **Standalone APK**: Pre-compiled Android application package (`Webview.apk`) ready for installation.
- ⚡ **Rapid Prototyping**: Fast development cycle leveraging MIT App Inventor visual block components.

---

## 📊 Comparison: Prototype 1 vs Prototype 2

| Feature / Aspect | Prototype 1 (MIT App Inventor) | Prototype 2 (React Native Fabric) |
| :--- | :--- | :--- |
| **Technology** | MIT App Inventor (Blocks) | React Native 0.87 (Fabric Architecture) |
| **Language** | Visual Block Programming / Scheme | TypeScript & React 19 |
| **Rendering Engine** | Standard Android WebView | Fabric (C++ TurboModules & JSI) |
| **Navigation Bar** | Basic / Built-in browser behavior | Custom Bottom Bar (Prev, Next, Reload) |
| **Hardware Back Button** | Standard / Default | Intercepted with native `BackHandler` |
| **Architecture** | Component-based visual flow | Component hierarchy + TypeScript typing |
| **Code Access** | Visual blocks / Exported `.apk` | Complete native source code (`android/`, `ios/`) |

---

## 📥 Installation & Testing

You can directly install the pre-compiled APK on an Android device:

1. **Download / Copy the APK**:
   Locate `Webview.apk` in the root of this repository.

2. **Enable Unknown Sources**:
   On your Android device, go to **Settings > Security / Privacy > Install unknown apps** and enable permission for your file manager or browser.

3. **Install the APK**:
   Tap `Webview.apk` and follow the prompt to install the application.

4. **Alternative via ADB (Android Debug Bridge)**:
   ```bash
   adb install -r Webview.apk
   ```

---

## 📁 Repository Structure

```
Webview-prototype-1/
├── README.md        # Project documentation
└── Webview.apk      # Compiled Android application package
```

---

## 🔗 Related Projects

- 🚀 **Prototype 2**: [TugasWebViewFabric (React Native Fabric / New Architecture)](../TugasWebViewFabric)

---

## 📄 License

Created for educational purposes under the **Mobile Programming (Pemrograman Mobile)** coursework.

