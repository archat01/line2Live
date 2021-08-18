1. In order to train your own model please follow the tutorial in this link:
https://www.youtube.com/watch?v=oqd54apcgGE&t=155s

2. In order to feed the image from webcam activate "tensorflow" virtual environment in Anaconda, else
tensorflow won't run on GPU and the detection load will transfer to CPU.

3. Once trained export the model and use "rawImage_detection.py" to generate texture. The said Python 
script is located inside "line2Live\pythonCodes_line2Live". This code is useful for feeding 
the image through webcam only. 

4. In order to feed the Image through web interface please navigate to "line2Live_lite" 
folder and Run the "lite.py" script.

5. For web interface one need to start the Python Server as well. In order to start the server please 
navigate to "pythonServer" folder and run the "app.py" script. You may or may not use 
virtual environment though using one is always recommended.

6. Default IP of the Server is Set to "192.168.1.33:5000" which is located in the last few lines of 
app.py, please change it according to your own requirement and network settings.

7. If the set up goes well without errors, once you start the Unity 3D application named 
"testProject_unity3D" located inside "testProject_unity3D\firstBuild_absolutePath" you may see the GUI
and it will automatically spawn models of the fishes with machine synthesized textures when an image of 
a fish is scanned or shared to server.

8. If same image is shred / scanned repeatedly, it won't generate new instance of a fish, this 
functionality is introduced to avoid unwanted loading on the syste.