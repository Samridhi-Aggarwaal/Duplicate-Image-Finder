# Duplicate-Image-Finder

This application is a graphical tool built using Python and Tkinter to find duplicate images in a folder based on image hash matching. The app allows users to select a folder and an individual image to search for duplicates or visually similar images. It supports a variety of image formats and provides an easy-to-use interface to browse folders and files.

Key Features
  Image Hashing: Uses dhash (difference hash) technique to quickly identify duplicate or visually similar images.
  GUI Interface: Simple Tkinter-based GUI for easy navigation and functionality.
  Excel Export: Allows users to save results in an Excel file with timestamped filenames for record-keeping.
  File Compatibility: Supports multiple image formats including .jpg, .jpeg, .png, .gif, .bmp, .tiff, .ico, and .jfif.
  Visual Display: Lists identified duplicates in a Treeview table for easy viewing.

Requirements
  Software: Python 3.x
  Modules: imagehash, Pillow (PIL), openpyxl, Tkinter

The Duplicate Image Finder is particularly useful for photographers, content creators, and anyone managing large image collections, enabling them to maintain an organized library by identifying and managing duplicate images efficiently.
