# image_filter_demonstration

This Python program showcases various image filters or "kernels" applied to manipulate pixel values in an image. The filters include averaging, Sobel, Laplacian, median, and Gaussian filters. The program also highlights the differences between the convolve2d and filter2D functions and explores the impact of normalizing pixel values.

Averaging Filter
The program reads an image and applies a 3x3 averaging filter to smooth the grayscale image. The resulting image is displayed, demonstrating the effect of the averaging filter.

Sobel Filter
The Sobel filter is employed to detect edges in both vertical and horizontal directions. The program calculates the gradient using raw convolution (convolve2d) and OpenCV's filter2D function. The images of vertically, horizontally convolved, and the maximum edge are displayed.

Laplacian Filter
The Laplacian filter is used to highlight regions of rapid intensity change in the image. The program applies a 3x3 Laplacian filter and displays the resulting edge-detected image.

Median Filter
A median filter is employed to replace each pixel value with the median of the neighboring pixels. The program iterates through the image array, applying the median filter and displaying the denoised image.

Gaussian Filter
A Gaussian filter with a 5x5 kernel is applied to blur the image. The program uses OpenCV's filter2D function for convolution and displays the Gaussian-blurred image.

Note: Due to RAM constraints in certain environments, some figures using plt functions are commented out to prevent runtime errors. Uncommenting and running specific sections may require adjusting memory usage.
