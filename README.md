# 🔒 Fast Secure Steganography Tool (Experimental)

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![License](https://img.shields.io/badge/License-MIT-green)

**Status:** Experimental – testing ideas for hiding data in images.

A Python tool to **securely hide text in images** using AES encryption and randomized pixel positions. Optimized for **large images** and comes with a **user-friendly GUI**.  

> ⚠️ **Warning:** This project is experimental. Use it for testing and learning purposes only. Not intended for production security.

---

## 📝 Features

- Encrypts text using **AES (Fernet) 128-bit encryption**
- Hides data in **randomized pixel positions** for better security
- **Memory-efficient**: can handle very large images without crashes
- Non-blocking **Tkinter GUI** with threading
- Supports **PNG and BMP images**
- Generates **44-character base64 Fernet keys** for encryption

---

## ⚙️ Installation

Requires **Python 3.8+** and the following libraries:

```bash
pip install pillow cryptography
