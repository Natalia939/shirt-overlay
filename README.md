# 👕 Shirt Overlay Image Script

A Python script that overlays a shirt image (`shirt.png`) onto another input image, resizing and fitting it perfectly.  
This project demonstrates **image processing**, **file handling**, and **Python scripting skills**.

---

## 📘 Project Overview

This script allows you to take any image (JPEG or PNG) and overlay a predefined shirt image on top of it.  
It’s a small, visual Python project that demonstrates:

- File and path handling (`os`, `sys`)
- Image processing with **Pillow (PIL)**
- Command-line interface design
- Exception handling and validation

---

## 🛠️ Features

- Validates input arguments (exactly two required: input and output image paths)
- Ensures input and output files exist and have valid extensions (`.jpg`, `.jpeg`, `.png`)
- Maintains matching extensions between input and output
- Resizes and crops the input image to match the shirt overlay
- Produces a visually appealing composite image

---

## 🧰 Requirements

- Python 3.x  
- Pillow library for image processing  

Install Pillow using pip:

```bash
pip install Pillow
