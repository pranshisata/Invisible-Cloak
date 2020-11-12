The project's true idea is based on Harry Potter's invisible cloak. 

Dependencies:
1. Python3
2. Numpy
3. OpenCV

Algorithm:
1. Capture the background frame
2. Detect the red color cloth using color detection and segmentation algorithm
3. Segment the red cloth by generating a mask
4. Generat the final augmented output

You can capture any color other than red you just need to. You can do that by updating the HSV value.
HSV (Hue, Saturation, Value)
Hue: Hue is the colour portion of the model, expressed as a number from 0 to 360 degrees
Saturation: Saturation describes the amount of grey in a particular colour
Value: Value works in conjunction with saturation and describes the brightness or intensity of the colour, from 0–100 percent, where 0 is completely black, and 100 is the brightest
