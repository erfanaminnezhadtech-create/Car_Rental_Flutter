# 🚗 Car Rental App (Flutter Web)

This project is a **Car Rental App** built with **Flutter** and deployed as a **Web / PWA** application. The provided file (`index.html`) serves as the entry point for the web version.

---

## 📌 Project Overview

**Car Rental App** is a modern web application for managing and booking cars, with **Progressive Web App (PWA)** support, allowing it to run on both desktop and mobile browsers.

---

## 🛠️ Technologies Used

* **Flutter (Web)**
* **Dart**
* **HTML5**
* **Service Worker (PWA)**

---

## 📁 Web File Structure

```
web/
├── index.html          # Main HTML file
├── main.dart.js        # Compiled Flutter output
├── manifest.json       # PWA configuration
├── flutter_service_worker.js
├── icons/
│   └── Icon-192.png
└── favicon.png
```

---

## 🌐 index.html Explanation

The `index.html` file includes:

* `base href` for the correct app path
* Metadata for browser and iOS compatibility
* **PWA activation** via Service Worker
* Loading of `main.dart.js`

---

## 🚀 Running the Project

### Prerequisites

* Install **Flutter SDK**
* Enable **Flutter Web**

```bash
flutter config --enable-web
```

### Run on Browser

```bash
flutter run -d chrome
```

### Build Web Version

```bash
flutter build web
```

After building, the output files will be located in:

```
build/web/
```

---

## 📱 PWA Support

This project supports PWA, which means:

* Can be installed on mobile and desktop
* Can run offline (if caching is implemented)
* Provides a mobile-app-like experience

---

## ✨ Project Name

```text
Car Rental App
```

---

## 📄 License

This project is created for educational and development purposes. Specify a license for commercial use.

---

## 👨‍💻 Developer

* Flutter Developer
* Web & Mobile Application
