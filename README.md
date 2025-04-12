# SATAN IB TOOL

A powerful fb inbox server for Termux with a stylish UI, 90-day OTP-based authentication system, and multi-file support for tokens, messages, and haters. Contact me on facebook for activation :- Facebook -> https://www.facebook.com/legendsatan

![Banner](https://img.shields.io/badge/version-5.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-Termux%20%2F%20Android-green.svg)
![Status](https://img.shields.io/badge/status-Active-brightgreen.svg)

---

## Features

- OTP-based secure access (valid for 90 days)
- Hater & Hero names in customized fonts
- Clean bordered UI for inputs and file selections
- Facebook Graph API based message bombing
- Token rotation, speed control & restart loop
- Stylish logs with timestamped delivery
- Activation expiry auto-handling

---

## Termux Setup

Install all dependencies:

```bash
pkg update && pkg upgrade -y
pkg install python git -y
pip install requests pyfiglet colorama
