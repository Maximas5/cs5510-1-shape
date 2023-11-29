# About the Project
This project uses cv2 in the shapedetector.py file to process and detect simple shapes in a provided image file. It does this by detecting the number of vertices of a shape, up to 5 for a pentagon. Any shape with more than 5 vertices is assumed to be a circle.

See https://pyimagesearch.com/2016/02/08/opencv-shape-detection/ for more details on implementation.

## Usage Instructions
1. Navigate to folder containing the driver code, *detect_shapes.py*
2. Place any images you want to process in the same folder.
3. Run the following command, replacing \<image\> with the name of the image you want to process: 

    `python3 detect_shapes.py --image <image>`
