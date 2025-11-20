# 📡 Near-Field-Communication-Project

Welcome to **Near-Field-Communication-Project**, a dual-platform solution for interacting with NFC (Near Field Communication) tags and devices. This project combines the power of Web NFC and a native Android NFC reader app to offer seamless tag detection, reading, and writing capabilities.

---

## 🚀 Live Demo & Downloads

- 🌐 **Web NFC App**: [Launch Web NFC](https://web-nfc-ten.vercel.app) — interact with NFC tags directly from your browser *(Chrome for Android required)*  
- 📱 **Android NFC App**: [Download APK](./NFCApp.apk) — install the native NFC reader app for enhanced tag detection

---

## 📸 Screenshots

## Demo Screenshots

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

(A) Web NFC: Uses the experimental Web NFC API to read/write NFC tags via supported browsers.

(B) Android NFC App: A Kotlin-based mobile app built with Android Studio that supports reading and writing NDEF messages from physical NFC tags.

--- 

## 🛠️ Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: Node.js, Express

Mobile: Kotlin, Android SDK

Deployment: Vercel (for Web NFC)

---

## 📚 Topics Covered

1) NFC tag detection and reading

2) Writing NDEF messages (In Progress)

3) RFID tag compatibility

4) Web NFC API integration

5) Android NFC development

---

## 📄 License
This project is licensed under the MIT License. See license.txt for details.

---

## 🙌 Contributing
Pull requests are welcome! If you’d like to improve the app, fix bugs, or expand functionality, feel free to fork the repo and submit a PR.

---

## ✨ Acknowledgments
Thanks to the pioneers of Web NFC and the open-source Android community for making NFC development accessible and exciting.
