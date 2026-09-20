# 02.ASCII_ART
### Image to ASCII Art Converter

The **Image to ASCII Art Converter** is a Python-based image processing project that converts digital images into text-based ASCII art. The application uses **OpenCV** to read, convert, resize, and process images in grayscale, while **NumPy** is used to perform numerical operations on the image data.

The program analyzes the brightness of individual pixels and categorizes them into different intensity levels using predefined thresholds. Each intensity level is then represented by a specific ASCII character such as `#`, `-`, `*`, `.`, `+`, and `o`. The processed characters are printed row by row in the terminal, creating a simplified text-based representation of the original image.

The image is resized before conversion to reduce the number of characters and make the generated ASCII art suitable for displaying in a terminal or command prompt. Users can provide an image path through the command line, while a default sample image is used when no path is specified.

**Technologies Used:** Python, OpenCV, NumPy

**Key Features:**

* Converts images into ASCII art.
* Supports grayscale image processing.
* Automatically resizes images for terminal display.
* Uses brightness thresholds to map pixels to ASCII characters.
* Accepts custom image paths through command-line arguments.
* Provides a lightweight example of basic digital image processing.

This project demonstrates fundamental concepts of **image processing, grayscale conversion, image resizing, pixel intensity analysis, thresholding, NumPy arrays, and command-line programming** in Python.

