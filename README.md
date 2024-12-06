# Image Processing: Grayscale and Binary Conversion
This project demonstrates manual image processing in Python, focusing on reducing the dimensionality of images through grayscale and binary (black-and-white) transformations. It uses the Lena image, a standard in image processing research, as the input.

### Features
Grayscale Conversion: Converts a color image (RGB) into grayscale using the weighted average formula that accounts for human visual perception of colors.
Binary Conversion: Transforms a grayscale image into black-and-white (binary) based on a customizable threshold value.
The project avoids using pre-built functions for these transformations, ensuring a deep understanding of pixel-level image manipulation.

### Objectives
To learn how to manipulate images by directly processing pixel data.
To implement mathematical concepts in image processing, such as weighted averages and thresholding.
To understand the principles of dimensionality reduction in images.

### Technologies Used:
Python: Programming language for implementation.
Pillow: Library for loading, saving, and basic image handling (used only for reading and writing images).
How It Works
Input Image: The input is the Lena image (lena.jpg), a widely used image in image processing experiments.

### Grayscale Conversion:
Reads RGB values for each pixel.
Applies the formula:
Gray= 0.299⋅𝑅 +0.587⋅𝐺+0.114⋅𝐵
Creates a new image with pixel values ranging from 0 (black) to 255 (white).

### Binary Conversion:
Takes the grayscale image as input.
Applies a threshold (default: 128) to classify each pixel as black (0) or white (255).
Output Images:
A grayscale version (lena_grayscale.jpg).
A binary version (lena_binary.jpg).

### Learning Outcomes
Understanding pixel manipulation and image processing fundamentals.
Developing algorithms for grayscale and binary transformations without relying on pre-built functions.
Gaining practical experience with Python loops, conditionals, and mathematical operations.
