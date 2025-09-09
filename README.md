# libraries
 Image Fetcher Script - README
=====================================

Description:
------------
This Python script downloads an image from a user-provided URL
and saves it inside a "Fetched_Images" directory. It ensures the
directory exists before saving and handles errors gracefully.

Usage:
------
1. Run the script:
   python fetch_image.py

2. Enter an image URL when prompted:
   Example: https://example.com/sample.jpg

3. The image will be saved in the "Fetched_Images" folder.

Features:
---------
- Creates "Fetched_Images" directory if it doesn't exist
- Downloads and saves image with original filename
- Handles invalid URLs, timeouts, and failed connections
- Provides fallback filename if extraction fails

Requirements:
-------------
- Python 3.x
- `requests` library
  Install with: pip install requests

Example:
--------
$ python fetch_image.py
Enter the image URL: https://example.com/pic.png
✅ Image successfully downloaded and saved as: Fetched_Images/pic.png

Author:
-------
Aluchery
"""
