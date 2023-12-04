# About the Project
This project uses cv2 in the shapedetector.py file to process and detect simple shapes in a provided image file. It does this by detecting the number of vertices of a shape, up to 5 for a pentagon. Any shape with more than 5 vertices is assumed to be a circle. Image file must have a black background to make the shapes have high enough contrast to work.

### Dependencies
`pip install imutils`

## Usage Instructions
1. Navigate to folder containing the driver code, *detect_shapes.py*
2. Place any images you want to process in the same folder.
3. Run the following command, replacing \<image.jpg\> with the filename of the image you want to process: 

    `python3 detect_shapes.py --image <image.jpg>`

4. Press spacebar to iterate through the detected objects in the scene and observe them being highlighted and labeled with the detected shape.
5. Script will end when spacebar is pressed after final object is identified.
