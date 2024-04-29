# TNSDC-Generative-AI-Colorization-of-B-W-pics
Naan Mudhalvan Project


# Colorize B&W Images with Python

This Python script allows you to colorize black and white images using deep learning techniques. It utilizes the OpenCV library for computer vision and the Tkinter library for the graphical user interface (GUI).

## Requirements

Make sure you have the following dependencies installed:

- Python 3.x
- Tkinter
- NumPy
- OpenCV (cv2)
- Pillow (PIL)
- The Python Imaging Library (PIL)
- matplotlib

You can install these dependencies using pip:

```bash
pip install numpy opencv-python pillow matplotlib


Usage
Clone or download the repository to your local machine.
Ensure that your black and white images are in a compatible format (e.g., PNG, JPEG).
Run the Python script 'main.py'.
Use the GUI to upload a black and white image by clicking on "Upload Image".
Once the image is uploaded, click on "Color Image" to colorize it.
The colorized image will be displayed in the GUI.


Files
colorize_images.py: Python script for colorizing black and white images.
models/pts_in_hull.npy: Numpy file containing pre-calculated points for colorization.
models/colorization_deploy_v2.prototxt: Model configuration file for colorization.
models/colorization_release_v2.caffemodel: Pre-trained model weights for colorization.
logo2.png: Logo image used in the GUI.


Notes
Make sure to place the pts_in_hull.npy, colorization_deploy_v2.prototxt, and colorization_release_v2.caffemodel files in the models directory.
The logo2.png file is used as the logo in the GUI. You can replace it with your own logo if desired.
Ensure that your Python environment has the required libraries installed before running the script.
The script resizes images to a fixed size (480x360) for processing. You can modify this size according to your requirements.
The colorized image will be saved as result.png in the current directory.



