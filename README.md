# Duplicate-Image-Finder

The Duplicate Image Finder application is designed to assist users in identifying and managing duplicate images within a specified folder. The application can handle certain file types like JPG, JPEG, PNG, GIF, BMP, TIFF, ICO or JFIF. It has been created using Python programming language and the tkinter library for the graphic user interface (GUI). It allows users to 
1.	Select a target folder.
2.	choose a single image for comparison.
3.	find duplicates of selected image within the specified folder.
4.	display the duplicate images found in a user-friendly format.
5.	save the results in an excel file.



Key Features

  - Image Hashing: Uses dhash (difference hash) technique to quickly identify duplicate or visually similar images.

  - GUI Interface: Simple Tkinter-based GUI for easy navigation and functionality.
  
  - Excel Export: Allows users to save results in an Excel file with timestamped filenames for record-keeping.
  
  - File Compatibility: Supports multiple image formats including .jpg, .jpeg, .png, .gif, .bmp, .tiff, .ico, and .jfif.
  
  - Visual Display: Lists identified duplicates in a Treeview table for easy viewing.


Requirements

  - Software: Python 3.x

  - Modules: Imagehash, Pillow (PIL), Openpyxl, Tkinter, Collections, Datetime


The Duplicate Image Finder is particularly useful for photographers, content creators, and anyone managing large image collections, enabling them to maintain an organized library by identifying and managing duplicate images efficiently.
