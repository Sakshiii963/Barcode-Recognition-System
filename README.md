# Barcode-Recognition-System
A Python-based project using OpenCV and Pyzbar to detect and decode barcodes in real-time from webcam feeds or uploaded images. Features an intuitive Tkinter GUI, preprocessing for enhanced accuracy, and automatic handling of detected URLs. Ideal for retail, inventory, and logistics applications.


Features
Real-time Scanning: Detects and decodes barcodes from webcam feeds.
Image Upload Support: Processes uploaded images to extract barcode data.
Preprocessing: Grayscale conversion, Gaussian blur, and edge detection for improved accuracy.
User-Friendly Interface: Built using Tkinter for intuitive interaction.
Automatic URL Handling: Opens detected URLs in the default browser.
Error Handling: Provides user feedback for issues like unreadable images or missing barcodes.


Usage
python main.py

Choose between:
Scan via Webcam: Real-time barcode detection from a webcam feed.
Browse Image: Select an image file to process and extract barcode data.


Dependencies
Python 3.x
OpenCV
Pyzbar
NumPy
Tkinter (standard library)
Pillow


