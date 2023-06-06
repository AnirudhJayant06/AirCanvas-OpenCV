# AirCanvas_OpenCV
OpenCV library was utilized to draw on the screen captured via system’s webcam using three distinct highlighter color pens: Parrot, Dark Green, and Orange.

Steps:

1. Hardcore the HSV values of highlighter pens along with their BGR values (These HSV values of highlighter color pens is detected using a different project).
2. Captured a frame using the webcam and call ‘findColors’ method (which calls ‘getContours’ method) which returns the coordinates of pen pointer detected.
3. These new points ‘ll be added to ‘my_points’ list
4. ‘drawOnCanvas’ method was called to draw circle on the captured frame.

Project Demo: https://drive.google.com/file/d/1430bVFAydB9dYfb3qguqAYvOJB3j2_Z8/view?usp=sharing
