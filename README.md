# Image Zipper

A Python script to validate, resize, and compress images into a ZIP file. This script ensures that images meet specific requirements such as format, size, and aspect ratio, making it ideal for preparing image batches for systems with strict import requirements.

## Description

The Image Zipper script automates the process of validating and preparing image files for import into systems that require specific image attributes. It checks each image for the correct format, size, and aspect ratio, resizing them if necessary. The script then compresses the validated images into a single ZIP file, ready for upload.

### Features

- **Validation**: Ensures images meet the specified format (JPG, JPEG, PNG), size range, and aspect ratio.
- **Resizing**: Automatically resizes images to 240x320 pixels if they do not meet the size requirements.
- **Compression**: Compiles all validated and resized images into a ZIP file, without any subfolders.
- **User-Friendly**: Provides clear console output for any issues encountered during processing.

## Requirements

- Python 3.x
- Pillow library

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/image-zipper.git
   cd image-zipper
