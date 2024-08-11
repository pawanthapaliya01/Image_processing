# Image_processing
Project: Simple Image Filter
Overview

This project demonstrated basic image processing techniques using Python and OpenCV. We loaded an image, applied grayscale and sepia filters, and detected edges using the Canny edge detector. The results were displayed using Matplotlib.
Requirements

    Python
    OpenCV
    Matplotlib
    NumPy (for the sepia filter)

The required libraries were installed using pip:
pip install opencv-python matplotlib numpy

Explanation

    Imported Libraries:
        cv2: OpenCV for image processing.
        numpy: For numerical operations (used for the sepia filter).
        matplotlib.pyplot: For plotting images.

    Function apply_sepia:
        Input: RGB image.
        Process: Applied a sepia filter using a transformation matrix.
        Output: Sepia-toned image.

    Function main:
        Loaded the Image: Read the image using OpenCV and converted it from BGR to RGB.
        Converted to Grayscale: Converted the image to grayscale for edge detection.
        Applied Filters: Applied the sepia filter and detected edges.
        Plotted Results: Used Matplotlib to plot the original, grayscale, sepia, and edge-detected images side by side.

    Executed the Script:
        The if __name__ == "__main__": block ensured that main() was executed when the script was run directly.

Usage

    Placed the script in your project directory.
    Ensured the image file (Untitled.jpeg) was in the same directory or adjusted the path accordingly.
    Ran the script to see the images processed and displayed.
