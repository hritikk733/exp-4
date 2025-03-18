# exp-4

Gradient operators detect edges by calculating the rate of intensity change in an image.
They work by computing the first derivative of pixel values in horizontal (x) and vertical (y) directions.
Sobel and Prewitt are common operators that use convolution with specific kernels to detect edges.
The Sobel operator uses 3x3 kernels and is sensitive to both horizontal and vertical edges.
The Prewitt operator is similar to Sobel but uses different kernels, emphasizing smoother results.
Roberts Cross uses 2x2 kernels for detecting diagonal edges.
The gradient magnitude is calculated by combining the gradients in both directions, highlighting areas with rapid intensity changes.
