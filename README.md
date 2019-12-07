# Driver-Drowsiness-Detection-through-Eyelid-Closure
==========================================================================
First install the Required Libraries of Python 3.7 (python already installed)

1) Install Anaconda first (add then to the path if during installation path was not selected)
2) OpenCv:
         Open CMD and type pip install opencv-python 
         this will install the latest opencv
3)Imutils:
         pip install --upgrade imutils 
4)PlaySound:
         pip install playsound (for windows user only install playsound)
         pip install pyobjc (For Mac User install both pyobjc and playsound)
5)DLIB:
         first install visual stdio build tools for to install Cmake.
         For that go here https://visualstudio.microsoft.com/downloads/
         and select Tools for Visual stdio 2019 and under this download Build Tools for Visual Studio 2019
         
         After installing Go to CMD and Type pip install dlib 
         
Now all the libraries are set 
Now how to Run it:
  1) First download shape_predictor_68_face_landmarks.dat file from 
     https://github.com/AKSHAYUBHAT/TensorFace/blob/master/openface/models/dlib/shape_predictor_68_face_landmarks.dat 
     here
  2) keep all the files in one folder
  3) type cd "that_folder_full_path" in CMD
  4) python detect_drowsiness.py -p shape_predictor_68_face_landmarks.dat -a alarm.wav for running the file
  
  =================================================================================================================================
  
