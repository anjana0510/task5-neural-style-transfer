# Neural Style Transfer

This project demonstrates *Neural Style Transfer*, where the artistic style of one image (e.g., a painting) is applied to the content of another image (e.g., a photograph).

## Task Objective
Apply the artistic style of one image to another using a pre-trained convolutional neural network (VGG19).

## Technologies Used
- Python
- TensorFlow
- Matplotlib
- Google Colab

## How It Works
1. Load a content image and a style image.
2. Use a pre-trained VGG19 model to extract features.
3. Define loss functions:
   - Content loss
   - Style loss
   - Total variation loss
4. Use gradient descent to generate a target image that minimizes the total loss.
5. Display and save the stylized output.

## Requirements
- TensorFlow
- NumPy
- Matplotlib
- PIL (Python Imaging Library)

You can install them with:

```bash
pip install tensorflow numpy matplotlib pillow
