# Image-Histogram-Analysis-and-Enhancement
This Python script analyzes image histograms and performs various histogram-based enhancements, including histogram shift, histogram equalization, and contrast stretching. These techniques aim to improve the visual quality and enhance the contrast of digital images.

# Image Histogram Analysis and Enhancement:

## Plot Corresponding Image Histogram:

Generates and plots the histogram of the input image, displaying the distribution of pixel intensities.
Histogram Shift by Value:

Shifts the histogram by a specified value, effectively changing the brightness or contrast of the image. This operation is useful for adjusting the overall brightness level.
Plot Cumulative Image Histogram:

Computes and plots the cumulative histogram of the input image, providing insights into the cumulative distribution of pixel intensities.
Histogram Equalization:

Performs histogram equalization on the input image to enhance contrast and improve visual quality. This technique redistributes pixel intensities to achieve a more balanced histogram.

Sub-steps:

Compute the cumulative distribution function (CDF) of the image histogram.
Transform pixel intensities based on the CDF to achieve a more uniform distribution.
Output the histogram-equalized image.
Plot Modified Image:

Displays the modified image resulting from histogram equalization, providing a visual comparison with the original image.
Plot Modified Image Histogram:

Generates and plots the histogram of the modified image to visualize the effects of histogram equalization.
Plot Modified Image Cumulative Histogram:

Computes and plots the cumulative histogram of the modified image, illustrating the distribution of pixel intensities after histogram equalization.
Experiment-2: Contrast Stretching

Use Image Histogram to Deduce Parameters for Contrast Stretching:

Analyzes the image histogram to determine suitable parameters for contrast stretching, such as minimum and maximum intensity values.
Apply Contrast Stretching on the Corresponding Image:

Utilizes the deduced parameters to perform contrast stretching, expanding the dynamic range of pixel intensities to enhance image contrast and improve visual clarity.
