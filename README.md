# obj-detection-cv
Object detection, tracking and classification in images methods using OpenCV

Edge Detection (1-edge-detection.ipynb):
Essential for detecting object boundaries, which is often a preliminary step in object detection workflows.

Contour Detection (3-contour-detection.ipynb):
Contours are critical for identifying shapes in images. This can be directly tied to detecting objects based on their outlines.

Corner Detection (2-corner-detection.ipynb):
Detecting corners helps in identifying key features of objects, which is important for more advanced object detection algorithms.

Template Matching (5-template-matching.ipynb):
This is a simple form of object detection where a template is used to find objects that match the shape or pattern in the image.

Feature Matching (6-feature-matching.ipynb):
More advanced than template matching, this technique compares image features, making it useful for detecting objects in various orientations or scales.

Object Detection with Color (4-object-detection-with-color.py):
Detecting objects based on color can be an effective and simple way to isolate objects if they have distinct color properties.

Watershed Algorithm (7-watershed.ipynb):
This can help in segmenting overlapping objects, which is crucial when multiple objects are close together in an image.

Face and Cat-Face Detection (8, 9, and 12):
Though specific to faces, these examples could give you insights into using OpenCV's pre-trained classifiers and Haar cascades, which can also be applied to other objects.

Pedestrian Detection (11-pedestrian-detection.ipynb):
Likely focuses on using machine learning methods or cascade classifiers to detect humans. It may contain techniques applicable to detecting other types of objects.
