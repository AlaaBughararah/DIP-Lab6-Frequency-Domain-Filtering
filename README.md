# Lab 6 — Frequency Domain Filtering

This lab applies Laplacian and Sobel filters in the frequency domain using Python and the Fast Fourier Transform (FFT).

## Objectives
- Understand frequency-domain image filtering.
- Apply the Laplacian filter to highlight edges.
- Implement Sobel filters using padded kernels and FFT.
- Combine horizontal and vertical edge responses into an edge magnitude image.

## Tools
Python, NumPy, Matplotlib, scikit-image, and Jupyter Notebook.

## Method
The image is transformed using a 2D FFT and multiplied by the filter’s frequency response. An inverse FFT converts the filtered result back to the spatial domain.

## Results
The Laplacian highlights edges and fine details. Sobel X emphasizes vertical edges, while Sobel Y emphasizes horizontal edges. Combining both Sobel responses produces a more complete edge map.
