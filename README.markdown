# Colour Finder

## Description

This project analyzes an image to identify its dominant colors using OpenCV and NumPy. It displays the top three dominant colors and the most dominant color in separate windows, providing a simple tool for color analysis in images, useful for design or artistic purposes.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)

## Usage

1. Run the script: `python colour_finder.py`
2. Enter the path to an image file (e.g., `image.jpg`).
3. The script will display the original image, a window showing the top three dominant colors, and another window showing the most dominant color.

## Download Link

- [Download colour_finder.py](https://github.com/username/Python-Projects/raw/main/colour_finder.py)

## Notes

- Ensure the image path is correct; the script will exit if the path is invalid.
- The script may fail with unsupported image formats; use common formats like JPG or PNG.
- Results depend on the image’s color distribution; complex images may yield less accurate dominant colors.
- The color display windows are 300x300 pixels; close them to end the program.