# 🛡️ PixelVault - Image Steganography Tool

**PixelVault** is a steganography application that hides and retrieves secret messages within image files using the Least Significant Bit (LSB) technique. It provides a user-friendly GUI built with Tkinter, allowing users to encode and decode messages securely in `.png`, `.jpg`, and `.jpeg` image formats.

---

## 🎯 Features

- 🔐 **Secure Message Encoding** in image pixels
- 📷 **Support for PNG/JPG/JPEG** image formats
- 🧠 **Intuitive GUI** using Python's Tkinter library
- 🎨 **Colorful and Elegant Interface**
- 📥 **Browse & Save** images using file dialogs
- 📤 **Message Decoding** from any previously encoded image

---

## 📸 Screenshots

> Add screenshots here after running the GUI:
- Encode screen with message
- Decoded message output

---

## 🛠️ How It Works

This tool modifies the **Least Significant Bit (LSB)** of pixel values to store message bits. An end-of-message marker (`11111110`) ensures accurate decoding.

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.10 or higher
- `Pillow` library for image processing

Install dependencies:
```bash
pip install pillow
