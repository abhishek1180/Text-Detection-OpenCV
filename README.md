### Deep Learning based Text Detector in Images and videos using OpenCV and the EAST text detector.

In text detection we only detect the bounding boxes around the text. But, in text recognition, we actually find what is written in the box.

Text Recognition engines such as Tesseract require the bounding box around the text for better performance. Thus, this detector can be used to detect the bounding boxes before doing Text Recognition.

“EAST” : Efficient and Accurate Scene Text detection pipeline. The EAST pipeline is capable of predicting words and lines of text at arbitrary orientations on imagesOpenCV’s EAST text detector is a deep learning model, based on a novel architecture and training pattern. It is capable of (1) running at near real-time at 13 FPS on 720p images and (2) obtains state-of-the-art text detection accuracy.

Use OpenCV’s EAST detector to automatically detect text in both images and video streams.OpenCV’s text detector implementation of EAST is quite robust, capable of localizing text even when it’s blurred, reflective, or partially obscured.

