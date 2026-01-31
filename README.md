# README: VPN Protocol for Bypassing Network Restrictions

## 🛡️ About This Project

This project provides a **VPN protocol designed to bypass network restrictions and censorship**, with an upcoming Android application implementation. The protocol is engineered to deliver stable, secure, and resilient access to restricted resources.

## 📁 Repository Structure

- **[`/protocol/`](./protocol/)** — Source code and specification for the VPN protocol.
    - **[Protocol Logic](./protocol/logic.md)** — Detailed documentation of the protocol's operation, including its obfuscation, encryption, and traffic routing mechanisms.
    - **[Protocol Architecture](./protocol/architecture.md)** — Component interaction diagrams and data flow specifications.

- **[`/android/`](./android/)** — **Coming Soon**: Source code for the Android client application.
    - The application will be based on a modified version of [SocksTun](https://github.com/heiher/sockstun) — a lightweight and efficient `tun2socks` implementation for Android.
    - It will provide a user-friendly interface for managing the VPN connection.

## 🔧 Core Protocol Features

### Advanced Obfuscation & Anti-Censorship
- **Traffic Obfuscation:** Masks VPN traffic to resemble standard HTTPS or other benign protocols.
- **Dynamic Port/Protocol Switching:** Adapts connection methods to evade deep packet inspection (DPI) and blocking.
- **Resilient Architecture:** Designed to withstand common censorship techniques and maintain connection stability.
- **Adaptive Algorithms:** Adjusts strategies based on detected network environments and restriction types.

### Security & Privacy
- End-to-End Encryption for all tunnelled data.
- Secure User Authentication.
- Protection against fingerprinting and protocol detection.
- Regular cryptographic key rotation.

## 📱 Upcoming Android Application

### Built on SocksTun
The Android app will integrate our custom VPN protocol using a enhanced fork of [heiher's SocksTun](https://github.com/heiher/sockstun), offering:
- Seamless integration with our obfuscation protocol.
- An improved, intuitive user interface.
- Granular connection controls and settings.
- Connection quality monitoring and diagnostics.

### Planned Application Features
- One-tap connect/disconnect.
- Server selection for optimized speed and reliability.
- Data usage statistics.
- Per-application VPN routing (split tunneling).
- Auto-reconnect and kill-switch functionality.

## 🚀 Development Status

### Current Phase
1.  ✅ **VPN Protocol Core:** Actively under development.
2.  ⏳ **Android Client Application:** Source code will be added to this repository soon.

### Dependencies
- For the protocol: Standard cryptographic libraries.
- For the Android app: Modified SocksTun core, Android SDK.

## 📄 License

This project will be released under a GPL v3.

---
*The Android application source code will be available in this repository shortly. Stay tuned for updates!*
