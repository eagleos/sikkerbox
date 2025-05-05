# SikkerBox

[中文文档](./README_CN.md)

## Overview

SikkerBox is a cross-platform multi-platform network toolkit that simultaneously supports Android, ios, macos, and windows access, and will realize the following functions:
(1) 2FA authentication function of Microsoft Authenticator authentication class APP, allowing adding github and other information to realize 2FA authentication.
(2) Ping diagnostic function based on user input domain name or IP.
(3) Domain whois query function.
(4) DNS reverse lookup function.
(5) IP calculator function.
(6) Virtual Hosts function, according to the user from the device to select the hosts file, or edit the hosts file, and set the switch to enable the function, to realize the network access priority read the hosts file.

Currently, the function of point (1) above has been realized, i.e., it realizes secure two-factor authentication (2FA), which can generate time-based one-time passwords (TOTP) for your online accounts, and provides a powerful and user-friendly extra security layer solution for your digital life.

## 2FA Features

- **Secure Storage**: All account secrets are encrypted and stored securely using Hive database
- **QR Code Scanning**: Easily add accounts by scanning QR codes
- **Manual Entry**: Support for manually entering account information
- **Time-Based OTP**: Generate time-based one-time passwords (TOTP) compliant with RFC 6238
- **Offline Access**: Works completely offline after setup
- **Multi-Platform Support**: Available for Android, iOS, Windows, macOS, Linux, and web
- **Copy to Clipboard**: Quick copy functionality for easy code entry
- **Error Handling**: Robust error handling with detailed logging
- **Minimalist UI**: Clean, intuitive interface focused on usability

## 2FA Technical Details

SikkerBox is built using Flutter and follows these key principles:

- **Security First**: No data is transmitted to any server; all data remains on your device
- **Privacy Focused**: No analytics or tracking
- **Open Source**: Transparent codebase available for review
- **Modern Architecture**: Utilizes Provider pattern for state management
- **Clean Code**: Well-structured codebase with clear separation of concerns

## Getting Started

### Installation

Currently temporarily provide android apk installation package, just directly download the apk and install it.

## Acknowledgments

- The Flutter team for their excellent framework
- All the package maintainers whose work made this project possible

![sikkerbox app software screenshots 1](./sikkerbox1.jpg)
![sikkerbox app software screenshots 2](./sikkerbox2.jpg)
![sikkerbox app software screenshots 3](./sikkerbox3.jpg)
![sikkerbox app software screenshots 4](./sikkerbox4.jpg)
![sikkerbox app software screenshots 5](./sikkerbox5.jpg)
![sikkerbox app software screenshots 6](./sikkerbox6.jpg)
