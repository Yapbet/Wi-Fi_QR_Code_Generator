# Wi-Fi QR Code Generator 📶

## Overview
A simple Python project that generates a QR code using your Wi-Fi name (SSID) and password. The QR code is saved as a PNG image and opens automatically on Windows.

## How to Run
1. Install Python.
2. Install the required library:
   ```bash
   pip install qrcode[pil]
   ```
3. Run the Python script:
   ```bash
   python main.py
   ```
4. Enter your Wi-Fi name and password.
5. Find your QR code in the `QRcode` folder.

## What You Need to Learn
- Python variables and user input
- String formatting (f-strings)
- Importing libraries
- Using the `qrcode` library
- File and folder handling with `pathlib`
- Basic operating system operations with `os`
