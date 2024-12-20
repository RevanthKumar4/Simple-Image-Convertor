﻿# Simple-Image-Convertor

Project Overview: This is a simple file converter application built using Python's Tkinter and PIL (Python Imaging Library). The goal of the project is to allow users to convert images from JPEG format to PNG format. The application provides a simple graphical user interface (GUI) for the user to interact with, select files, and save the converted image in a preferred location.

Key Features:

**GUI Interface:**

The application uses Tkinter for the GUI, creating a window with an "Import JPEG File" button and a "Convert JPEG to PNG" button.
The window is styled with a custom background color and fonts, creating a user-friendly experience.

**Import JPEG File:**

Users can import a JPEG file from their system using the "Import JPEG File" button.
The file is opened using the PIL.Image module, which is part of the Python Imaging Library.

**Convert to PNG:**

Once a JPEG image is imported, users can convert it to PNG format using the "Convert JPEG to PNG" button.
The application allows users to choose where to save the converted PNG file.

**Error Handling:**

The program checks if an image is selected before performing the conversion. If no image is selected and the user tries to convert, an error message box appears to alert them.
