# 📡 Near-Field-Communication-Project

Welcome to **Near-Field-Communication-Project**, a dual-platform solution for interacting with NFC (Near Field Communication) tags and devices.  
This project combines the power of **Web NFC** and a **native Android NFC reader app** to offer seamless tag detection, reading, and writing capabilities.

---

## 🚀 Live Demo & Downloads

- 🌐 **Web NFC App** → [Launch Web NFC](https://web-nfc-ten.vercel.app)  
  *Interact with NFC tags directly from your browser (Chrome for Android required)*  

- 📱 **Android NFC App** → [Download APK](./NFCApp.apk)  
  *Install the native NFC reader app for enhanced tag detection*

---

## 📸 Screenshots

<table>
  <tr>
    <td>
      <div align="center">
        <img src="https://github.com/Kratugautam99/Near-Field-Communication-Project/blob/main/Demo/NFCapp1.png" alt="NFC App (On Not Supported Device)" width="250"/>
        <p><b>NFC App (On Not Supported Device)</b></p>
      </div>
    </td>
    <td>
      <div align="center">
        <img src="https://github.com/Kratugautam99/Near-Field-Communication-Project/blob/main/Demo/NFCapp2.png" alt="NFC App (On Supported Device)" width="250"/>
        <p><b>NFC App (On Supported Device)</b></p>
      </div>
    </td>
  </tr>
  <tr>
    <td>
      <div align="center">
        <img src="https://github.com/Kratugautam99/Near-Field-Communication-Project/blob/main/Demo/NFCweb1.png" alt="NFC Web (Instructions and Working)" width="500"/>
        <p><b>NFC Web (Instructions and Working)</b></p>
      </div>
    </td>
    <td>
      <div align="center">
        <img src="https://github.com/Kratugautam99/Near-Field-Communication-Project/blob/main/Demo/NFCweb2.png" alt="NFC Web (Source and Technical Details)" width="500"/>
        <p><b>NFC Web (Source and Technical Details)</b></p>
      </div>
    </td>
  </tr>
</table>

---

## 📦 Project Structure

```bash
near-field-communication/
├── Demo/                 # Demonstration Images
├── NFCReaderApp/         # Android NFC Reader App (Kotlin-based)
├── public/               # Static assets for Web NFC frontend
├── NFCApp.apk            # Prebuilt Android APK
├── .gitignore            # Git ignore rules
├── license.txt           # MIT License
├── package.json          # Node.js dependencies and scripts
├── server.js             # Express server for Web NFC
```

---

## 🧠 About the Project

This repository demonstrates two approaches to NFC interaction:

- **Web NFC** → Uses the experimental Web NFC API to read/write NFC tags via supported browsers.  
- **Android NFC App** → A Kotlin-based mobile app built with Android Studio that supports reading and writing NDEF messages from physical NFC tags.

---

## 🛠️ Technology Stack

| Platform | Technologies | Notes |
|----------|--------------|-------|
| **Web NFC App** | HTML, CSS, JavaScript, Node.js, Express, Vercel | Built for browsers supporting the experimental Web NFC API. Uses Node.js + Express for backend and deployed via Vercel. |
| **Android NFC App** | Kotlin, Android SDK | Native mobile app built with Android Studio. Supports reading/writing NDEF messages from physical NFC tags. Different stack from Web NFC since it leverages Android’s NFC hardware APIs. |

---

## 📖 Usage Guide

Follow these steps to get started with the project:

### 🔹 Web NFC App
1. Open [Web NFC App](https://web-nfc-ten.vercel.app) in **Chrome for Android** (Web NFC is not supported on desktop browsers).  
2. Tap your NFC tag on the back of your Android device.  
3. The app will detect and display tag information.  
4. Writing NDEF messages is currently **in progress** but reading works seamlessly.  

### 🔹 Android NFC App
1. Download the [APK file](./NFCApp.apk).  
2. Install it on your NFC-enabled Android device.  
3. Launch the app and bring an NFC tag close to your device.  
4. The app will read the tag and display its contents.  
5. Writing NDEF messages is supported for compatible tags.  

---

## 📄 License

This project is licensed under the **MIT License**. See `license.txt` for details.

---

## ✨ Acknowledgments

Thanks to the pioneers of **Web NFC** and the **open-source Android community** for making NFC development accessible and exciting.
