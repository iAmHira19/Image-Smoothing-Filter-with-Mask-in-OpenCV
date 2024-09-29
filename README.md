# Image Smoothing Filter with Mask in OpenCV

## Description
This project demonstrates the smoothing filtering process using OpenCV. A mask (kernel) is applied to an image to reduce noise and create a smoother appearance. The example uses a basic 3x3 averaging filter to smooth the input image.

## Features
- Load and display an image.
- Apply a 3x3 smoothing filter (mask) to the image.
- Display the original and smoothed images side by side.
- Save the smoothed image as a new file.

## Requirements
- Python 3.x
- OpenCV (opencv-python-headless)
- NumPy
- Matplotlib (for displaying images)

## Installation
1. Install required packages:
    ```bash
    !pip install opencv-python-headless matplotlib numpy
    ```

2. Upload an image to Colab to process.

## Usage
- Upload the image you want to smooth.
- Run the code in Google Colab or any Python environment supporting OpenCV.
- The script will apply the smoothing filter using a mask and display the results.

## Code Explanation
The smoothing filter uses a 3x3 kernel mask, where each value in the kernel is \( \frac{1}{9} \). This creates an averaging filter that smooths the image by computing the average pixel value from the neighborhood around each pixel.

The convolution is performed using OpenCV’s `filter2D` function.

## Example Output
- **Original Image**: Displays the original, unprocessed image.
- **Smoothed Image**: Displays the image after the smoothing filter is applied.

## Contributing
Feel free to fork the repository, create issues, or submit pull requests with improvements or new features.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
