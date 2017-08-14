# Content: Computer Vision
## Project: SwapCV

In this project I modified the original code to allow live face from a video stream.

To run the script you'll need to install dlib (http://dlib.net) including its
Python bindings, Haar Cascades and OpenCV. You'll also need to obtain the trained model from
sourceforge:
    http://sourceforge.net/projects/dclib/files/dlib/v18.10/shape_predictor_68_face_landmarks.dat.bz2
Unzip with `bunzip2` and change `PREDICTOR_PATH` to refer to this file

Get the frontal face Haar Cascade from : https://github.com/opencv/opencv/tree/master/data/haarcascades
