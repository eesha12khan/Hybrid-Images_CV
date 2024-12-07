# Hybrid-Images_CV
# Hybrid Image Generator
This repository contains a Python implementation for creating hybrid images, where low-frequency components of one image are combined with the high-frequency components of another to produce an interesting visual effect. The project uses OpenCV for image processing and is intended to be run in Google Colab.
# Features
  i)   Low-Frequency Image Generation: Applies Gaussian blur to create the low-frequency version of an image.
  ii)  High-Frequency Image Generation: Subtracts a blurred version from the original to isolate high-frequency details.
  iii) Hybrid Image Creation: Combines the low-frequency and high-frequency images to produce a single hybrid image.
  iv)  Visualization: Displays the generated images in Google Colab using cv2_imshow.
  v)   File Output: Saves the low-frequency, high-frequency, and hybrid images as .jpg files.
# Requirements
o Python 3.x
o OpenCV
o NumPy
o Google Colab (optional, but preferred for displaying images)
