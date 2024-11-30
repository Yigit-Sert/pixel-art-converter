# Pixel Art Converter

This project is a simple Python application that converts images into a 35x25 pixel art format using Google Colab. Users can upload an image, convert it to pixel art, and then download the result.

## Project Description

This program allows users to upload an image and convert it into a pixel art version. The image is resized to 35x25 pixels and then enlarged to create the pixel art effect. After conversion, the user can download the pixelated image.

## Usage

1. **Go to Google Colab**:
    - You can run this project on Google Colab. Visit [Google Colab](https://colab.research.google.com/).

2. **Required Libraries**:
    - The necessary libraries (`streamlit` and `pillow`) are installed automatically in the Colab environment.

3. **Uploading an Image**:
    - The user can upload an image using the `files.upload()` function. Supported formats are PNG, JPG, and JPEG.

4. **Converting to Pixel Art**:
    - The uploaded image is resized to 35x25 pixels and then resized back to the original size, creating the pixel art effect.

5. **Viewing and Downloading the Result**:
    - Both the original image and the pixel art image are displayed side by side.
    - The pixel art image can be downloaded using the provided "Download" button.

## Code Explanation

The project follows these steps:

1. **Image Upload**:
    - The user uploads an image using the `files.upload()` function in Colab.

2. **Pixel Art Conversion**:
    - The image is resized to 35x25 pixels using the `Pillow` library. The image is then resized back to the original dimensions to create the pixel art effect.

3. **Displaying and Downloading the Result**:
    - The original image and the pixel art image are displayed using `matplotlib`.
    - The user can download the pixel art image using the download button.

## Quick Start

To run this project in Google Colab, follow these steps:

1. Open a new notebook in Google Colab.
2. Copy and paste the code into the notebook.
3. Run the code to upload an image.
4. See the pixel art version of the image and download the result.

## Required Libraries

- **Pillow**: For image processing tasks.
- **Matplotlib**: To display images in Colab.
- **Google Colab**: For file upload and download operations.

## Running the Project

1. Open the notebook in Google Colab.
2. Run the code and upload an image.
3. View the pixel art image and download it.
