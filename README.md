# Edge Detection Operators in Computer Vision

This script demonstrates different edge detection techniques in Computer Vision using OpenCV and Python. It applies Sobel, Prewitt, and Canny edge detection operators to a grayscale image and compares the results.

## Prerequisites

Ensure you have the required Python libraries installed:

    pip install opencv-python matplotlib numpy

## How to Use

1. Update the image path in the script. It currently reads from `/content/drive/MyDrive/Michael_Jackson_-_Thriller.png`. Change this to your local image path:
       
       img = cv2.imread('path/to/your/image.png', 0)
       
2. Run the script in your terminal or Python environment.
### Note: You can directly open the `.ipynb` file in Colab or Jupyter Notebook.

## How it Works

1. **Sobel Edge Detection**: Uses the `cv2.Sobel` function to compute the horizontal and vertical gradients of the image, which are then combined using `cv2.magnitude`.
2. **Prewitt Edge Detection**: Manually creates the Prewitt kernels (horizontal and vertical) and applies them using `cv2.filter2D`, then combines them.
3. **Canny Edge Detection**: Uses the advanced `cv2.Canny` function for hysteresis-based robust edge detection.
4. **Visualization**: Uses Matplotlib to display a 2x2 grid comparing the original image against the three edge-detected outputs.

#OUTPUT :-
<img width="1031" height="989" alt="image" src="https://github.com/user-attachments/assets/9633c40e-4a1b-4932-9d5d-a912a7492701" />
