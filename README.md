# Content: Computer Vision
## Project: SwapCV

This project allows you to swap faces in real time.

To run the script you'll need to install dlib (http://dlib.net) including its
Python bindings, Haar Cascades and OpenCV. You'll also need to obtain the trained model from
sourceforge:
    http://sourceforge.net/projects/dclib/files/dlib/v18.10/shape_predictor_68_face_landmarks.dat.bz2
Unzip with `bunzip2` and change `PREDICTOR_PATH` to refer to this file

Get the frontal face Haar Cascade from : https://github.com/opencv/opencv/tree/master/data/haarcascades

### Instructions : To run this code, in the file FaceSwapCV.ipynb, on line 8 in the code block add the path of your predictor in 'PREDICTOR_PATH' variable and on line 35 add the path of your HAAR cascade classifier in the variable 'cascade_path'.

##### This project wasn't implemented from scratch. The code for swapping faces was sourced from https://matthewearl.github.io/2015/07/28/switching-eds-with-python/ and the original code was modified to allow us to implement face swap filters in real time.
