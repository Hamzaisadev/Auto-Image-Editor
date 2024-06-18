Auto Image Editor Documentation
Introduction

The Auto Image Editor is a Python application designed for basic image editing tasks. It provides a user-friendly interface for manipulating and enhancing images. This documentation outlines the application's functionalities, installation process, usage guide, and code structure.

Features

Open and display images in various formats (JPG, JPEG, PNG, GIF, BMP).
Resize images to fit the canvas.
Rotate images clockwise by 90 degrees.
Flip images horizontally.
Draw on the image with a customizable pen size and color.
Undo the last edit action.
Save edited images to a user-specified location.
Apply various image filters:
HDR (High-Dynamic-Range)
Smoothing (Gaussian Blur)
Sharpening
Grayscale
Emboss
Enhance (Edge Enhancement)
Technology Stack

Programming Language: Python
GUI Library: Tkinter, customtkinter (extension)
Image Processing Library: Pillow (PIL Fork)
System Requirements

Operating System: Windows, macOS, Linux (with compatible Python installations)
Python Version: 3.x (not specified)
Installation

Prerequisites:

Ensure you have Python version 3.x installed on your system. Download and install Python from the official website: https://www.python.org/downloads/.

Package Installation:

Open a terminal or command prompt and run the following command to install the required libraries using pip:

Usage

Launching the Application:

Double-click the application script (e.g., auto_image_editor.py) to launch the Auto Image Editor.

Basic Workflow:

Click the "Upload" button to open an image file.
Utilize the editing tools and filters available on the interface to modify the image as desired.
Click the "Save" button to save the edited image to a preferred location.
Code Structure

The application code is well-organized, with functionalities separated into functions for better maintainability. Here's a breakdown of the main components:

Global Variables: Define application-wide variables like canvas size, image path, etc.
Functions:
Image manipulation functions (open, rotate, flip, etc.)
Drawing functionality (draw event handler)
Undo functionality
Color selection for drawing pen
Saving edited image
Filter application functions (HDR, smooth, sharpen, etc.)
Layout: Creates the GUI elements using frames, canvas, and custom buttons.
Main Loop: Starts the Tkinter event loop for user interaction.
Customization

The code offers some customization options:

You can add new image filters to expand the editing capabilities.
Existing filters and editing tools can be modified to achieve different effects.
The GUI appearance (colors, fonts, etc.) can be adjusted to personalize the experience.
Further Development

There's potential for further development in several areas:

Implementing more advanced image editing features (cropping, resizing, etc.).
Optimizing performance for handling larger images.
Adding support for additional image formats.
Creating a comprehensive user manual for detailed instructions.
Contributing

Currently, contributions are not actively sought. However, you're welcome to reach out if you have suggestions or bug reports.

License

The Auto Image Editor is distributed under the MIT License. You can find the license details within the source code repository.

Contact

For any questions or feedback, feel free to create an issue on the GitHub repository.

Additional Notes

This documentation serves as a general guide. Refer to the source code for a complete understanding of the application's functionalities.
Consider including screenshots of the application interface in the future for better visualization.
