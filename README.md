# face_registering.py
This file handles the face registration process. Users can register their faces by capturing video frames from a webcam. 
The code utilizes the OpenCV and face_recognition libraries to detect and extract faces from the frames. 
It prompts the user to enter their name and captures a fixed number of frames to generate face encodings.
These face encodings, along with the corresponding names, are stored in a CSV file, serving as the face database. 
This file provides a simple and interactive way for users to register their faces and build the face database.

# face_recognition.py
This file performs the recognition step in the face recognition project. 
It utilizes the OpenCV and face_recognition libraries for face detection and recognition. 
The code captures video frames from a webcam and detects faces using the Haar cascade classifier.
It then compares the detected faces with the stored face encodings from the face database. 
If a match is found, the associated name is displayed on the frame. 
The code also draws rectangles around the detected faces for visual feedback. 
