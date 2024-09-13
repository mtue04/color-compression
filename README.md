# Project 01: Applied Mathematics &amp; Statistics for IT

## Overview
This project, Color Compression, aims to reduce the number of colors in an image using the K-Means clustering algorithm. The compression is achieved by grouping similar colors and replacing them with cluster centroids. The implementation uses the Python programming language along with libraries such as NumPy, PIL (Pillow), and matplotlib to handle image processing tasks.

## Prerequisites
The project relies on the following Python libraries:
  - numpy
  - PIL (Pillow)
  - matplotlib

You can install the required libraries using:
`pip install numpy pillow matplotlib`

## How to Run
1. Clone the repository and navigate to the project directory.
2. Prepare the images to compress and place them in the images/ folder.
3. Run cells in Jupyter file `22127440.ipynb`

## Features
  - Mini Batch K-Means: The script uses the Mini Batch K-Means algorithm for faster processing, especially with large images.
  - Adjustable Color Clusters: Users can specify the number of colors to compress the image to.
  - Supports Multiple Formats: The output can be saved in formats such as PNG, JPG, or PDF.
