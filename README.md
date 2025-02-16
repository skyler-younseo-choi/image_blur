# image_blur
📌 Overview
This project implements an image-blurring algorithm using a 3×3 averaging filter (convolution kernel). The program processes grayscale images (black and white) by replacing each pixel's value with the average of itself and its surrounding 8 neighbors. Edge pixels are handled by assuming out-of-bounds pixels have a value of 0.

🔍 How It Works
Reads a grayscale image as a 2D grid of pixel values (0–255).
Applies a 3×3 averaging filter using integer division (//) to ensure pixel values remain whole numbers.
Pixels at the edges assume out-of-bounds values as 0.
Outputs a blurred version of the image in the same format.

✨ Example
Input Image:

1   2   3  
4   5   6  
7   8   9  
Blurred Output:

1   2   1  
3   5   3  
2   4   3  
