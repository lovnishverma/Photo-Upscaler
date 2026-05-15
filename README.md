---
title: Photo Upscaler
emoji: 🏙️
colorFrom: indigo
colorTo: gray
sdk: static
pinned: true
short_description: Ai Image Upscaler
---

# Photo Upscaler

An AI-powered image upscaling tool designed to enhance image resolution and quality with ease. This project provides a clean, user-friendly interface for high-fidelity magnification, supporting both single and batch processing.

## 🚀 Live Demos

* **Official Website:** [lovnishverma.in/Photo-Upscaler/](https://www.lovnishverma.in/Photo-Upscaler/)
* **Hugging Face Space:** [lovnishverma-photo-Upscaler.static.hf.space](https://lovnishverma-photo-Upscaler.static.hf.space/index.html)

## ✨ Key Features

* **AI Magnification Options:** Upscale images by **2x, 4x, 6x, or 8x** using advanced AI models.
* **Batch Processing (Queue System):** Add multiple images to a queue and process them sequentially for efficiency.
* **Real-time Comparison:** Side-by-side preview of the original and the upscaled image for immediate quality assessment.
* **Drag & Drop Interface:** Simplifies the workflow with intuitive drop zones for image selection.
* **Automatic Downloads:** Features an automated download trigger once the rendering process is complete.
* **Supported Formats:** Compatible with standard image formats, including `.jpg`, `.jpeg`, `.png`, and `.bmp`.

## 🛠️ Technical Overview

The application is built as a high-performance static web app using a modern frontend stack:

* **Frontend Logic:** Pure JavaScript with specialized libraries for image processing and file management.
* **Core Libraries:**
* `jsnew_image-upscaler.js`: Core upscaling logic.
* `js_FileSaver.js`: Manages client-side file saving.
* `js_spark-md5.min.js`: Efficient MD5 hashing for file integrity.
* `js_quene.js`: Custom queue management for batch processing.


* **Styling:** Responsive UI crafted with CSS3 and Google Fonts (Poppins).

## 📖 How to Use

1. **Upload:** Use the "Upload" button or drag your image file directly onto the dashboard.
2. **Configure:** Select your preferred magnification level (2x, 4x, 6x, or 8x).
3. **Process:**
* For a single image, start the process immediately.
* Use **"Add To Queue"** to prepare multiple files, then click **"Start Queue"** to process them all at once.


4. **Save:** View the comparison and download your enhanced high-resolution image.

## 🙏 Attribution & Improvements

This project is an enhanced version of the **Qoc Upscaler** by free-videoconverter.net.

**Key Enhancements include:**

* A complete overhaul of the user interface for better usability.
* Removal of restrictive size limitation warnings.
* Integration of automated download triggers on render finish.
* Added drag-and-drop support for the "Nu Image" target.
